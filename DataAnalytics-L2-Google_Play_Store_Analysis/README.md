# Google Play Store Analysis

## Overview

This project analyzes Google Play Store applications and user reviews to identify patterns in app categories, ratings, installations, pricing, estimated revenue, and user sentiment.

Completed as part of the **Oasis Infobyte Data Analytics Internship Program (OIB-SIP)**.

## Objectives

* Analyze app category distribution and identify saturated categories.
* Examine rating distributions and average ratings by category.
* Investigate the relationship between app size and installations.
* Compare free and paid applications.
* Analyze paid app prices and estimate revenue by category.
* Perform sentiment analysis on user reviews.
* Compare sentiment across app categories.
* Present data-driven insights for app developers.

## Datasets

The project uses two datasets:

* **Google Play Store Apps:** App categories, ratings, reviews, size, installations, and prices.
* **Google Play Store User Reviews:** Review text and sentiment-related information.

## Tools and Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* VADER Sentiment Analysis
* Plotly

## Methodology

1. Load and inspect both datasets.
2. Clean duplicate records, missing values, invalid values, and data types.
3. Analyze app categories and rating distributions.
4. Visualize app size versus installations and calculate correlation.
5. Compare free and paid applications.
6. Examine paid app prices and estimate revenue by category.
7. Use VADER to classify review sentiment as positive, negative, or neutral.
8. Compare sentiment across app categories.
9. Summarize findings and recommendations.

## Key Analysis Areas

### App Categories and Ratings

Explore app distribution across categories and compare average ratings.

### App Size and Installations

Use scatter plots and correlation analysis to examine the relationship between app size and installation counts.

### Pricing and Estimated Revenue

Compare free and paid apps, explore paid app price distributions, and estimate revenue using listed prices and installation counts.

*Estimated revenue is an approximation, not verified actual earnings.*

### Sentiment Analysis

Apply VADER to user reviews and examine sentiment patterns across app categories.

## Conclusion

This project demonstrates the use of data cleaning, exploratory data analysis, visualization, and sentiment analysis to understand app-market patterns and user feedback.

## Project Files

DataAnalytics-L2-Google_Play_Store_Analysis/
│
├── README.md
├── Google_Play_Store_Analysis.ipynb
├── googleplaystore_cleaned.csv
├── googleplaystore_reviews_cleaned.csv
├── googleplaystore.csv                 ← Original apps dataset
└── googleplaystore_user_reviews.csv    ← Original reviews dataset

## Author

**Rithika S**
B.Tech — Biomedical Engineering | Aspiring Data Analyst

**Organization:** Oasis Infobyte
**Program:** OIB-SIP Data Analytics Internship
**Duration:** September 2026 – October 2026


