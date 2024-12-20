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
  - Dropped  only `Product_Category_3`to avoid data loss.
  - Handling missing value in column `Product_Category_2` through this we will get both way of handling missing value and get a comprehensive solution.

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
## Questions for Review
1. Why were the column `Product_Category_3` dropped instead of filling the missing values?
2. How does the purchasing trend vary between different age groups and marital statuses?
3. Which visualization technique was most effective in highlighting key insights from the dataset?
4. How can combining multiple columns provide better insights compared to analyzing individual columns?
5. Which product category or occupation group showed the highest purchasing amount, and what does it suggest for marketing strategies?
6. What insights can be derived from the difference in purchasing trends between males and females?
7. How does the marital status of individuals impact their purchasing behavior on Black Friday?
8. Which age group spends the most on Black Friday, and how can this insight be used for targeted marketing?
9. What trends can be observed in the types of products purchased by different occupations?
10. What are the possible limitations of this analysis, and how could additional data improve the insights?
