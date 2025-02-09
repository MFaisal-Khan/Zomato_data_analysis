# Zomato Data Analysis

## Introduction
This project analyzes Zomato restaurant data to extract meaningful insights about restaurants, cuisines, ratings, and pricing. The analysis is performed using Python and Pandas in a Jupyter Notebook.

## Dataset
- The dataset used is `zomato.csv`, which contains information about restaurants listed on Zomato.
- Key columns include:
  - `Restaurant Name`
  - `Cuisines`
  - `Average Cost for two`
  - `Rating`
  - `City`
  - `Votes`

## Analysis Steps
1. **Data Loading & Exploration**
   - Read the dataset using Pandas.
   - Check data types and missing values.
   - Display basic statistics.
   
2. **Data Cleaning**
   - Handle missing values and duplicates.
   - Convert data types if necessary.

3. **Exploratory Data Analysis (EDA)**
   - Distribution of restaurant ratings.
   - Most popular cuisines.
   - Average cost analysis across different cities.
   - Relationship between votes and ratings.

4. **Visualization**
   - Various charts and graphs to visualize restaurant trends.
   - Libraries used: Matplotlib and Seaborn.

## Usage
To run the analysis:
1. Install the required libraries:
   ```bash
   pip install pandas matplotlib seaborn jupyter
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook zomato_cleaned_data.ipynb
   ```
3. Execute the cells to analyze the dataset.

## Results & Insights
- Popular cuisines and cities with the most restaurants.
- Pricing trends across different locations.
- How customer ratings and votes correlate.

## Conclusion
This analysis helps understand restaurant trends, customer preferences, and pricing structures in the Zomato dataset. It can be used for business insights or further machine learning applications.

## Author
Faisal

