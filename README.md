# 🏦 Banking Data Analysis

## 📌 Project Overview

This project focuses on analyzing banking customer data to uncover meaningful insights into **customer demographics, financial behavior, banking relationships, credit usage, loans, deposits, account balances, business lending, loyalty classification, and risk characteristics**.

The dataset contains **3,000 customer records** and provides a detailed view of each customer's financial profile and relationship with the bank.

The goal of this project is to transform raw banking data into actionable insights that can help understand customer segments, financial behavior, product usage, and potential areas for business improvement.

---

## 🎯 Project Objectives

The major objectives of this analysis are:

* Analyze the demographic profile of banking customers.
* Understand customer income and financial strength.
* Analyze loans and credit card usage.
* Compare bank deposits, checking accounts, and savings accounts.
* Study business lending patterns.
* Analyze customer loyalty classifications.
* Investigate relationships between income, assets, loans, and deposits.
* Examine customer risk-related attributes.
* Identify high-value customer segments.
* Generate insights that could support banking business decisions.

---

## 📊 Dataset

The dataset contains customer-level banking information.

Each row represents an individual banking customer.

### Dataset Size

* **Records:** 3,000 customers
* **Columns:** 25
* **Format:** CSV
* **Data Type:** Customer and financial banking data

The dataset includes fields such as Client ID, customer name, age, location, joining date, banking contact, nationality, occupation, fee structure, loyalty classification, income, savings, credit cards, loans, deposits, accounts, business lending, properties, and risk-related identifiers.

---

## 🗂️ Data Dictionary

| Column                     | Description                                                      |
| -------------------------- | ---------------------------------------------------------------- |
| `Client ID`                | Unique identifier for each banking customer                      |
| `Name`                     | Customer name                                                    |
| `Age`                      | Age of the customer                                              |
| `Location ID`              | Identifier representing customer location                        |
| `Joined Bank`              | Date when the customer joined the bank                           |
| `Banking Contact`          | Banking representative/contact assigned to the customer          |
| `Nationality`              | Customer nationality                                             |
| `Occupation`               | Customer occupation                                              |
| `Fee Structure`            | Customer's applicable fee category                               |
| `Loyalty Classification`   | Customer loyalty segment such as Jade, Gold, Silver, or Platinum |
| `Estimated Income`         | Estimated annual income of the customer                          |
| `Superannuation Savings`   | Customer's superannuation/retirement savings                     |
| `Amount of Credit Cards`   | Number of credit cards held                                      |
| `Credit Card Balance`      | Outstanding credit card balance                                  |
| `Bank Loans`               | Outstanding bank loan amount                                     |
| `Bank Deposits`            | Customer deposits held with the bank                             |
| `Checking Accounts`        | Balance associated with checking accounts                        |
| `Saving Accounts`          | Balance associated with savings accounts                         |
| `Foreign Currency Account` | Balance held in foreign currency accounts                        |
| `Business Lending`         | Amount associated with business lending                          |
| `Properties Owned`         | Number of properties owned                                       |
| `Risk Weighting`           | Risk-related customer classification                             |
| `BRId`                     | Banking relationship identifier                                  |
| `GenderId`                 | Gender identifier                                                |
| `IAId`                     | Internal analytical/category identifier                          |

The column structure and example records are present in the supplied dataset.

---

## 🔍 Key Areas of Analysis

### 1. Customer Demographics

Analyze customers based on:

* Age
* Nationality
* Occupation
* Gender
* Location

This can help identify the major customer groups and understand the demographic composition of the bank's customer base.

---

### 2. Customer Loyalty Analysis

The dataset contains multiple loyalty classifications, including:

* Jade
* Gold
* Silver
* Platinum

Analysis can focus on:

* Number of customers in each loyalty category
* Average income by loyalty segment
* Average deposits by loyalty segment
* Loan exposure by loyalty segment
* Credit card usage by loyalty segment
* Overall financial profile of different customer segments

---

### 3. Income Analysis

The `Estimated Income` field can be used to analyze:

* Average customer income
* Highest and lowest income groups
* Income distribution
* Income by occupation
* Income by loyalty classification
* Relationship between income and banking products

---

### 4. Loan & Credit Analysis

The dataset contains both bank loan and credit card information.

Possible analysis includes:

* Total bank loan exposure
* Average loan amount
* Credit card ownership
* Average credit card balance
* Customers with high loan balances
* Relationship between income and borrowing
* Loan exposure by loyalty segment

---

### 5. Deposit & Account Analysis

Banking deposits and account balances can be analyzed using:

* Bank deposits
* Checking accounts
* Savings accounts
* Foreign currency accounts

Possible questions:

* Which customers maintain the highest deposits?
* Which loyalty segment has the highest deposits?
* How do savings and checking balances compare?
* Do higher-income customers maintain higher deposits?

---

### 6. Business Lending Analysis

