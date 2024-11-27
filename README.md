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

# Amazon Prime Video Dashboard

<img src="https://github.com/user-attachments/assets/eac292b8-dc40-49d6-abe1-d03596fa80ed" alt="AmazonPrimeVideoDashboard" width="500">

This dashboard provides a comprehensive overview of Amazon Prime Video's content library. It includes metrics on the number of titles, ratings, genres, directors, and release dates, offering insights into the platform's offerings. Below is a detailed description of each visualization:

---

## Dataset
The dataset used for this project can be downloaded from the following link:  
https://www.kaggle.com/datasets/shivamb/amazon-prime-movies-and-tv-shows

## **Summary Metrics**
- **Total Titles**: Displays the total number of movies and TV shows available on Amazon Prime Video (9,655).
- **Total Ratings**: The number of unique rating categories used for the shows (25).
- **Total Genres**: The number of distinct genres covered in the platform's library (519).
- **Total Directors**: The total number of directors whose work is featured (5,771).
- **Start Date**: The earliest release year for content on the platform (1920).
- **End Date**: The latest release year for content included in the analysis (2021).

---

## **Ratings by Total Shows**
- **Chart Type**: Horizontal Bar Chart
- **Description**: Shows the count of titles grouped by their rating categories (e.g., 13+, 16+, R, PG-13).
- **Insight**: The "13+" rating category has the highest number of titles, with 2.1K shows, indicating a focus on family-friendly content.

---

## **Genres by Total Shows**
- **Chart Type**: Horizontal Bar Chart
- **Description**: Highlights the top genres by the number of shows available.
- **Insight**: 
  - Drama is the most prevalent genre with 986 titles.
  - Comedy follows with 536 titles.
  - Other popular genres include Drama-Suspense, Comedy-Drama, and Documentary.

---

## **Total Shows by Country**
- **Visualization**: Map
- **Description**: Geographic distribution of the total number of shows by country.
- **Insight**: The map provides an interactive way to see the availability of titles across different regions.

---

## **Movies and TV Shows**
- **Chart Type**: Donut Chart
- **Description**: Compares the distribution of movies and TV shows in the content library.
- **Insight**: 
  - TV shows constitute the majority (80.82% or 7,810 titles).
  - Movies make up 19.18% (1,850 titles).

---

## **Total Shows by Release Year**
- **Chart Type**: Line Chart
- **Description**: Displays the trend of content releases over time, broken down by type (Movie or TV Show).
- **Insight**: A sharp increase in releases is visible after the year 2000, indicating an expansion of Amazon Prime Video's library in recent years.

---

## **Design Highlights**
- **Interactive Visualizations**: Users can filter the data dynamically using various slicers and filters embedded in the dashboard.
- **Prime Video Branding**: The dashboard prominently features the Prime Video logo, reinforcing the brand identity.
- **Dark Theme**: The design utilizes a dark background for better contrast and a modern look.

---

This dashboard provides a clear, interactive, and visually appealing representation of Amazon Prime Video's library, making it easier to understand the platform's content strategy and user offerings. Let me know if you want to enhance the dashboard description further or need additional features!


### 5. Interactive Dashboard
- **Consolidated View**: All the above visualizations combined into a single interactive dashboard.
- **Added Slicer**: Date slicer based on the `FactFinance` table, including a **Date Hierarchy**.
  
---

# HR-Employee-Attrition Dashboard
<img src="https://github.com/user-attachments/assets/ebf3a614-69b4-47a6-aba8-3e788a767064" alt="HREmployee" width="500">

This HR-Attrition Dashboard provides an insightful overview of employee attrition within an organization, presenting key metrics and trends to help HR teams make data-driven decisions. Here's a detailed breakdown of its components:

---

## **1. Total Employees**
- Displays the **total number of employees** in the organization, which is **1,470**. 
- This metric serves as a starting point for evaluating attrition rates and trends.

---

## **2. Attrition by Working Year**
- A **bar chart** shows the total number of employees leaving the organization categorized by their **years of service**:
  - **0-10 years**: 182 employees.
  - **11-20 years**: 39 employees.
  - **21-30 years**: 11 employees.
  - **31+ years**: 5 employees.
- Highlights that most attrition occurs among employees with less than 10 years of working experience.

---

## **3. Attrition by Employee Satisfaction**
- Another **bar chart** categorizes attrition based on employees' **job satisfaction levels**:
  - **Dissatisfied**: 73 employees.
  - **Very Satisfied**: 66 employees.
  - **Very Dissatisfied**: 52 employees.
  - **Satisfied**: 46 employees.
- This visualization reveals the correlation between employee satisfaction and attrition, showing higher attrition among dissatisfied employees.

---

## **4. Attrition Rate**
- Displays the overall **attrition rate** as **16%**.
- This metric provides a high-level view of how many employees have left relative to the total workforce.

---

## **5. Attrition by Distance to Work**
- A **donut chart** presents attrition based on employees' **commute distance**:
  - **Nearby**: 144 employees (60.76%).
  - **Far**: 48 employees (20.25%).
  - **Very Far**: 45 employees (18.99%).
- This metric helps assess whether long commutes contribute significantly to attrition rates.

---

## **6. Attrition by Department**
- Another **donut chart** shows attrition distribution across different departments:
  - **HR**: 12 employees.
  - **R&D**: 133 employees.
  - **Sales**: 92 employees.
- This visualization highlights which departments experience the highest attrition, with **R&D** being the most affected.

---

## **7. Gender-Based Attrition**
- Two distinct pie charts display the **gender split** in attrition:
  - **Female Attrition**: 87 employees (37%).
  - **Male Attrition**: 150 employees (63%).
- These figures provide insights into whether one gender is disproportionately impacted by attrition.
