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

