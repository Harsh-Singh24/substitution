# Teacher Substitution Automation

This Python script, designed to run on Google Colab, integrates seamlessly with Google Drive and Google Sheets. It automates the substitution process for teachers marked absent on a specific day with a designated leave type, leveraging data from Google Sheets. This solution significantly reduces manual effort, bringing down operation time from 1 hour to just 2 minutes.

## Features

- **Libraries Used**: 
  - `numpy`
  - `pandas`
  - `seaborn`
  - `datetime`
  - `collab`
  - `gsread`
  
- **Data Extraction**: Extracts teachers' timetables directly from Google Sheets.

- **Data Preprocessing**: Utilizes `pandas` for efficient data preprocessing, converting raw data into a structured format suitable for processing.

- **Efficiency Improvement**: Automates the substitution process, reducing manual work and operation time from 1 hour to just 2 minutes.

- **Leave Management**: Handles five different leave types with precision, ensuring accurate substitution results.

- **Workload Balancing**: Ensures that the total workload for teachers does not exceed 7 lectures per day.

- **Exclusion of HODs**: Ensures that Heads of Departments (HODs) are not assigned as substitutes.

## Benefits

This automation enhances operational efficiency, eliminates manual errors, and provides a streamlined approach to managing teacher substitutions.

---
