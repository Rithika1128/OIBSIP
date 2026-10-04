# OIBSIP Level 1 Task 2 — Airbnb Data Cleaning

## 📌 Project Overview

This project was completed as part of my **Data Analytics Internship at Oasis Infobyte (OIBSIP)**.

The objective of this project is to clean and prepare an Airbnb dataset for further analysis. The dataset was checked for missing values, duplicate records, incorrect data types, inconsistent text formatting, invalid values, and statistical outliers.

## 📂 Dataset

The dataset used in this project is the **New York City Airbnb Open Data (2019)** dataset.

**Source:** Kaggle — New York City Airbnb Open Data  
**Author:** Dgomonov  
**License:** CC0: Public Domain

The dataset contains Airbnb listing information from New York City, including host details, neighbourhoods, room types, prices, reviews, and availability.

[Dataset Source](https://www.kaggle.com/dgomonov/new-york-city-airbnb-open-data)

The dataset contains Airbnb listing information such as:

- Listing ID
- Host details
- Neighbourhood and location
- Room type
- Price
- Minimum nights
- Number of reviews
- Last review date
- Reviews per month
- Host listing count
- Availability

### Files Included

- `airbnb_raw.xlsx` — Original dataset
- `OIBSIP_L1_Task2_Airbnb_Data_Cleaning.ipynb` — Data cleaning notebook
- `airbnb_cleaned.csv` — Cleaned dataset

## Data Cleaning Process

The following steps were performed:

### 1. Initial Data Inspection
- Checked dataset shape and column information
- Examined data types
- Identified missing values
- Checked for duplicate records

### 2. Missing Value Handling
- Filled missing `name` values with `Unknown`
- Filled missing `host_name` values with `Unknown`
- Filled missing `reviews_per_month` values with `0` because these listings had no reviews
- Converted `last_review` into a datetime format while retaining missing dates for listings with no reviews

### 3. Duplicate Detection
No duplicate rows were found in the dataset.

### 4. Invalid Value Handling
Listings with a price of `0` were removed because a zero price is not meaningful for standard Airbnb price analysis.

- Rows before cleaning: **48,895**
- Rows removed due to zero price: **11**
- Final rows: **48,884**

### 5. Data Type Correction
The `last_review` column was converted from text/object format to the appropriate datetime format.

### 6. Inconsistent Formatting
Text columns were checked for unwanted spaces and possible encoding issues. Recoverable text encoding issues were corrected.

### 7. Outlier Detection
The **Interquartile Range (IQR)** method was used to identify statistical outliers in numerical columns.

Outliers were retained when they could represent legitimate Airbnb listings or host behaviour rather than data errors.

## 📊 Before and After

| Metric | Before Cleaning | After Cleaning |
|---|---:|---:|
| Rows | 48,895 | 48,884 |
| Columns | 16 | 16 |
| Duplicate Rows | 0 | 0 |
| Missing Values | 20,152 | 10,051* |

\*The remaining missing values are in `last_review` for listings with no reviews. These were intentionally retained because there is no valid review date to fill.

## 💡 Conclusion

In this project, I cleaned and prepared an Airbnb dataset by checking for missing values, duplicate records, incorrect data types, inconsistent text formatting, invalid values, and outliers.

I removed listings with zero prices, handled missing values based on the meaning of each column, converted the `last_review` column into the correct date format, and checked the dataset for unusual values using the IQR method.

The final dataset contains **48,884 rows with no duplicate records** and is ready for further analysis.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Internship

**Oasis Infobyte — OIBSIP Data Analytics Internship**

**Track:** Data Analytics  
**Level:** Level 1  
**Task:** Airbnb Data Cleaning## 
The dataset contains Airbnb listing information from New York City, including host details, neighbourhoods, room types, prices, reviews, and availability.

[Dataset Source](https://www.kaggle.com/dgomonov/new-york-city-airbnb-open-data)
