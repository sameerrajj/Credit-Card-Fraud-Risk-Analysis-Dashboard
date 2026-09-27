# Credit Card Fraud Analysis Dashboard | Power BI

## 📊 Project Overview

This project is an interactive **Credit Card Fraud Analysis Dashboard** developed using **Microsoft Power BI**.

The dashboard provides a visual analysis of fraudulent transactions across different fraud types, transaction categories, states, months, merchants, and fraud-risk levels.

The dataset used for this project was provided in a **pre-cleaned format**. The main focus of this project is on **Power BI dashboard development, DAX calculations, data analysis, and visualization**.

---

## 🎯 Project Objectives

The main objectives of this dashboard are to:

- Analyze fraudulent transaction patterns
- Calculate important fraud-related KPIs
- Identify fraud types contributing to transaction amounts
- Analyze fraudulent transactions across different states
- Understand monthly fraud trends
- Examine transaction amounts by fraud-risk level
- Provide interactive filtering for deeper analysis

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **DAX (Data Analysis Expressions)**
- **Power Query**
- **Power BI Visualizations**
- **Business Intelligence**
- **Data Visualization**

---

## 📁 Dataset

The project uses a pre-cleaned transaction dataset containing the following fields:

- Transaction ID
- Customer Name
- Merchant Name
- Transaction Date
- Transaction Amount (INR)
- Fraud Risk
- Fraud Type
- State
- Card Type
- Bank
- IsFraud
- Fraud Score
- Transaction Category
- Merchant Location

> **Note:** The dataset was provided in a pre-cleaned format, so no original data-cleaning process was performed as part of this project.

---

## 📈 Dashboard KPIs

The dashboard includes the following key performance indicators:

| KPI | Description |
|---|---|
| **Fraud Rate %** | Percentage of transactions identified as fraudulent |
| **Fraudulent Transactions** | Total number of fraudulent transactions |
| **Critical Risk Transaction %** | Percentage of transactions classified as critical risk |
| **Fraudulent Transaction Amount** | Total transaction amount associated with fraudulent transactions |
| **Top Fraud Type** | Fraud type identified by the dashboard calculation |

---

## 📊 Dashboard Analysis

### 1. Fraud Type & Transaction Category

A stacked bar chart analyzes the **total transaction amount by fraud type and transaction category**.

This helps understand how different transaction categories contribute to different fraud types.

### 2. Fraud Risk Analysis

A donut chart displays the **total transaction amount by fraud-risk level**.

This allows comparison between different risk categories such as:

- Low
- Medium
- High
- Critical

### 3. State-wise Fraud Analysis

A column chart shows the **number of fraudulent transactions by state**.

This provides a geographical view of fraudulent activity within the dataset.

### 4. Monthly Fraud Trend

A monthly trend chart displays the **number of fraudulent transactions over time**.

This helps identify changes and patterns in fraudulent activity across different months.

---

## 🎛️ Interactive Filters

The dashboard includes interactive slicers for:

- **Fraud Type**
- **State**
- **Merchant Name**

Users can select different values to dynamically update the dashboard visuals and KPIs.

---

## 🧮 DAX & Calculations

DAX was used to create calculated measures and KPIs required for the dashboard.

The calculations include:

- Total fraudulent transactions
- Fraud rate
- Fraudulent transaction amount
- Critical-risk transaction percentage
- Top fraud type
- Transaction-level aggregations

These measures allow the dashboard to dynamically respond to slicer selections.

---

## 💡 Business Questions Answered

The dashboard helps answer questions such as:

- What percentage of transactions are fraudulent?
- How many fraudulent transactions are present?
- Which fraud types contribute the most transaction value?
- Which states have the highest number of fraudulent transactions?
- How does fraud activity change from month to month?
- What proportion of transaction value belongs to each fraud-risk level?
- Which merchants or fraud types can be investigated further?

---

## 📂 Repository Structure

```text
Credit-Card-Fraud-Analysis-PowerBI/
│
├── README.md
├── Fraud data.csv
├── Credit Card Fraud Analysis.pbix
└── Dashboard.png
