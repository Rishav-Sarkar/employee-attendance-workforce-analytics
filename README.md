Employee Attendance & Workforce Analytics Dashboard

An interactive workforce analytics solution developed using Google Looker Studio, analyzing 55,374 employee attendance records across 980 employees over a three-month period.

The project transforms raw attendance data into a structured business intelligence dashboard covering attendance, workforce distribution, departments, locations, shifts, work modes, productive hours, overtime, and workforce trends.

Project Highlights

Metric	Value
Attendance Records	55,374
Unique Employees	980
Departments	10
Locations	5
Shift Types	5
Employment Types	4
Analysis Period	Jan 2 – Mar 31, 2026
Attendance Statuses	3

Project Objective

The objective of this project was to analyze a large employee attendance dataset and convert raw attendance records into meaningful workforce insights through an interactive dashboard.

The analysis focuses on:

* Employee attendance patterns
* Workforce distribution
* Department-level attendance
* Location-wise employee distribution
* Shift-wise attendance
* Work-mode distribution
* Productive working hours
* Overtime
* Monthly workforce trends
* Late-arrival and early-exit patterns

The dashboard is designed to provide both a high-level workforce overview and a more detailed productivity analysis.

Dataset

The dataset contains 55,374 employee attendance records representing 980 unique employees across January, February, and March 2026.

The data contains 22 fields covering employee information, attendance, working patterns, and productivity metrics.

Key Dimensions

* Employee
* Department
* Location
* Employment Type
* Shift
* Attendance Date
* Attendance Status
* Work Mode

Key Metrics

* Login Time
* Logout Time
* Productive Hours
* Break Duration
* Overtime Hours
* Late Arrival
* Early Exit

Attendance Status

* Present
* Half Day
* On Leave

Work Mode

* Work From Office
* Work From Home
* Client Site

Data Preparation

Before building the dashboard, the raw dataset was reviewed and prepared for analysis.

The data preparation process included:

* Reviewing dataset structure and field types
* Validating attendance records
* Standardizing categorical fields
* Reviewing date and time fields
* Checking missing values
* Validating working-hour metrics
* Reviewing overtime values
* Reviewing late-arrival and early-exit fields
* Preparing calculated metrics for dashboard reporting

Data Quality Handling

Records marked as On Leave naturally contain no login or logout activity and therefore have zero productive hours.

These records were treated as valid attendance-status records rather than incorrectly categorizing the absence of working-time values as missing or erroneous data.

Key Performance Indicators

The dashboard incorporates multiple workforce KPIs.

Total Employees

980 unique employees

Attendance Records

55,374 employee attendance records

Attendance Rate

The overall Present rate across the dataset is approximately:

93.1%

Attendance Rate =
Present Records / Total Attendance Records × 100

Average Productive Hours

* All attendance records: 7.73 hours
* Present records: 8.21 hours

Total Overtime

8,308.79 hours

Attendance Analysis

The overall attendance distribution is:

Attendance Status	Records	Percentage
Present	51,553	93.1%
Half Day	1,186	2.1%
On Leave	2,635	4.8%
Total	55,374	100%

The dashboard uses these categories to provide an overview of employee attendance patterns across departments, locations, shifts, and other workforce dimensions.

Workforce Distribution

The dashboard analyzes workforce distribution across multiple dimensions.

Departments

The dataset contains 10 departments, including:

* Engineering
* Sales
* Customer Success
* HR
* Design
* Operations
* Finance
* Marketing
* Data Science
* Product Management

Locations

Employee distribution is analyzed across 5 office locations.

Shifts

Attendance patterns are analyzed across 5 shift types.

Employment Types

The dataset contains 4 employment types, enabling further segmentation of the workforce.

Work Mode Analysis

Among Present records, the approximate work-mode distribution is:

Work Mode	Share
Work From Office	76.4%
Work From Home	20.7%
Client Site	2.9%

This provides visibility into the organization’s working model and the relative distribution of different workplace arrangements.

Productivity & Overtime Analysis

The project goes beyond basic attendance reporting by analyzing productive hours and overtime.

Month	Present Records	Avg. Productive Hours	Overtime Hours
January	17,040	7.56	1,934.93
February	17,131	7.60	2,190.71
March	17,382	8.03	4,183.15

