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

## Data Visualization
Data visualization has been conducted using **Matplotlib** and **Seaborn** to create informative charts. These visualizations helped to uncover trends and insights within the dataset, answering key questions and providing a deeper understanding of the underlying patterns and relationships. This allowed for:
- **Exploration of rating distributions**
- **Identification of outliers in popularity**
- **Analysis of genre trends**
- **Understanding movie ratings based on popularity**

## Outcome
- The dataset was cleaned and preprocessed to remove irrelevant columns and handle missing or inconsistent values.
- Outliers were addressed, ensuring the dataset's accuracy and improving the performance of the movie recommendation system.
- The `Genre` and `Vote_Average` columns were standardized and categorized for enhanced analysis.
- Visualizations revealed important insights, such as rating distribution patterns and correlations between popularity and ratings.
- The dataset is now optimized for use in movie recommendation models, facilitating better recommendations and insights.

## Screenshot
Below is a screenshot of the Jupyter Notebook used in this project:

## Screenshot

Below are screenshots of the Jupyter Notebook used in this project:

![image](https://github.com/user-attachments/assets/836d7297-65cf-4499-b1f6-3e85f04a208e)
![image](https://github.com/user-attachments/assets/153e305f-e440-4879-b7fa-fd184590a087)
![image](https://github.com/user-attachments/assets/8d7557fb-177c-4fc6-b9fa-3591449bf0c0)





