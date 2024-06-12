# Employee Attendance Analysis Dashboard Using Power BI

## Overview

This project aims to analyze employee attendance data over the last three months and visualize the findings using Power BI. The key metrics analyzed include total workdays, present days, present percentage, sick leave percentage, and work-from-home percentage. The analysis is conducted on a monthly, weekly, and date-wise basis.

## Dataset

The dataset contains employee attendance records with the following columns:
- `Date`: The date of the record.
- `EmployeeID`: Unique identifier for each employee.
- `Status`: Attendance status (e.g., Present, Sick Leave, Work From Home).

## Analysis

### Metrics Calculated:
1. **Total Workdays**: Total number of working days in the period.
2. **Present Days**: Number of days an employee was present.
3. **Present Percentage**: (Present Days / Total Workdays) * 100.
4. **Sick Leave Percentage**: (Sick Leave Days / Total Workdays) * 100.
5. **Work From Home Percentage**: (Work From Home Days / Total Workdays) * 100.

### Analysis Dimensions:
- **Monthly Analysis**
- **Weekly Analysis**
- **Date-wise Analysis**

## Power BI Dashboard

The Power BI dashboard provides the following visualizations:
1. **Monthly Trends**:
   - Total workdays, present days, sick leave percentage, and work-from-home percentage.
2. **Weekly Trends**:
   - Similar metrics analyzed on a weekly basis.
3. **Date-wise Analysis**:
   - Detailed view of daily attendance status.

## How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/employee-attendance-analysis.git


   
### Instructions for Setting Up Power BI Dashboard

1. **Prepare the Dataset**: Ensure your dataset is formatted correctly and saved as `employee_attendance.csv`.
2. **Load Data into Power BI**:
   - Open Power BI Desktop.
   - Load the dataset (`employee_attendance.csv`) into Power BI.
3. **Create Data Model**:
   - Create necessary calculated columns and measures for total workdays, present days, present percentage, sick leave percentage, and work-from-home percentage.
4. **Create Visualizations**:
   - Use line charts, bar charts, and tables to visualize the monthly, weekly, and date-wise analysis.
5. **Publish Dashboard**:
   - Once the dashboard is ready, publish it to the Power BI service for sharing and collaboration.

By following the above steps, you will be able to analyze and visualize the employee attendance data effectively.

