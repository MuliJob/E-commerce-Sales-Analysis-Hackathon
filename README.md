# E-commerce-Sales-Analysis-Hackathon
Analyzing an E-commerce Sales and Customer Insights Dataset to uncover trends, answer key business questions, and creating actionable insights.

# Cleaning data with excel

## Removing duplicates

- Clicked "Data" tab
- Selected "Remove Duplicates" in the "Data Tools" group
- Checked all columns to identify complete duplicate rows
- Clicked OK to remove duplicates and there was no completely duplicate rows

## Handling missing values

- Went to "Data" then "Filter"
- On each column clicked on filter dropdowns to identify blank cells
  for categorical columns e.g. Gender and region, replaced with "Unknown"
- For numerical columns e.g. age, I used this formula =IFERROR(AGE_COLUMN, MEDIAN(AGE_COLUMN_RANGE)) so that if the AGE_COLUMN has an error or blank it uses the median
- Replaced missing shipping status with pending

## Standardizing gender column

- Used "Find and Replace"
 and replaced first lowercase with capsfirst