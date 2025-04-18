# Google Play Store Apps Analysis

## Overview

This project involves a comprehensive analysis of the Android app market, using data from over ten thousand apps available on Google Play. By exploring insights in the data, we aim to devise strategies to drive growth and retention for mobile applications.

## Data Sources

We use two main datasets:
1. `apps.csv`: Contains details of Google Play applications, including features like category, rating, size, installs, price, and more.
2. `user_reviews.csv`: Contains 100 pre-processed reviews per app, including sentiment analysis with three features: Sentiment, Sentiment Polarity, and Sentiment Subjectivity.

## Steps Taken

### 1. **Data Exploration**
   - Load the dataset.
   - Examine the structure and content using sampling and summary methods.

### 2. **Data Cleaning**
   - Remove duplicates from the dataset.
   - Clean the `Installs` and `Price` columns by stripping special characters (`+`, `,`, `$`).
   - Print a summary of the dataframe to ensure successful cleaning.

### 3. **Data Type Correction**
   - Convert `Installs` and `Price` columns to float data types for numerical computations.

### 4. **Exploring App Categories**
   - Analyze app categories to identify market trends.
   - Visualize the number of apps in each category using bar plots.

### 5. **Distribution of App Ratings**
   - Compute the average app rating.
   - Visualize the distribution of ratings to analyze performance across categories.

### 6. **Size and Price Analysis**
   - Study app sizes and prices to understand user preferences.
   - Investigate correlations between size/price and app ratings.

### 7. **Category-Price Relation**
   - Analyze pricing trends across categories.
   - Filter out "junk" apps to clean pricing data.

### 8. **Popularity Analysis**
   - Compare install numbers for free vs. paid apps using box plots.

### 9. **Sentiment Analysis**
   - Merge datasets to analyze user reviews.
   - Conduct sentiment analysis to evaluate user perceptions of free vs. paid apps.

## Tools Used

- Python (Pandas, Numpy, Seaborn, Matplotlib, Plotly)
- Jupyter Notebook

## Key Insights

- Apps in `Family` and `Game` categories dominate the market share.
- Highly-rated apps tend to be lightweight (2–20 MB) and affordable (under $10).
- Free apps receive harsher user feedback than paid apps.

## Next Steps

- Extend the analysis to other app stores.
- Perform predictive modeling to forecast app success based on historical data.
- Refine app pricing strategies using advanced statistical methods.