The analysis shows that average productive hours increased from 7.56 hours in January to 8.03 hours in March.

Monthly overtime also increased during the period, with March recording 4,183.15 hours, the highest monthly overtime volume in the dataset.

Department Analysis

Department-level analysis provides a more granular view of workforce attendance.

Some of the largest departments by attendance-record volume are:

Department	Attendance Records
Engineering	16,457
Sales	8,322
Customer Success	6,483

Attendance rates across the 10 departments were also calculated to enable comparative analysis alongside productivity and overtime metrics.

Dashboard

The project consists of two interactive pages developed in Google Looker Studio.

Page 1 — Attendance Overview

The first page provides a consolidated view of employee attendance and workforce distribution.

Analysis Areas

* Total Employees
* Attendance Rate
* Attendance Status
* Department-wise Attendance
* Location-wise Employee Distribution
* Shift-wise Attendance Status
* Work-mode Distribution
* Attendance Trends
* Interactive Filtering

Purpose

The page provides a high-level overview of workforce attendance and enables users to analyze attendance patterns across different organizational dimensions.

Dashboard Preview

Page 2 — Workforce Productivity Analysis

The second page focuses on productivity and workforce working patterns.

Analysis Areas

* Productive Hours
* Average Productive Hours
* Overtime Hours
* Monthly Productivity Trends
* Department-level Analysis
* Work-mode Analysis
* Late-arrival Patterns
* Early-exit Patterns
* Detailed Workforce Analysis

Purpose

The page extends the attendance analysis into productivity and operational workforce metrics.

Dashboard Preview

Key Insights

1. Overall Attendance

The dataset records an overall 93.1% Present rate across 55,374 employee attendance records.

2. Increasing Productive Hours

Average productive hours increased from 7.56 hours in January to 8.03 hours in March.

3. Overtime Growth

Monthly overtime increased from 1,934.93 hours in January to 4,183.15 hours in March.

4. Work From Office Dominance

Work From Office accounts for approximately 76.4% of Present records, making it the dominant work mode within the dataset.

5. Department-level Analysis

Attendance rates across departments remain within a relatively narrow range, allowing attendance patterns to be examined alongside productivity, overtime, and workforce distribution.

Interactive Dashboard

The complete interactive dashboard is available through Google Looker Studio.

View Interactive Dashboard

Replace YOUR_LOOKER_STUDIO_LINK with the published Looker Studio URL.

Tools & Technologies

Area	Technology
Data Source	CSV
Data Preparation	Google Sheets / Data Cleaning
Data Analysis	Exploratory Data Analysis, KPI Analysis
Visualization	Google Looker Studio
Documentation	Markdown
Version Control	GitHub

Skills Demonstrated

This project demonstrates practical experience in:

* Data Cleaning
* Data Preparation
* Data Transformation
* Exploratory Data Analysis
* KPI Development
* Workforce Analytics
* HR Analytics
* Business Intelligence
* Data Visualization
* Dashboard Development
* Trend Analysis
* Dimensional Analysis
* Data Interpretation
* Google Looker Studio
* Google Sheets
* GitHub

Repository Structure

employee-attendance-analytics/
│
├──  employee_attendance.csv
│
├── Dashboard/
│   ├── Attendance_Overview.png
│   └── Workforce_Productivity_Analysis.png
│
├── README.md

Future Enhancements

Potential future enhancements include:

* Automated data refresh
* Live database integration
* Attendance anomaly detection
* Absenteeism trend analysis
* Productivity benchmarking
* Overtime forecasting
* Workforce segmentation
* Automated monthly HR reporting
* Integration with additional HR datasets

Data Privacy

This project is intended for portfolio and analytical demonstration purposes.

Before publishing the dataset publicly, personally identifiable or sensitive employee information should be removed or anonymized.

The repository should not contain:

* Personal phone numbers
* Personal email addresses
* Government identification numbers
* Salary information
* Passwords or credentials
* Other sensitive employee information

Author

Rishav Sarkar

Data Analyst | Business Analyst | AI/ML Enthusiast

GitHub: [Rishav-Sarkar](https://github.com/Rishav-Sarkar)

LinkedIn: [Rishav Sarkar](https://www.linkedin.com/in/rishav-s-553333145/)
