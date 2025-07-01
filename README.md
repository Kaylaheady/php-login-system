# PHP Login System

## Overview
This is a basic PHP & MySQL login system with 1-minute inactivity timeout.

## Session Handling
Each successful login stores `$_SESSION["last_activity"]`. If the user is inactive > 60 sec, they’re logged out automatically.

## Known Issues
- Passwords are plain text (for demo).
- Only one user in the DB.

## Files
- login.php - login form and processing
- admin.php - protected admin area
- logout.php - ends session
- error.php - login fail page
- db_config.php - DB connection
- create_users_table.sql - for database setup
