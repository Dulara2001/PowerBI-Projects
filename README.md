# PowerBI-Projects

# AdventureWorksDW2022 Dashboard
<img src="https://github.com/user-attachments/assets/b7b9dd95-6289-452d-9370-f38df9f9027f" alt="AdventureWorks" width="500">

This project showcases a Power BI dashboard created using the AdventureWorksDW2022 dataset, which includes multiple visualizations to analyze financial data effectively.

## Dataset
The dataset used for this project can be downloaded from the following link:  
[AdventureWorksDW2022 Dataset](https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver16&tabs=ssms)

---

## Features

### 1. Clustered Column Chart
- **Visualization**: Clustered column chart based on `Organization`, `Scenario Name`, and `Amount`.
- **Purpose**: Compare **Actual vs. Budgeted Amounts** for the selected Account Type.
- **Filters**:
  - Year
  - Account Type
- **Screenshot**:
  - Filtered for **Year: 2011** and **Account Type: Revenue**.



### 2. Matrix Table
- **Data Displayed**:
  - `Account Type`
  - `Account Description`
  - `Operator`
  - `Value Type`
  - `Amount`
- **Feature**: Hierarchy between **Account Type** and **Account Description**.
- **Purpose**: Analyze detailed financial data in a tabular format.



### 3. Pie Chart
- **Visualization**: Pie chart to show **Amount** grouped by `Department Group Name`.
- **Filters**:
  - Year
  - Account Type
  - Scenario Name
- **Screenshot**:
  - Filtered for **Year: 2011**, **Scenario Name: Actual**, and **Account Type: Expenditures**.

-

### 4. Line Chart
- **Visualization**: Line chart to display **Monthly Expenditure** (Budgeted vs. Actual).
- **Filters**:
  - Year
- **Feature**: Separate lines for each scenario.
- **Screenshot**:
  - Filtered for **Year: 2011**.

---