The `Business Lending` field provides an opportunity to analyze customers with business-related financial exposure.

Potential analysis:

* Total business lending
* Average business lending
* Business lending by loyalty classification
* Business lending by occupation
* Business lending versus customer income
* High-value business banking customers

---

### 7. Customer Asset Analysis

The dataset includes:

* Bank deposits
* Savings accounts
* Checking accounts
* Foreign currency accounts
* Properties owned
* Superannuation savings

These variables can be combined to understand the broader financial strength of customers.

---

### 8. Risk Analysis

The dataset includes a `Risk Weighting` field that can be used to examine customer risk characteristics.

Possible analysis:

* Customer distribution by risk weighting
* Average loans by risk category
* Average deposits by risk category
* Income distribution by risk category
* Relationship between risk and customer loyalty
* Identification of financially significant customer segments

---

## 📈 Potential Business Questions

This project can answer questions such as:

1. Which loyalty classification has the highest number of customers?
2. Which loyalty segment generates the highest financial value?
3. What is the average estimated income of customers?
4. Which occupations have the highest average income?
5. Which customers have the highest bank loan exposure?
6. Which loyalty segment has the highest average deposits?
7. What is the relationship between income and bank deposits?
8. Which customers have significant credit card balances?
9. How does business lending vary across customer segments?
10. Which risk categories contain the highest loan exposure?
11. How does customer age relate to banking behavior?
12. Which customer segments own the most properties?
13. How are checking and savings account balances distributed?
14. Which customers represent potential high-value banking relationships?

---

## 🛠️ Project Workflow

```text
Raw Banking Dataset
        │
        ▼
Data Cleaning
        │
        ▼
Data Exploration
        │
        ▼
Customer Segmentation
        │
        ▼
Financial Analysis
        │
        ▼
Risk & Loyalty Analysis
        │
        ▼
Data Visualization
        │
        ▼
Business Insights
```

---

## 📊 Suggested KPIs

The following KPIs can be used in a banking dashboard:

* **Total Customers**
* **Total Estimated Income**
* **Total Bank Loans**
* **Total Bank Deposits**
* **Total Credit Card Balance**
* **Total Business Lending**
* **Total Savings**
* **Total Checking Balance**
* **Average Customer Income**
* **Average Loan Amount**
* **Average Deposit**
* **Average Credit Card Balance**
* **Customers by Loyalty Classification**
* **Customers by Risk Weighting**

---

## 📊 Suggested Dashboard Sections

If this project is implemented in Power BI/Tableau, the dashboard can contain:

### Executive Overview

* Total Customers
* Total Deposits
* Total Loans
* Total Business Lending
* Total Customer Income

### Customer Analysis

* Customers by Age
* Customers by Nationality
* Customers by Occupation
* Customers by Loyalty Classification

### Financial Analysis

* Loans vs Deposits
* Income vs Deposits
* Credit Card Balance
* Savings vs Checking Accounts
* Business Lending

### Risk & Loyalty

* Customers by Risk Weighting
* Loan Exposure by Risk
* Deposits by Loyalty Classification
* Income by Loyalty Classification

---

## 💡 Business Insights

The analysis can help banking teams:

* Identify high-value customers.
* Understand customer financial behavior.
* Identify customer segments for targeted banking products.
* Analyze lending exposure.
* Understand deposit patterns.
* Improve customer segmentation.
* Identify opportunities for cross-selling financial products.
* Monitor customer risk characteristics.
* Develop data-driven customer retention strategies.

---

## 📁 Project Structure

```text
banking-data-analysis/
│
├── data/
│   └── banking_data.csv
│
├── dashboard/
│   └── banking_analysis_dashboard.*
│
├── analysis/
│   └── banking_analysis.*
│
├── images/
│   └── dashboard.png
│
└── README.md
```

> Update the folder names above according to the actual structure of your GitHub repository.

---

## 🧰 Tools & Technologies

Depending on the implementation, this project can use:

* **SQL** – Data querying and analysis
* **Python** – Data cleaning and exploratory analysis
* **Pandas** – Data manipulation
* **Matplotlib / Seaborn** – Data visualization
* **Power BI** – Interactive dashboarding
* **Excel** – Data exploration and reporting
* **Git & GitHub** – Version control and project documentation

---

## 🚀 Project Outcome

This project demonstrates how raw customer banking data can be transformed into structured business insights.

It covers the complete analytical process from **understanding customer data to financial analysis, customer segmentation, risk analysis, KPI development, and visualization**.

The project can serve as a portfolio project for **Data Analyst, Business Analyst, Banking Analytics, and Data-related roles**.

---

## 👤 Author

**Your Name**

Computer Science Graduate

### Connect With Me

* GitHub: Add your GitHub profile
* LinkedIn: Add your LinkedIn profile
* Email: Add your email

---

## ⭐ If You Find This Project Useful

If you find this project useful or interesting, consider giving the repository a ⭐ on GitHub.
