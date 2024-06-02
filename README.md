Thank you for providing the data file. Here’s the updated README section that reflects this change and includes the direct reference to the uploaded file:

---

## Kansas City 311 Service Requests Analysis

### Overview
This project focuses on analyzing the 311 service requests data from Kansas City to gain insights into the types and frequency of issues reported by residents. The analysis aims to identify trends, patterns, and potential areas for improvement in the city's response to these requests.

### Scope of Work

1. **Creating Visualizations**:
   - Utilize Tableau and Power BI to create visualizations based on the business requirements provided.

2. **Perform Data Profiling**:
   - Understand the data and identify inconsistencies by performing data profiling.

3. **Data Staging for Ad-Hoc Analysis**:
   - Use SQL and visualization tools to perform data staging for ad-hoc analysis.

### Data Connection and Preparation

- **Connect to Databases**:
  - Connect Power BI and Tableau to the Azure SQL database, SQL Server database, or MySQL.
  - Utilize the staging table loaded in these databases to build visualizations.

### Implementation

- **Data Availability**:
  - The data is available in the repository: [311_CallCenterServiceRequests_KansasCity_2007-March2021.tsv.zip](https://github.com/vaishnavipatel-15/Kansas-City-311-Service-Requests-Analysis/releases/download/v1.0/311_CallCenterServiceRequests_KansasCity_2007-March2021.tsv.zip).
  - For reference, visit the [open data website](https://data.kcmo.org/311/311-Call-Center-Service-Requests/4y5b-s6ew): `311 Kansas City 2007-2011`.
  - Use the provided zip file which contains the TSV file needed for analysis.

1. **Data Profiling with Alteryx**:
   - Use Alteryx to profile the TSV data and identify issues such as missing values, duplicates, date formats, data conversions, special characters, and inconsistencies.

2. **Data Population**:
   - Populate data into Microsoft SQL database, Azure SQL database, or local MySQL database using Alteryx.

### Business Questions to Build Visualization

1. **Service Requests Over Time**:
   - Analyze the trend in service requests over the years 2018-2021 and monthly variations.

2. **Volume of Service Requests by Source**:
   - Examine the overall trend in service requests received from different sources.

3. **Volume of Service Requests by Department**:
   - Analyze the trend in service requests received by various departments.

4. **Top 10 Performance Metrics (Response Time)**:
   - Identify the top 10 cases with the fastest response times, categorized by Category1 and Type of Request.

5. **Geographical Visualization**:
   - Identify the top 10 areas with the highest number of service requests.

6. **Departmental Workload Comparison**:
   - Compare the workload among different departments and work groups using visual representations.

7. **Response Time Analysis**:
   - Visualize the distribution of response times for each department and identify any outliers or patterns.

8. **Service Request Status Composition**:
   - Create a visualization to show the composition of service request statuses (open, closed, in progress) and how this composition has changed over the years 2018-2021.

9. **Time to Closure Analysis**:
   - Visualize the average days to close service requests for each category1 and identify categories with consistently longer closure times.

10. **Workload Efficiency**:
    - Create a visualization to show the relationship between workload (number of service requests) and efficiency (days to close) for each department.


### Power BI Report

You can download the Power BI file from the [Releases section](https://github.com/vaishnavipatel-15/Kansas-City-311-Service-Requests-Analysis/releases).

Ensure that your dashboards are clear, visually appealing, and provide insightful answers to the questions posed. Use appropriate charts, graphs, and visual elements to effectively convey your findings.

---

This README update should now correctly guide users on the data file usage and provide a comprehensive overview of the project.
