# ECU-Testing-QA-Power-BI-Dashboard
📊 **Overview**

This project is a 3-page interactive Power BI dashboard built to analyze automotive ECU test execution and QA performance. It simulates real automotive test data across modules like BMCM, BMS, Gear Indicator, Wiper System, and Body Control Module.

-The dashboard helps QA teams understand:

1.Test Execution Status

2.Pass/Fail Trends

3.Automation Coverage

4.Defect Severity Distribution

5.Module-wise Efficiency

6.Requirement Coverage




📁 **Dashboard Pages**

1️⃣ **Test Execution Overview**

KPIs: Pass Rate, Fail Rate, Total Tests, Automation %, Avg Execution Time

1.Test trend over time

2.Module-wise pass/fail comparison

3.Automated vs Manual distribution

4.Slicers for filtering

<img width="1460" height="757" alt="Screenshot 2025-11-22 194123" src="https://github.com/user-attachments/assets/c271b78b-45aa-4193-abe7-80e4ba6a1550" />





2️⃣ **Defect Analysis**

1.Total defects, critical/major/minor defects

2.Defects by module & status

3.Severity distribution (donut chart)

4.Detailed defect table with conditional formatting
<img width="1410" height="817" alt="Screenshot 2025-11-22 194309" src="https://github.com/user-attachments/assets/c220ef26-a332-4b91-927d-932f2c7b48f0" />




3️⃣**Coverage and efficiency**

1.Requirement coverage % (Gauge)

2.Automation vs Manual by module

3.Execution time trends

4.Module-wise efficiency table
<img width="1422" height="818" alt="Screenshot 2025-11-22 194401" src="https://github.com/user-attachments/assets/bc94d1c0-f0ea-4d52-b367-78a23d170833" />




🛠 **Tech Stack**

Power BI Desktop

DAX (Data Analysis Expressions)

Power Query

Excel (Simulated Test Data)


📂**Dataset**

The dataset contains 300+ test scenarios with columns like:

Test_ID

Module

Tester

Date

Result

Automated (Y/N)

Execution_Time

Defect_ID, Severity, Status

Requirement_Covered


🚀 **How to Use**

1.Clone the repository

2.Download ECU_Test_Data.xlsx

3.Open ECU_QA_Dashboard.pbix in Power BI

4.Refresh the dashboard

5.Explore and analyze!



**Author:
Shreya Maidaragi**
