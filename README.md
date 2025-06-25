# Fraud Analytics Dashboard
## Overview
This interactive Power BI dashboard provides a comprehensive overview of fraudulent financial transactions across various devices, payment methods, and user profiles. The dashboard is designed to help financial institutions and analysts identify fraud patterns, high-risk channels, and user behavior trends that may indicate potential security threats.
![Image](https://github.com/user-attachments/assets/05736010-bef3-4c13-bc61-c3816977b9bd)

## The visualizations are structured to highlight:
* Total transaction volumes
* Devices and methods most associated with fraud
* User activity with the highest transaction volumes
* Time-bound transaction summaries
## Key Insights & Observations
### 1. Device Involvement in Fraudulent Activity
* Mobile devices recorded the highest number of fraudulent transactions (806), surpassing both desktops (748) and tablets (729).
* A small portion of transactions originated from unknown devices (75), which could indicate tampering or non-standard access points.
### 2. Fraud-Prone Payment Methods
* Bill Payments emerged as the most fraud-prone transaction type.
* Fraudulent transaction value is distributed equally (32%) among Credit Cards, Net Banking, and Debit Cards, suggesting a wide fraud exposure across digital channels.
### 3. Transaction Age by Type
* Bank Transfers and Bill Payments have the highest average user age, suggesting older users may engage more with these methods, or possibly are more targeted.
### 4. User-Based Transaction Activity
* User ID 1201 has the highest total transaction amount (240K), followed by users 1947 and 3617.
* This may indicate a high-value client or a potentially compromised account due to the volume.
### 5. 24-Hour Activity
* A total of 382K transactions were recorded in the last 24 hours, signaling a high activity rate and the need for real-time monitoring.
## Recommendations
### 1. Implement Enhanced Mobile Security
* Given the mobile device’s high fraud incidence, implement multi-factor authentication (MFA), biometric verification, and regular app updates to enhance mobile transaction security.
### 2. Monitor Bill Payments More Closely
* As bill payments are the most fraud-prone method, apply tighter controls such as transaction velocity checks, anomaly detection, and approval workflows.
### 3. Flag and Review High-Transaction Users
* Users with high transaction volumes like User ID 1201 should be automatically flagged for enhanced fraud screening.
### 4. Investigate Unknown Device Access
* Transactions from unknown devices should trigger alerts. Device fingerprinting can be used to track new or unusual login environments.
### 5. Real-Time Monitoring and Alerts
* With over 380K transactions in 24 hours, real-time dashboards and alert systems should be implemented for prompt detection and response.
## Tools and Techniques Used
* Power BI for data modeling and dashboard design
* Power Query for data transformation and cleaning
* DAX (Data Analysis Expressions) for calculated fields and metrics
* Data visualization best practices: use of pie charts, bar charts, and gauges to enhance interpretability
## Repository Contents
* fraud_analytics_dashboard.pbix – Power BI file containing the full report
* dashboard_screenshot.jpeg – Image preview of the dashboard
* README.md – This project description and write-up
* insight_report.pdf (Optional) – Exported version of the analysis for stakeholder presentation
## Conclusion
This fraud analytics dashboard serves as a powerful tool for identifying fraud trends and supporting strategic decision-making. By visualizing the most critical aspects of fraudulent activity, organizations can better protect themselves and their customers against financial crimes.
