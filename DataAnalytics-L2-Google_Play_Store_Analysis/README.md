# Google Play Store Analysis

## Project Overview

This project analyzes Google Play Store applications and user reviews to identify patterns in app categories, ratings, installations, pricing, estimated revenue, and user sentiment.

The project was completed as part of the **Oasis Infobyte Data Analytics Internship Program (OIB-SIP)**.

## Objectives

* Analyze app category distribution and identify saturated categories.
* Explore rating distributions and average ratings by category.
* Investigate the relationship between app size and installations.
* Compare free and paid applications.
* Examine paid app price distributions and estimate revenue by category.
* Perform sentiment analysis on user reviews.
* Compare user sentiment across app categories.
* Present data-driven insights for app developers.

## Datasets

The project uses two datasets:

1. **Google Play Store Apps** — app categories, ratings, reviews, size, installations, prices, and other app details.
2. **Google Play Store User Reviews** — review text and sentiment-related information.

Both raw and cleaned datasets are included in this project folder, where available.

## Tools and Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* VADER Sentiment Analysis
* Plotly

## Project Workflow

1. Load and inspect the datasets.
2. Clean duplicate records, missing values, invalid values, and data types.
3. Perform exploratory data analysis.
4. Visualize app categories, ratings, installations, size, and pricing.
5. Calculate estimated paid-app revenue by category.
6. Apply VADER to classify reviews as positive, negative, or neutral.
7. Compare sentiment across categories.
8. Summarize findings and recommendations.

## Key Analysis Areas

### App Categories and Ratings

Analyze the distribution of apps across categories and compare their average ratings.

### App Size and Installations

Use a scatter plot and correlation analysis to explore the relationship between app size and installations.

### Pricing and Estimated Revenue

Compare free and paid apps, examine paid app prices, and estimate revenue using listed prices and installation counts.

**Note:** Estimated revenue is an approximation, not verified actual earnings.

### User Sentiment

Use VADER sentiment analysis to classify review text and examine sentiment patterns across app categories.

## Conclusion

This project demonstrates how data cleaning, exploratory data analysis, visualization, and sentiment analysis can help developers understand app-market patterns and user feedback.

## Project Files

* `Google_Play_Store_Analysis.ipynb` — analysis notebook
* `googleplaystore.csv` — original apps dataset, if included
* `googleplaystore_user_reviews.csv` — original reviews dataset, if included
* `googleplaystore_cleaned.csv` — cleaned apps dataset
* `googleplaystore_reviews_cleaned.csv` — cleaned reviews dataset

## Author

**Rithika S**
B.Tech — Biomedical Engineering
Aspiring Data Analyst

**Organization:** Oasis Infobyte
**Program:** OIB-SIP Data Analytics Internship
**Duration:** September 2026 – October 2026

