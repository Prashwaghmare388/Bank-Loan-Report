# Bank Loan Reports

## Project Objective
Welcome to the Bank Loan Reports project, This repository contains a comprehensive analysis of bank loan data, providing dashboards and detailed metrics for better decision-making.

## Dataset Used
- <a href="https://github.com/Prashwaghmare388/Bank-Loan-Report/blob/main/Bank%20Loan%20Report.xlsx">Dataset</a>

## Questions (KPIs)

Key Performance Indicators (KPIs) Requirements:

1. Total Loan Applications: We need to calculate the total number of loan applications received during a specified period. Additionally, it is essential to monitor the Month-to-Date (MTD) Loan Applications and track changes Month-over-Month (MoM).
2. Total Funded Amount: Understanding the total amount of funds disbursed as loans is crucial. We also want to keep an eye on the MTD Total Funded Amount and analyse the Month-over-Month (MoM) changes in this metric.
3. Total Amount Received: Tracking the total amount received from borrowers is essential for assessing the bank's cash flow and loan repayment. We should analyse the Month-to-Date (MTD) Total Amount Received and observe the Month-over-Month (MoM) changes.
4. Average Interest Rate: Calculating the average interest rate across all loans, MTD, and monitoring the Month-over-Month (MoM) variations in interest rates will provide insights into our lending portfolio's overall cost.
5. Average Debt-to-Income Ratio (DTI): Evaluating the average DTI for our borrowers helps us gauge their financial health. We need to compute the average DTI for all loans, and MTD, and track Month-over-Month (MoM) fluctuations.



Good Loan v Bad Loan KPI’s
In order to evaluate the performance of our lending activities and assess the quality of our loan portfolio, we need to create a comprehensive report that distinguishes between 'Good Loans' and 'Bad Loans' based on specific loan status criteria
Good Loan KPIs:
1. Good Loan Application Percentage: We need to calculate the percentage of loan applications classified as 'Good Loans.' This category includes loans with a loan status of 'Fully Paid' and 'Current.'
2. Good Loan Applications: Identifying the total number of loan applications falling under the 'Good Loan' category, which consists of loans with a loan status of 'Fully Paid' and 'Current.'
3. Good Loan Funded Amount: Determining the total amount of funds disbursed as 'Good Loans.' This includes the principal amounts of loans with a loan status of 'Fully Paid' and 'Current.'
4. Good Loan Total Received Amount: Tracking the total amount received from borrowers for 'Good Loans,' which encompasses all payments made on loans with a loan status of 'Fully Paid' and 'Current.'
Bad Loan KPIs:
5. Bad Loan Application Percentage: Calculating the percentage of loan applications categorized as 'Bad Loans.' This category specifically includes loans with a loan status of 'Charged Off.'
6. Bad Loan Applications: Identifying the total number of loan applications categorized as 'Bad Loans,' which consists of loans with a loan status of 'Charged Off.'
Bad Loan Funded Amount: Determining the total amount of funds disbursed as 'Bad Loans.' This comprises the principal amounts of loans with a loan status of 'Charged Off.'
7. Bad Loan Total Received Amount: Tracking the total amount received from borrowers for 'Bad Loans,' which includes all payments made on loans with a loan status of 'Charged Off.'


## Dataset Interaction 1
- <a href="https://github.com/Prashwaghmare388/Bank-Loan-Report/blob/main/Summery%20Dashboard.png"> Summery Dashboard</a>

DASHBOARD 2: OVERVIEW
In our Bank Loan Report project, we aim to visually represent critical loan-related metrics and trends using a variety of chart types. These charts will provide a clear and insightful view of our lending operations, facilitating data-driven decision-making and enabling us to gain valuable insights into various loan parameters. Below are the specific chart requirements:
1. Monthly Trends by Issue Date (Line Chart):
Chart Type: Line Chart
Metrics: 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received'
X-Axis: Month (based on 'Issue Date')
Y-Axis: Metrics' Values
Objective: This line chart will showcase how 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received' vary over time, allowing us to identify seasonality and long-term trends in lending activities.
2. Regional Analysis by State (Filled Map):
Chart Type: Filled Map
Metrics: 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received'
Geographic Regions: States
Objective: This filled map will visually represent lending metrics categorized by state, enabling us to identify regions with significant lending activity and assess regional disparities.
3. Loan Term Analysis (Donut Chart):
Chart Type: Donut Chart
Metrics: 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received'
Segments: Loan Terms (e.g., 36 months, 60 months)
Objective: This donut chart will depict loan statistics based on different loan terms, allowing us to understand the distribution of loans across various term lengths.
4. Employee Length Analysis (Bar Chart):
Chart Type: Bar Chart
Metrics: 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received'
X-Axis: Employee Length Categories (e.g., 1 year, 5 years, 10+ years)
Y-Axis: Metrics' Values
Objective: This bar chart will illustrate how lending metrics are distributed among borrowers with different employment lengths, helping us assess the impact of employment history on loan applications.
5. Loan Purpose Breakdown (Bar Chart):
Chart Type: Bar Chart
Metrics: 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received'
X-Axis: Loan Purpose Categories (e.g., debt consolidation, credit card refinancing)
Y-Axis: Metrics' Values
Objective: This bar chart will provide a visual breakdown of loan metrics based on the stated purposes of loans, aiding in the understanding of the primary reasons borrowers seek financing.

6. Home Ownership Analysis (TreeMap):
Chart Type: Tree Map
Metrics: 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received'
Hierarchy: Home Ownership Categories (e.g., own, rent, mortgage)
Objective: This treemap will display loan metrics categorized by different home ownership statuses, allowing for a hierarchical view of how home ownership impacts loan applications and disbursements.

## Dataset Interaction 2
- <a href="https://github.com/Prashwaghmare388/Bank-Loan-Report/blob/main/Overview%20Dashboard.png"> Overview Dashboard</a>

## Summary Dashboard:

Key Performance Indicators (KPIs) include Total Loan Applications, Funded Amount, Amount Received, Average Interest Rate, and Debt-to-Income Ratio.

Segmentation into Good Loans (Fully Paid, Current) and Bad Loans (Charged Off).

## Summary Dashboard
![Summery Dashboard](https://github.com/user-attachments/assets/4eeec4e0-6503-4541-8398-bfdc9b10f10a)



## Overview Dashboard:

Visual representation through charts including Line Charts (Monthly Trends), Maps (Regional Analysis), Donut Charts (Loan Term Analysis), Bar Charts (Loan Purpose Breakdown), and Tree Maps (Home Ownership Analysis).

## Overview Dashboard
![Overview Dashboard](https://github.com/user-attachments/assets/2a6fc47d-a3ac-443f-84df-e2c55de29031)


DASHBOARD 3: DETAILS
In our Bank Loan Report project, we recognize the need for a comprehensive 'Details Dashboard' that provides a consolidated view of all the essential information within our loan data. This Details Dashboard aims to offer a holistic snapshot of key loan-related metrics and data points, enabling users to access critical information efficiently.
Objective:
The primary objective of the Details Dashboard is to provide a comprehensive and user-friendly interface for accessing vital loan data. It will serve as a one-stop solution for users seeking detailed insights into our loan portfolio, borrower profiles, and loan performance.
