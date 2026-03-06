🏥 **Healthcare Operations & Revenue Analysis**
📋 **Project Overview**
This project focuses on the end-to-end data pipeline—from raw data ingestion and cleaning to deep-dive exploratory analysis—using a dataset of 10,000+ healthcare records. The primary goal was to uncover patterns in patient length of stay (LoS), hospital revenue efficiency, and clinical outcomes to provide data-driven recommendations for hospital administrators. Data was taken from kaggle.

🛠️ **Tech Stack**
Database: MySQL (Data Cleaning & Analysis)

Documentation: Markdown / GitHub

📈 **Key Insights & Findings**
Revenue Concentration: Top 3 hospitals account for approximately [X]% of total revenue.

Operational Efficiency: The average Length of Stay (LoS) is [X] days, with "Emergency" admissions showing the highest variance in billing.

Clinical Patterns: Patients diagnosed with [Condition Name] showed a [X]% higher rate of "Abnormal" test results compared to other groups.

Insurance Impact: [Insurance Provider Name] leads in total claim value, contributing [X]% to the overall revenue stream.

🏗️ **Data Engineering & Cleaning**
A staging environment was created in MySQL to ensure data integrity. The following steps were taken to transform the raw data into a "Ready-for-Analysis" state:

Data Standardization: Trimmed whitespace and standardized case formatting for Names, Genders, and Admission Types.

Feature Engineering: Created a length_of_stay column using DATEDIFF to measure operational duration.

Integrity Checks: Identifed and removed duplicate entries based on composite keys (Name, Age, Hospital, Date).

Constraint Management: Handled negative billing amounts and invalid age entries using ABS() and logic filters.

📊 **Exploratory Data Analysis (EDA)**
The analysis was broken down into four key pillars:

Financial Metrics: Month-over-Month (MoM) revenue growth and insurance provider breakdown.

Clinical Outcomes: Distribution of medical conditions and test result correlations.

Operational Performance: Average LoS by admission type and medical condition.

Provider Productivity: Revenue and patient volume handled by individual doctors and hospitals.
