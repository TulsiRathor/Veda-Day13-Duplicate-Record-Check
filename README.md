# Day 13 – Duplicate Record Check

## Project Overview
This project was completed as part of my 45-day Data Analytics Internship at Veda Technology.

The objective was to identify duplicate records in the Sample Superstore dataset using Python and Pandas.

## Tools Used
- Python
- Pandas
- Jupyter Notebook

## Dataset
Sample Superstore Dataset

- Total Records: 10,194
- Total Columns: 21

## Duplicate Check Results
- Full-row exact duplicates: 0
- Rows involved in repeated Order ID and Product ID combinations: 22
- Distinct repeated key combinations: 11

## Key Findings
No exact duplicate records were found. However, some Order ID and Product ID combinations appeared multiple times with differences in other column values.

These records were retained because they may represent valid separate sales entries.

## Files Included
- `Veda_Day13_Duplicate_Record_Check.ipynb` – Jupyter Notebook
- `Veda_Day13_Duplicate_Report.csv` – Duplicate analysis report
- `Veda_Day13_Cleaned_Copy.csv` – Cleaned dataset copy
- `Veda_Day13_Audit_Note.txt` – Audit documentation

## Conclusion
This task helped me understand how to identify duplicate records, investigate repeated key combinations, and maintain data accuracy without unnecessarily deleting valid records.

**Internship:** Veda Technology  
**Task:** Day 13 – Duplicate Record Check
