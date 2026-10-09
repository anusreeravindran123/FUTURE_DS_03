FUTURE_DS_03 — Customer Conversion & Marketing Funnel Analysis

📊 Project Overview

This project analyzes a bank marketing campaign to understand customer conversion, marketing funnel performance, campaign effectiveness, and customer segments associated with successful term-deposit subscriptions.

Completed as part of Future Interns — Data Science & Analytics, Task 3, using Python and Google Colab.

🎯 Objectives

- Calculate overall customer conversion and drop-off rates.
- Analyze the marketing funnel and campaign performance.
- Compare converted and non-converted customers.
- Identify high-converting customer segments.
- Evaluate conversion by job, education, marital status, age, and loan status.
- Compare contact channels and campaign months.
- Analyze campaign contact frequency, call duration, and previous campaign outcomes.
- Track marketing KPIs and identify potential drop-off areas.
- Develop actionable recommendations to improve conversion.

📁 Dataset

File: "bank-full.csv"

The Bank Marketing dataset contains 45,211 customer records and 17 columns.

Feature| Description
"age"| Customer age
"job"| Occupation
"marital"| Marital status
"education"| Education level
"default"| Credit default status
"balance"| Average yearly balance
"housing"| Housing loan status
"loan"| Personal loan status
"contact"| Communication channel
"day", "month"| Last contact date
"duration"| Last call duration
"campaign"| Contacts during current campaign
"pdays"| Days since previous contact
"previous"| Previous campaign contacts
"poutcome"| Previous campaign outcome
"y"| Term-deposit subscription ("yes"/"no")

🧹 Data Preparation

- Loaded the CSV dataset and examined its structure, columns, and statistics.
- Checked missing values and duplicate records.
- Removed duplicate records where applicable.
- Cleaned column names and categorical values.
- Standardized categorical text to lowercase.
- Examined unique values and prepared the data for analysis.

📈 Key Performance Indicators (KPIs)

KPI| Value
Total Leads Contacted| 45,211
Converted Customers| 5,289
Non-Converted Customers| 39,922
Conversion Rate| 11.70%
Drop-off Rate| 88.30%
Average Customer Age| 40.94
Average Account Balance| 1,362.27
Average Call Duration| 258.16

The conversion rate is approximately 11.70%, meaning around one in nine contacted customers subscribed to the term deposit.

🔍 Analysis Performed

1. Customer Conversion & Marketing Funnel

Analyzed the distribution of converted and non-converted customers.

Funnel: Leads Contacted (45,211) → Converted Customers (5,289).

The dataset supports a two-stage funnel because separate website visitor or lead-generation stages are unavailable.

2. Customer Segmentation

Calculated customer counts and conversion rates across:

- Job categories
- Education levels
- Marital status
- Housing loan status
- Personal loan status
- Age groups (18–25, 26–35, 36–45, 46–55, 56–65, and 65+)
- Credit default status

3. Marketing Campaign Analysis

Analyzed:

- Conversion by contact channel (cellular, telephone, and unknown).
- Conversion by month to identify stronger campaign periods.
- Conversion by campaign contact frequency.
- Average call duration for converted and non-converted customers.
- Conversion by previous campaign outcome (success, failure, other, and unknown).

4. KPI Dashboard & Drop-Off Analysis

Created a dashboard-style KPI summary covering total leads, conversions, non-conversions, conversion rate, drop-off rate, average age, average balance, and average call duration.

The analysis highlights the difference between contacted customers and successful subscriptions.

📊 Key Business Insights

- Overall conversion was approximately 11.70%, with an 88.30% non-conversion rate.
- Cellular contact showed stronger conversion performance than the unknown contact category.
- Students and retired customers showed relatively high observed conversion rates among job groups.
- Customers with tertiary education showed stronger conversion than those with primary or secondary education.
- Single customers had higher observed conversion than married customers.
- Customers without housing or personal loans showed higher observed conversion.
- March, December, September, and October showed relatively strong conversion rates.
- Customers contacted fewer times generally showed stronger conversion than those contacted repeatedly.
- Longer calls were associated with customer engagement, but duration alone does not prove causation.
- Customers with successful previous campaign outcomes had substantially higher conversion rates.
- Conversion patterns differed across age groups and default-status categories.

These are observed associations in the dataset, not proof that any individual characteristic causes conversion.

🚀 Recommendations

1. Target effectively: Prioritize customer segments with stronger historical conversion rates while monitoring campaign outcomes.
2. Use previous results: Consider previous campaign success when prioritizing future leads.
3. Optimize channels: Evaluate and prioritize communication channels with better conversion performance.
4. Limit excessive contacts: Monitor repeated calls to reduce inefficient contact and customer fatigue.
5. Optimize timing: Evaluate campaign months with stronger conversion rates.
6. Improve engagement: Focus on meaningful customer conversations rather than call duration alone.
7. Personalize campaigns: Use customer demographics, loan status, contact history, and previous outcomes responsibly.
8. Monitor KPIs: Regularly track leads, conversions, conversion and drop-off rates, channel performance, and segment performance.

📉 Visualizations Created

- Customer conversion distribution
- Marketing funnel
- Conversion rate by job and education
- Conversion by marital status and loan status
- Conversion by contact channel and month
- Conversion by campaign contact frequency
- Average call duration by conversion status
- Conversion by age group
- Conversion by previous campaign outcome
- Correlation matrix
- KPI summary dashboard

🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- Jupyter Notebook

📂 Project Structure

FUTURE_DS_03/
├── bank-full.csv
├── FUTURE_DS_Task_03_Bank_Marketing_Analysis.ipynb
├── job_conversion_analysis.csv
├── contact_conversion_analysis.csv
├── month_conversion_analysis.csv
├── campaign_conversion_analysis.csv
├── previous_outcome_analysis.csv
├── bank_marketing_kpi_summary.csv
└── README.md

🎓 Internship Details

- Program: Future Interns
- Track: Data Science & Analytics
- Task: Task 3 — Bank Marketing / Customer Conversion Analysis

👩‍💻 Author

Anusree R
B.Tech — Computer Science and Engineering (Data Science)

⭐ Project Summary

This project demonstrates how data analytics can evaluate bank marketing performance, identify customer segments associated with successful term-deposit subscriptions, compare communication channels, and examine campaign timing and contact frequency.

The findings provide a data-driven foundation for improving customer targeting, optimizing marketing resources, monitoring conversion KPIs, and reducing inefficient contacts.
