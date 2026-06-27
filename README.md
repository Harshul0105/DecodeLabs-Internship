# DecodeLabs-Internship

# Data Cleaning, Exploratory Data Analysis & Feature Engineering

## Overview

This project focuses on cleaning, analyzing, and transforming an e-commerce dataset into a machine learning-ready dataset. It was completed as part of the **Decode Labs Data Science Internship – Project 1**.

The project demonstrates the complete data preprocessing workflow, including missing value handling, outlier detection, feature engineering, visualization, and exporting a cleaned dataset.

---

## Dataset

**Dataset:** E-commerce Sales Dataset

The dataset contains information such as:

* Order Date
* Product
* Quantity
* Unit Price
* Total Price
* Items in Cart
* Coupon Code
* Customer and Order Details

---

## Objectives

* Perform Exploratory Data Analysis (EDA)
* Identify and handle missing values
* Detect and treat outliers
* Engineer new features from existing data
* Visualize important trends
* Generate a cleaned dataset for future machine learning tasks

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## Project Workflow

### 1. Data Loading

* Imported the dataset using Pandas.
* Displayed the first few records.
* Inspected dataset information and summary statistics.

### 2. Exploratory Data Analysis

Performed:

* Dataset overview
* Statistical summary
* Missing value analysis
* Data type inspection

### 3. Missing Value Handling

The `CouponCode` column contained missing values.

Missing values were replaced with:

```python
"No Coupon"
```

---

### 4. Outlier Detection

Outliers were identified using:

* Boxplots
* Interquartile Range (IQR)

Columns inspected:

* Quantity
* UnitPrice
* ItemsInCart
* TotalPrice

---

### 5. Outlier Treatment

Applied the **IQR Method** to cap extreme values in the **TotalPrice** column.

---

### 6. Feature Engineering

Created the following new features:

| Feature      | Description                                              |
| ------------ | -------------------------------------------------------- |
| OrderMonth   | Month extracted from the Order Date                      |
| OrderDay     | Day extracted from the Order Date                        |
| DiscountUsed | Indicates whether a coupon was applied (1 = Yes, 0 = No) |

---

### 7. Data Visualization

Visualizations include:

* Missing Value Heatmap
* Boxplots
* Correlation Heatmap

These visualizations helped understand data quality and relationships between numerical variables.

---

### 8. Export Cleaned Dataset

The processed dataset was exported as:

```
Cleaned_dataset.csv
```

---

## Project Structure

```
Project/
│
├── Project1.ipynb
├── Dataset for Data Analytics - Sheet1.csv
├── Cleaned_dataset.csv
└── README.md
```

---

## Results

* Successfully handled missing values.
* Reduced the impact of outliers.
* Created new features to improve future predictive modeling.
* Generated a clean dataset ready for machine learning.

---

## Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Missing Value Imputation
* Outlier Detection & Treatment
* Feature Engineering
* Data Visualization
* Statistical Analysis
* Data Preprocessing

---

## Future Improvements

* Apply advanced imputation techniques such as KNN Imputation.
* Perform feature scaling and encoding.
* Train machine learning models using the cleaned dataset.
* Build an interactive dashboard using Power BI or Tableau.

---

## Author

**Harshul Kumawat**

B.Tech CSE (AI & ML)

Decode Labs Data Science Internship
