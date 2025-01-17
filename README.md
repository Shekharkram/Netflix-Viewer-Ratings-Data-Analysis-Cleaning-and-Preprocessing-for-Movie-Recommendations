# Netflix Viewer Ratings: Data Analysis, Cleaning and Preprocessing for Movie Recommendations

## Overview
This project focuses on cleaning and preparing a Netflix viewers' rating dataset to enhance its accuracy, consistency, and usability for movie recommendation systems.

## Objective
The primary objective of this project was to clean and preprocess the Netflix viewer ratings dataset to ensure its readiness for building a movie recommendation system. This involved handling missing values, removing irrelevant data, addressing outliers, and categorizing relevant features for efficient analysis.

## Dataset Exploration Summary
- The dataset consists of 9,827 rows and 9 columns.
- Initially, the dataset has no missing values or duplicates, making it relatively clean.
- The `Release_Date` column needs to be converted to the correct datetime format.
- Columns like `Overview`, `Original_Language`, and `Poster-Url` are deemed unnecessary for the analysis and were removed.
- The `Popularity` column contains noticeable outliers, which were handled to ensure accurate analysis.
- The `Vote_Average` column was categorized for better analysis.
- The `Genre` column contains comma-separated values with extra spaces, which were cleaned and standardized.

## Tasks Performed
1. Cleaned and formatted the `Release_Date` column to the proper datetime format.  
2. Removed irrelevant columns such as `Overview`, `Original_Language`, and `Poster-Url`.  
3. Handled outliers in the `Popularity` column for improved analysis accuracy.  
4. Categorized the `Vote_Average` column to facilitate proper analysis.  
5. Cleaned and standardized the `Genre` column by handling comma-separated values and removing extra spaces.  
6. Ensured the dataset was ready for movie recommendation model development by optimizing data structure and consistency.
7. 7. Conducted data visualization using **Matplotlib** and **Seaborn** to create informative charts, uncover trends, and gain deeper insights into the dataset, which helped answer key questions and understand underlying patterns and relationships.

## Key Metrics
### Dataset Quality Metrics:
- **Missing Values:** Percentage handled for each column.
- **Duplicate Rows:** Number and percentage removed.
- **Outliers:** Count detected and addressed in key columns like `Popularity` and `Vote_Average`.
- **Irrelevant Data Removed:** Count of dropped columns.

### Data Standardization Metrics:
- **Formatted Dates:** Percentage of correct conversions in the `Release_Date` column.
- **Standardized Genres:** Count of unique genres after cleaning.
- **Categorized Ratings:** Number of categories created for `Vote_Average`.

### Visualization Metrics:
- **Trends Identified:** Insights into top-rated genres and seasonal viewer patterns.
- **Viewer Engagement:** Distribution of ratings and patterns in viewer behavior.

## Visualizations
Data visualization was conducted to uncover insights and trends within the dataset. Key visualizations include:

- **Bar Charts:** Highlighted relationships in variables such as `Age Group`, `Age Group & Gender`, and `Vote_Average`.
![image](https://github.com/user-attachments/assets/68058b52-139e-44ae-ba03-822d77d8504f)
- **Pie Charts:** Used to compare variables such as `Season` and `Genre`.
![image](https://github.com/user-attachments/assets/153e305f-e440-4879-b7fa-fd184590a087)
- **Histogram :**
- ![image](https://github.com/user-attachments/assets/8d7557fb-177c-4fc6-b9fa-3591449bf0c0)
  
## Outcome
- A clean, structured, and standardized dataset was prepared for use in developing a movie recommendation system.
- Insights into viewer preferences and behavior were gained through effective data visualizations.
- The dataset is now primed for advanced analysis and modeling to enhance Netflix's recommendation capabilities.






