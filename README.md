

---

# Netflix Data Cleaning, Analysis, and Visualization Using Python

## Overview
This project delves into cleaning, analyzing, and visualizing a Netflix dataset to uncover patterns and provide insights into its extensive content library. By employing data cleaning techniques and statistical analysis, the project highlights trends in content distribution across genres, countries, ratings, and more. Additionally, relationships between key attributes—such as release year, content type (Movies/TV Shows), and duration—are explored using rich visualizations.

The insights gained from this analysis are valuable for understanding the diversity of Netflix's catalog and can serve as a foundation for advanced applications like trend forecasting or building content recommendation systems.

## Dataset
The dataset used in this project is a CSV file titled `Netflix Dataset`. It contains the following key attributes:

- **Show ID**: Unique identifier for each title.
- **Type**: Categorizes the content as either a Movie or a TV Show.
- **Title**: Name of the content.
- **Director**: Name(s) of the director(s) involved.
- **Cast**: List of actors/actresses featured.
- **Country**: Country of origin for the content.
- **Date Added**: The date the content was added to Netflix.
- **Release Year**: The year the content was originally released.
- **Rating**: Content rating (e.g., PG, R, TV-MA).
- **Duration**: Length of the Movie or number of seasons for TV Shows.
- **Listed In**: Genres or categories of the content.
- **Description**: A brief summary or synopsis.

The dataset is sourced from Kaggle and is available in the project directory.

## Installation
Ensure you have Python installed (version 3.7 or later). Install the required libraries by running the following command:

```bash
pip install pandas seaborn matplotlib plotly textblob
```

## Usage
1. **Dataset Placement**: Save the dataset in the project folder.
2. **Run the Notebook**: Open and execute the `Netflix_Dataset_Analysis.ipynb` Jupyter Notebook.
3. **Follow the Workflow**: The notebook provides step-by-step procedures for cleaning, analyzing, and visualizing the dataset.

## Data Cleaning
To ensure high-quality analysis, the dataset undergoes several cleaning steps:

- Addressing missing values in columns like `director`, `cast`, and `country`.
- Dropping or imputing missing data where necessary.
- Standardizing data types for specific columns, such as converting `date_added` into a date format.
- Removing duplicates or redundant entries for improved accuracy.

## Data Analysis
Key analytical tasks performed include:

- **Content Distribution**: Examining the proportions of Movies and TV Shows in the dataset.
- **Genre and Country Trends**: Identifying popular genres and the countries contributing the most content.
- **Release Trends**: Exploring the number of titles released over different years.
- **Rating Analysis**: Analyzing how content ratings vary across Movies and TV Shows.

## Data Visualization
To better interpret the data, various visualizations are created using **Matplotlib**, **Seaborn**, and **Plotly**, including:

- **Count Plots**: Visualizing the distribution of Movies vs. TV Shows.
- **Bar Charts**: Highlighting top genres, countries, and ratings.
- **Histograms**: Showing trends in numeric variables like `release_year` and `duration`.
- **Scatter Plots**: Exploring relationships, such as the age of content vs. duration.

## Sentiment Analysis
Using **TextBlob**, a basic sentiment analysis is performed on content descriptions to evaluate their sentiment polarity. This provides insights into whether Netflix descriptions tend to be positive, neutral, or negative.

## Results
The analysis uncovers several key findings:

- **Content Type**: Movies dominate Netflix's catalog, with fewer TV Shows in comparison.
- **Country Contributions**: The US leads in content production, followed by significant contributions from countries like India and the UK.
- **Recent Releases**: Content released after 2015 makes up a large portion of the catalog.
- **Popular Genres**: Categories like documentaries, stand-up comedy, and drama are among the most prevalent.
- **Sentiment Trends**: Content descriptions generally exhibit a neutral to slightly positive sentiment.

## Acknowledgments
The dataset used in this project is sourced from the **Kaggle Netflix Shows Dataset**, which provides a valuable foundation for analyzing Netflix's content library.

--- 

