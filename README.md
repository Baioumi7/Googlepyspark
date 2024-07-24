# Google Play Store Data Analysis using PySpark


![114-1143971_google-play-logo-google-play-logo-transparent-background](https://github.com/Baioumi7)

This project utilizes PySpark to analyze a dataset obtained from Kaggle containing information about various apps on the Google Play Store.

## Overview

The aim of this project is to perform exploratory data analysis and extract insights from the Google Play Store dataset. PySpark is used for data processing and analysis, and SQL queries are executed to derive valuable information such as top reviews, top installations, category-wise distributions, and top paid apps.

## Dataset

The dataset used in this project is obtained from Kaggle and contains the following columns:
- App
- Category
- Rating
- Reviews
- Installs
- Type
- Price
- Genres

## Analysis Steps

The analysis steps involve the following:

1. Data Cleaning:
   - Dropping unnecessary columns.
   - Converting columns to appropriate data types.
   - Handling special characters in 'Installs' and 'Price' columns.

2. Creating a Temporary View:
   - Creating a temporary view 'Apps' to execute SQL queries.

3. SQL Queries:
   - Top reviews given to the apps.
   - Top 10 installs given to the apps.
   - Category-wise distribution of installs.
   - Top paid apps.
   - Most Reviewed Apps.
   - Price Distribution of Paid Apps.

## Files

- `analyze_google_play.py`: Python script containing the PySpark code for data analysis.
- `googleplaystore.csv`: Dataset used for analysis (not included in this repository).

## Usage

To run the analysis:
1. Ensure you have a PySpark environment set up.
2. Place the `googleplaystore.csv` file in the appropriate directory.
3. Update the file path in the `analyze_google_play.py` script to point to your dataset.
4. Execute the `analyze_google_play.py` script using PySpark.

## Dependencies

- PySpark

## Acknowledgements

- Kaggle for providing the dataset.

Feel free to explore the code and modify it as needed for your analysis.

If you have any questions or suggestions, please feel free to reach out.

