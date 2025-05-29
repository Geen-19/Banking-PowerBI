# Banking PowerBI Dashboard
![image](https://github.com/user-attachments/assets/83b198f0-8b3b-4e9c-821b-8d49c866d249)

# Loan Analysis
![image](https://github.com/user-attachments/assets/a95233ce-79c4-4445-9151-dedd2edc9419)

# Deposit Analysis
![image](https://github.com/user-attachments/assets/0b3a0dd6-4ee9-46fc-87fb-a6b3703d52ed)

# Bank Loan & Deposit Analysis Dashboard

A Power BI dashboard offering interactive insights into a bank’s loan and deposit portfolio—segmented by nationality, number of credit cards, income range, and overall deposit vs. loan trends.

---

## Table of Contents

1. [Project Overview](#project-overview)  
2. [Key Features](#key-features)  
3. [Data Description](#data-description)  
4. [Dashboard Walkthrough](#dashboard-walkthrough)  
5. [Getting Started](#getting-started)  
6. [Usage](#usage)  
7. [Folder Structure](#folder-structure)  
8. [Contributing](#contributing)  
9. [License](#license)  
10. [Author](#author)  

---

## Project Overview

Banks need to understand how loans and deposits behave across different customer segments. This dashboard helps stakeholders:

- Monitor total loans vs. deposits over time  
- Compare loan distribution by customer nationality  
- Analyze credit‐card count and loan uptake  
- Assess how income ranges influence borrowing behavior  

![Dashboard Snapshot](docs/dashboard_screenshot.png)

---

## Key Features

- **Loan Analysis by Nationality**  
  Visualize which customer groups (by country) hold the largest share of outstanding loans.

- **Credit Card Count vs. Loan Volume**  
  Scatter/heatmap showing correlation between number of credit cards held and loan amount.

- **Income Range Segmentation**  
  Bar charts that break down average loan size and default rates by income brackets.

- **Deposit vs. Loan Trend**  
  Line chart tracking total deposits against total loans month-over-month.

- **Summary KPIs**  
  Card visuals for total loans, total deposits, average loan per customer, and NPL (non-performing loan) ratio.

---

## Data Description

| File / Table        | Description                                              |
|---------------------|----------------------------------------------------------|
| `Customers.csv`     | Customer demographics: nationality, age, income, cards.  |
| `Accounts.csv`      | Account balances and deposit activity per customer.      |
| `Loans.csv`         | Loan records: amount, type, disbursement date, status.   |
| `CreditCards.csv`   | Number of active credit cards per customer.              |

> **Tip:** To connect your own data source (SQL Server, Azure, etc.), update the **Get Data** steps in Power BI’s Transform Data window.

---

## Dashboard Walkthrough

1. **Home & Filters**  
   - Global slicers for date range, nationality, income range, and credit‐card count.

2. **Loans by Nationality**  
   - A bar chart ranking countries by total outstanding loan value.

3. **Credit Cards vs. Loan Volume**  
   - A scatter plot: X axis = number of credit cards, Y axis = loan amount.

4. **Income Range Analysis**  
   - Stacked bars showing loan counts and average loan amounts per income bracket.

5. **Deposit vs. Loan Trends**  
   - Dual-axis line chart for total deposits and loans over time.

6. **KPI Cards**  
   - Quick stats:  
     - Total Loans Disbursed  
     - Total Deposits Collected  
     - Average Loan Size  
     - NPL Ratio

---

## Getting Started

### Prerequisites

- **Power BI Desktop** (latest version)  
  https://powerbi.microsoft.com/desktop/

### Installation

1. **Clone this repository**  
   ```bash
   git clone https://github.com/<your-username>/bank-loan-deposit-dashboard.git
   cd bank-loan-deposit-dashboard
