# Fleet-Maintenance-Analysis
This project analyzes vehicle maintenance data across different U.S. states and regions using SQL and Tableau. It was developed to identify trends in repairs and help stakeholders understand where and why repairs occur most frequently.

## Overview

Using a CSV dataset of vehicle repair records, I:

- Uploaded the data into MySQL Workbench
- Cleaned and joined tables to enrich the dataset
- Created a `regions` table to categorize U.S. states into 5 standard regions (Northeast, Southeast, Midwest, Southwest, West)
- Queried key repair patterns such as:
  - Most common repair types
  - Repairs by region and state
  - Fuel tank failures and their reasons

The final dashboard was built in Tableau Public and visually presents:
- Repair count by state (map view)
- Repair frequency by type (bar chart)
- Regional breakdown of repairs

##  Files Included

- `FleetMaintenanceRecords.csv` – Original dataset
- `regions.csv` – Region mapping table
- `FleetMaintenanceDashboard.twb` – Tableau dashboard file
- `README.md` – This file

## Tools Used

- MySQL Workbench
- Tableau Public
- Microsoft Excel (for CSV prep)

## Key SQL Skills Demonstrated

- GROUP BY and COUNT queries
- INNER JOIN between vehicle and region tables
- Filtering with WHERE and IN clauses
- Creating new tables and inserting batch records
- Exporting CSV data for visualization

This project was created as part of the DAD-220 SQL course, focusing on practical database analysis and data visualization.
