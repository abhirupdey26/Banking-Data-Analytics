# Banking Data Analytics Project

An end-to-end banking data analytics project using *Python and Power BI* to analyze customer demographics, loyalty classifications, banking products, deposits, loans, and business lending.

## 📌 Project Overview

The objective of this project is to explore banking customer data, identify meaningful patterns, and present the findings through an interactive Power BI dashboard.

The project follows a simple analytics workflow:

*Data → Python EDA → Business Analysis → Power BI Dashboard → Insights*

## 🛠️ Tools & Technologies

- *Python*
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
- *Google Colab*
- *Microsoft Power BI*
- *GitHub*

## 📊 Dataset

The dataset contains information about *3,000 banking customers*.

Key attributes include:

- Customer ID
- Age
- Nationality
- Occupation
- Gender
- Loyalty Classification
- Fee Structure
- Estimated Income
- Bank Deposits
- Bank Loans
- Business Lending
- Credit Card Balance
- Banking Accounts
- Properties Owned
- Risk Weighting

## 🔍 Python Exploratory Data Analysis

Python was used to understand and explore the dataset before creating the dashboard.

The analysis included:

- Dataset shape and structure
- Data types and descriptive statistics
- Missing-value checks
- Duplicate-value checks
- Categorical variable analysis
- Customer distribution analysis
- Loyalty classification analysis
- Nationality-based analysis
- Financial value analysis
- Comparison of deposits, loans and business lending

The EDA helped identify important patterns and determine which metrics were most useful for the Power BI dashboard.

## 📈 Power BI Dashboard

The final Power BI dashboard consists of three pages.

### 1. Banking Overview

Provides a high-level view of the banking customer base and financial performance.

Key metrics include:

- Total Customers
- Total Bank Deposits
- Total Bank Loans
- Total Business Lending
- Average Customer Age

Visualizations include:

- Customer Distribution by Loyalty Classification
- Total Bank Deposits by Nationality
- Total Bank Loans by Nationality

![Banking Overview](Banking%20Overview.png)

---

### 2. Financial Analysis

Focuses on the financial performance of different customer loyalty segments.

Key metrics include:

- Total Business Lending
- Total Credit Card Balance
- Average Customer Income

The main visualization compares:

- Bank Deposits
- Bank Loans
- Business Lending

across different loyalty classifications.

![Financial Analysis](Financial%20Analysis.png)

---

### 3. Customer Analysis

Provides a deeper look at customer demographics and fee structures.

The page includes:

- Customers by Nationality
- Average Bank Deposits by Nationality
- Average Bank Loans by Nationality
- Customers by Fee Structure

![Customer Analysis](Customer%20Analysis.png)

## 💡 Key Business Insights

### 1. Jade customers represent the largest loyalty segment

Jade customers have the highest number of customers among the loyalty classifications in the dataset.

### 2. Jade customers contribute the highest overall financial value

The Jade segment contributes the highest total:

- Bank Deposits
- Bank Loans
- Business Lending

### 3. Business lending is the largest financial category

Across the loyalty segments, business lending is consistently higher than bank deposits and bank loans.

### 4. European customers contribute the highest total deposits

European customers form the largest customer group in the dataset and consequently contribute the highest overall bank deposits.

### 5. Customer income and financial activity can be analyzed by segment

The dashboard allows users to compare financial metrics across loyalty classifications and customer groups to identify areas of higher customer value.

## 🔄 Project Workflow

```text
Banking Dataset
       ↓
Data Understanding
       ↓
Data Quality Checks
       ↓
Python Exploratory Data Analysis
       ↓
Identify Business Patterns
       ↓
Power BI Visualization
       ↓
Interactive Dashboard
       ↓
Business Insights
