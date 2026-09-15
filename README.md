### Customer Churn Analysis and Prediction

## Analysis by Demographics
<img width="1358" height="707" alt="Screenshot 2026-09-16 020548" src="https://github.com/user-attachments/assets/9d086cb9-bee7-4843-86d9-5d5a29416169" />

## Churn Analysis
<img width="1362" height="716" alt="Screenshot 2026-09-16 020600" src="https://github.com/user-attachments/assets/40b072a0-171d-423b-9331-eff599fbb261" />

## Trend Analysis
<img width="1350" height="712" alt="Screenshot 2026-09-16 020610" src="https://github.com/user-attachments/assets/de417355-7480-4f02-958b-5be695d03bcb" />

## Overview
<img width="1357" height="711" alt="Screenshot 2026-09-16 020631" src="https://github.com/user-attachments/assets/e458fcd8-e1e3-4a36-b4c9-28a939fd002b" />


## Table of Contents
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools Used](#tools-used)
- [Data Preparation](#data-preparation)
- [Key Insights](#key-insights)
- [Recommendations](#recommendations)

### Project Overview
The project analyzes customer churn in a telecommunications company to identify primary churn drivers and at-risk accounts, delivering actionable data-driven strategies to improve customer retention.

### Data Source 
Customer Churn Dataset: Provided through the SaiKet Systems Internship Program, containing customer demographic information, account tenure, contract types, payment methods, and subscribed services.

### Tools Used 
- **Power BI Desktop:** Data transformation, DAX modeling, and multi-page interactive dashboard development.
- **Power Query:** Data cleaning, type formatting, and binning.

### Data Preparation
1. **Data Connection:** Imported the customer churn dataset into Power BI Desktop.
2. **Data Transformation:** Handled missing values, formatted data types, and created tenure bins for distribution analysis.
3. **Data Analysis & DAX:** Created measures for Churn Rate %, Total Charges, Average Tenure, and segmented churn metrics.
4. **Data Visualization:** Built a structured 4-page report (Demographics, Churn Drivers, Trend Analysis, and Executive Overview).

### Key Insights

**1. Overall Churn Metrics:**
- **Customer Base:** Out of 7,043 total customers, 1,869 churned, resulting in an overall **Churn Rate of 26.54%**.
- **Revenue Exposure:** The customer base represents **$16.06M in total charges** and **$456.12K in monthly recurring charges**.
- **Tenure Benchmark:** The average customer tenure is **32.37 months**, with churn risk heavily concentrated in the early subscription stages.

**2. Core Churn Drivers:**
- **Contract Commitment:** Customers on **Month-to-month contracts** exhibit the highest vulnerability with a **42.71% churn rate**, compared to **11.27% for 1-Year** and **2.83% for 2-Year** contracts.
- **Internet Service:** Users with **Fiber Optic** internet churn at **41.89%** overall (peaking at **54.61% on Month-to-month**), significantly higher than DSL users (**18.96%**).
- **Payment Methods:** Customers utilizing **Electronic Check** represent the highest count of churned accounts among all payment categories.
- **Tenure Risk:** Churn drops drastically after the first 12 months; the highest attrition occurs within months 1–6.

### Recommendations
- **Contract Conversion Incentives:** Provide discounted 1-year commitments or bundled perks to transition high-risk "Month-to-month" subscribers to annual agreements.
- **Fiber Optic Quality & Pricing Audit:** Conduct a service reliability and pricing review for Fiber Optic offerings to address high churn on premium-tier connections.
- **Early-Tenure Loyalty Programs:** Deploy automated milestone check-ins and loyalty rewards at months 6 and 12 to guide new users past the early attrition window.
- **Payment Method Migration:** Incentivize auto-pay via bank transfer or credit card to reduce high attrition linked with manual electronic checks.
