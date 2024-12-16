# Netflix Dataset Exploratory Data Analysis (EDA)

This project performs Exploratory Data Analysis (EDA) on the Netflix dataset using Apache Spark. The analysis focuses on extracting insights related to content type distribution, production trends, top content-producing countries, and content ratings.

## Requirements
- Python 3.8+
- Apache Spark 3.0+
- PySpark library

## Dataset Description
The dataset `netflix_titles.csv` includes the following fields:
- **type**: Type of content (Movie or TV Show)
- **release_year**: Year of release
- **country**: Country where the content was produced
- **rating**: Content rating (e.g., PG, R)

## Features
1. **Initialize Spark**: Creates a Spark session for data processing.
2. **Load Data**: Loads the `netflix_titles.csv` dataset into a Spark DataFrame.
3. **Analysis**:
   - **Schema & Record Count**: Displays the schema and number of records.
   - **Content Type Distribution**: Visualizes the distribution of Movies vs. TV Shows.
   - **Yearly Trends**: Analyzes production trends over the years.
   - **Top Countries**: Identifies the top 10 countries producing the most content.
   - **Ratings Distribution**: Shows the distribution of content ratings.

## Setup and Usage
1. Download the `netflix_titles.csv` dataset and place it in the project directory.
2. Install required dependencies:
   ```bash
   pip install pyspark
   ```
3. Run the analysis script:
   ```bash
   python netflix_eda.py
   ```