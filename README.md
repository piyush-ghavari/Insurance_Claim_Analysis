# Prime Insurance Claim Analysis – Power BI Dashboard

## 🏢 Company: Prism Insurance Pvt. Ltd.

This Power BI project offers deep insights into policy distribution, claim status, and customer feedback for an insurance company. It integrates data from MySQL and provides clear visuals with Row-Level Security (RLS) and sentiment analysis to support better decision-making.

---

## 📌 Project Overview

- **Data Source**: MySQL
- **Tool Used**: Power BI
- **Security**: Row-Level Security (Policy Type-based roles)
- **Domain**: Insurance Analytics
- **Goal**: To analyze claim trends, policy activity, and customer sentiment.

---

## 🔧 Project Workflow

1. **Data Connection**  
   Connected Power BI with MySQL database.

2. **Data Preparation**
   - Performed table view and data profiling.
   - Created additional calculated columns:
     - `Age Group` (from Age)
     - `Policy Status` (Active/Inactive from Policy End Date)
     - `Sentiment` (from Feedback column)

3. **Report Pages**
   - **Page 1: Executive Summary Dashboard**
   - **Page 2: Detailed Table View with Drillthrough**
   - **Page 3: Sentiment Analysis**

4. **Security**
   - Applied **Row-Level Security (RLS)** by Policy Type (Health & Travel roles).

---

## 📊 Visualizations

### Page 1 – Insurance Overview
- **KPI Cards**: Premium Amount, Coverage Amount, Claim Amount
- **Bar Chart**: Premium by Policy Type (Travel, Health, etc.)
- **Column Chart**: Number of Claims by Claim Status (Rejected, Settled, Pending)
- **Line Chart**: Claim Amount by Age Group (Adult > Elder > Young Adult)
- **Pie Chart**: Active vs Inactive Policies
- **Matrix**: Policy Type vs Claim Status Amount
- **Gender Summary**: Male vs Female Count
- **Slicers**: Policy Number, Claim Number, Customer ID

### Page 2 – Data Exploration
- Drill-through table for exploring individual customer/policy level records.

### Page 3 – Customer Sentiment Analysis
- **Custom Column** from feedback text to extract sentiment (Positive/Negative/Neutral)
- **Pie Chart**: Sentiment distribution
- **Table**: Feedback records with sentiment label
- **Slicer**: Sentiment filter for exploration

---

## 🔍 Key Insights

- **🚨 Major Concern**: 4.4K claims were rejected (₹26 Cr+) — highest among all statuses.
- **Travel Policies Dominate**: Highest premium amount ₹2.5M – shows rising travel insurance adoption.
- **Health and Auto Policies**: Also show high claim activity.
- **Home Insurance**: Least purchased – indicates low market penetration.
- **Inactive Policies**: 58% policies are inactive – affects renewal rates and revenue.
- **Age Trend**: Adults contribute to highest claim amount; young adults the least.
- **Balanced Gender Split**: Male: 5003 | Female: 5001
- **Sentiment Feedback**: Insights from customer opinions on service quality.

---

## 🛡️ Recommendations

- Investigate reasons behind **high claim rejections** and optimize approval workflow.
- Promote **Home Insurance** through targeted campaigns.
- Increase engagement for inactive policyholders via renewal reminders and offers.
- Enhance customer service based on **sentiment feedback**.
- Use **RLS** to restrict department-specific data access.

---

## 🚀 How to Use

1. Install **Power BI Desktop** from [powerbi.microsoft.com](https://powerbi.microsoft.com/)
2. Connect to your MySQL data or open the `.pbix` file
3. Use slicers and drillthroughs to explore interactive visuals
4. Apply role-level filters to test RLS logic

---

## 📸 Dashboard Preview

### Analysis Dashboard

![Screenshot 2025-06-16 193916](https://github.com/user-attachments/assets/a6a9cc86-f46e-43a6-bc3d-ed8ebaf0e2f4)
-------------------------------------------------------------------------------------------------------------------

### Detailed View


![Screenshot 2025-06-16 194454](https://github.com/user-attachments/assets/5da1b9bd-149a-414c-a46f-0cc3095e6f56)


![Screenshot 2025-06-16 194509](https://github.com/user-attachments/assets/c5b9a1a0-5350-447e-a963-2590b6709688)

---------------------------------------------------------------------------------------------------------------------

### Feedback Sentiment

![Screenshot 2025-06-16 194343](https://github.com/user-attachments/assets/82836de4-a63e-47fe-8cd1-3f46c2af0793)


---

## 📂 Tags

`#InsuranceAnalytics` `#PowerBI` `#DataVisualization` `#MySQL` `#SentimentAnalysis` `#ClaimInsights` `#RLS`

