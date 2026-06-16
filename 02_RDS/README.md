# 02 - RDS Database Setup

## Overview
Created AWS RDS MySQL database for the vprofile application backend.

## Steps Performed
- Created RDS MySQL instance (vprords)
- Engine Version: MySQL 8.0.45
- Instance Class: db.t3.micro
- Master Username: admin
- Database Name: accounts
- VPC Security Group: vproids-sg
- Connected to RDS via EC2 instance
- Imported database backup (db_backup.sql)
- Verified tables: role, user, user_role