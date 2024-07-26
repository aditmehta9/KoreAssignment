Here's a README template that incorporates details about how you completed the task and the methodologies used:

---

# SSIS Home Task - Adit Mehta

## Overview

This repository contains the solution for the SSIS home task assigned as part of the recruitment process. The task involved developing an ETL process using SQL Server Integration Services (SSIS) to extract, transform, and load data from a CSV file into a SQL Server production table via a staging table.

## Task Description

1. **Data Extraction and Type Standardization to Staging Table:**
   - **Extract:** Utilized an SSIS package to read data from a CSV file. The source data, originally in string format, was prone to errors.
   - **Transform:** Loaded the data into a staging table, converting string values into appropriate SQL data types (int, string, float, date, etc.) to ensure compatibility and accuracy for further processing.

2. **Data Cleaning in Staging Table:**
   - **Remove Duplicates:** Implemented logic to identify and remove duplicate records based on specific criteria or key columns.
   - **Handle Error Records:** Isolated records with data quality issues (e.g., null values in non-nullable fields, incorrect formats) for review and correction.

3. **Incremental Load to Production Table:**
   - **Load:** Created a data flow from the staging table to the production table, ensuring it included an ID column for unique record identification. Differentiated new from existing records based on ID and implemented logic to insert new records and update existing records.

## Setup and Execution

1. **Repository Setup:**
   - Created a public GitHub repository to host the SSIS solution and database backup.

2. **ETL Process Implementation:**
   - Developed an SSIS package with multiple components, including Data Flow Tasks, Transformation Components, and Control Flow elements to handle the extraction, transformation, and loading processes.

3. **Handling Discrepancies:**
   - Addressed discrepancies and ambiguities in the data, task description, or schema by adapting the approach to ensure accurate data processing and integration.

4. **Code Quality:**
   - Ensured that all code and SQL queries are clean, well-commented, and follow best practices for performance, security, and maintainability.

## Execution Report

- **Records Processed:** [30]
- **Excluded Records:** [4]
- **Challenges Faced:**
  - Data format inconsistencies and how they were addressed.
  - Handling large datasets and ensuring efficient processing.

## Instructions for Running the Solution

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/aditmehta9/KoreAssignment.git
   ```

2. **Open SSIS Package:**
   - Use SQL Server Data Tools (SSDT) to open the `Kore_Project.dtsx` file located in the `Kore Project` directory.

3. **Review and Execute ETL Process:**
   - Review the ETL process configuration.
   - Execute the SSIS package to run the ETL process and load data into the staging and production tables.

## Conclusion

This task demonstrates the ability to handle real-world ETL scenarios, manage data types, clean data, and implement incremental updates. The solution was developed with a focus on code quality, error handling, and comprehensive documentation.

---

Screenshots:

<img width="1380" alt="Screenshot 2024-07-25 at 8 06 09 PM" src="https://github.com/user-attachments/assets/5bf249d7-ca63-43ed-83e4-56dcb4502b25">
<img width="1376" alt="Screenshot 2024-07-25 at 8 04 45 PM" src="https://github.com/user-attachments/assets/37807a10-be2a-4c24-bdad-ee2e5d72bc31">
<img width="1919" alt="Screenshot 2024-07-25 at 7 43 32 PM" src="https://github.com/user-attachments/assets/aa3967f3-a2a5-45da-b32b-0b648b3c4de0">
<img width="972" alt="Screenshot 2024-07-25 at 7 43 19 PM" src="https://github.com/user-attachments/assets/fe3edd14-4b3e-44fb-bf1b-5c52bc7264f6">
<img width="960" alt="Screenshot 2024-07-25 at 7 43 13 PM" src="https://github.com/user-attachments/assets/96010fbd-6e09-461e-9c4e-3cdf711975ae">
