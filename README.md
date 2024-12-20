# Black_Friday_data_analysis_using_Python

## Prerequisites
- **Libraries Required**: Pandas, Numpy, Seaborn.

---

## Overview
Black Friday is a shopping holiday following Thanksgiving, famous for its deep discounts and special deals across a range of products. This project aims to analyze a dataset containing **537,578 rows and 12 columns** to provide valuable insights for market understanding and strategic planning.

---

## Project Goals
The analysis is divided into 7 key sections to ensure thorough exploration of the dataset:

### 1. Dataset Walkthrough
- Initial exploration of the dataset:
  - Column names and data types.
  - Identification of null values in `Product_Category_2` and `Product_Category_3`.
- **Resolution**:
  - Dropped `Product_Category_2` and `Product_Category_3` columns to avoid data loss.

### 2. Analyzing Columns
- Used `unique()` and `nunique()` functions to identify unique values in each column.
- **Examples**:
  - Determined the total number of customers and products using `User_ID` and `Product_ID`.
  - Analyzed unique values in `Gender` and `Age`.

### 3. Analyzing Gender
- **Key Findings**:
  - Male customers significantly outnumber female customers.
  - Used `groupby` to identify purchasing trends by gender.
- **Visualizations**:
  - Pie charts and bar plots to showcase insights.

### 4. Analyzing Age & Marital Status
- **Key Findings**:
  - Identified the age group with the highest number of orders and purchasing amounts.
  - Observed that **60% of the individuals are unmarried** and **40% are married**.
- **Visualizations**:
  - Pie charts and bar plots for better understanding.

### 5. Multi-Column Analysis
- Merged multiple columns for analysis, such as `Age` and `Gender`.
- **Visualizations**:
  - Used the Seaborn library for enhanced data representation with legends (`hue` parameter).

### 6. Occupation and Products Analysis
- Analyzed `Occupation`, `Product_ID`, and `Product_Category_1` columns.
- **Visualizations**:
  - Used `countplot` and grouped bar plots to determine:
    - Most frequent data in each column.
    - Product with the highest purchasing amount.

### 7. Combining Gender & Marital Status
- Combined `Gender` and `Marital Status` columns for deeper insights.
- **Visualizations**:
  - Countplots created using Seaborn to identify trends in the combined data.

---

## Questions for Discussion
1. Why did we choose to drop `Product_Category_2` and `Product_Category_3` instead of imput
