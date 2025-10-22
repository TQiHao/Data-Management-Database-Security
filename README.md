# Data Management & Security

Database security, access control, and backup management, focusing on user privileges, constraint validation, and database backup/restore operations.

## Assignment Details
- **Course**: CSIT115 Data Management and Security
- **Focus**: Database Security, Access Control & Backup Management
- **Tasks**: User Management, Constraint Validation, and Backup Operations

## Project Description
This assignment covers advanced database administration topics:
- **Task 1**: User creation and privilege management with GRANT statements
- **Task 2**: Complex constraint validation using SELECT queries
- **Task 3**: Database backup/restore operations and change tracking

## Tasks Completed

### Task 1: Database Security & User Management
- User creation with specific naming conventions
- GRANT statements for privilege assignment
- ALTER USER for resource limits and password management
- Privilege verification and user management

### Task 2: Constraint Validation
- Complex SELECT query to identify constraint violations
- Data integrity checking between INCLIENT and OUTCLIENT tables
- Unique record identification and reporting

### Task 3: Backup & Restore Operations
- mysqldump for logical database backups
- Database restoration and table modification
- Change tracking between database states
- Record comparison for added, modified, and deleted data

## Files
- `CSIT115_Assn3 - 2025S2.pdf` - Assignment specification and requirements
- `A3create.sql` - Database table creation script
- `A3load.sql` - Database data loading script
- `A3drop.sql` - Database cleanup script
- `A3task3change.sql` - Database modification script for Task 3
- `T03_8931914_TohQiHao_task1.txt` - Task 1 solutions (user management)
- `T03_8931914_TohQiHao_task2.txt` - Task 2 solutions (constraint validation)
- `T03_8931914_TohQiHao_task3.txt` - Task 3 solutions (backup/restore operations)
- `8931914.bak` - Database backup file

## Database Schema
Healthcare database system including:
- **PHYSICIAN** - Doctor information and credentials
- **CLIENT** - Patient information and records
- **INCLIENT** - Inpatient details (ward and bed assignments)
- **OUTCLIENT** - Outpatient details (day bed information)
- **PRESCRIPTION** - Medication prescriptions
- **DRUG** - Pharmaceutical drug information

## Technologies Used
- MySQL Database Management System
- User Access Control (GRANT/REVOKE statements)
- Privilege Management and Resource Limits
- Discretionary Access Control (DAC)
- Database Backup and Restore (mysqldump)
- Logical Backup Operations
- Constraint Validation and Data Integrity
- Complex SELECT Queries with JOINs
- ALTER USER Operations
- Password Management and Security
- Change Tracking and Data Comparison
- Command Line Database Tools

## Security Concepts Implemented

### Access Control:
- User creation and authentication
- Privilege hierarchy and grant options
- Resource limitation enforcement
- Password expiration policies

### Data Integrity:
- Constraint validation queries
- Business rule enforcement
- Data consistency checks

### Backup Management:
- Logical backup creation
- Database restoration procedures
- Change detection and tracking

## Author
Toh Qi Hao - CSIT115 Data Management and Security
