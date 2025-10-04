# Data Quality Checks for Billing Data Warehouse

## Overview
This project implements data quality checks for a billing data warehouse. It provides automated verification of data integrity, consistency, and validity through various test cases.

## Project Structure
- **dbconnect.py**: Database connection configuration  
- **dataqualitychecks.py**: Core data quality check functions  
- **generate-data-quality-report.py**: Main script to run tests and generate reports  
- **mytests.py**: Test case definitions  
- **setupstagingarea.sh**: Shell script to set up the staging environment  

## Features
- Null value detection
- Min/Max range validation
- Valid value checking
- Duplicate entry detection
- Automated test reporting

## Data Quality Checks
The project implements four main types of data quality checks:

### Null Check
Verifies if specific columns contain null values

### Min/Max Range Check
Validates if numeric values fall within expected ranges

### Valid Values Check
Ensures categorical data only contains predefined valid values

### Duplicate Check
Identifies duplicate entries in specified columns

## Setup
1. Configure PostgreSQL credentials in `dbconnect.py`
2. Run the staging area setup:

