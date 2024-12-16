# Product Data Analysis

## Overview
This project explores the relationship between mobile device specifications and their corresponding prices. Using a dataset of product features like **RAM**, **Internal Memory**, **Display Size**, **Brand**, and customer-related attributes such as **Number of Ratings**, the target variable (**Price**) is predicted using **Machine Learning** and **Deep Learning** models.

---

# Power BI
![Demo](https://github.com/abawan7/product_data_analysis/blob/main/PBI_Screenshot.png)

---
## Objectives
1. **Standardize and Analyze Product Features**  
   - Preprocess raw product data for consistency and comparability.
   - Handle missing values, outliers, and discrepancies.
2. **Uncover Pricing Trends**  
   - Analyze the influence of features like **Display Size** and **Internal Memory** on pricing.
3. **Develop Predictive Models**  
   - Build and compare **Random Forest Regressor** and **Neural Network** models for price prediction.
4. **Provide Insights**  
   - Deliver actionable insights to manufacturers and consumers.

---

## Dataset
- **File**: product_data.csv  
- **Size**: 1,345 rows, 8 columns  
- **Key Features**: RAM, Battery Capacity, Internal Memory, Display Size, Brand, Price  
- **Preprocessing**: Missing values, duplicates, and outliers handled. Features standardized and scaled.

---

## Methodology
### Data Preprocessing
- **Handling Missing Values**: Filled using global or group means.
- **Feature Engineering**: Extracted numerical values from mixed-format columns.
- **Scaling**: Min-Max Scaling applied to numeric columns.
- **Categorical Encoding**: One-hot encoding used for Brand and Model.

### Modeling
- **Random Forest Regressor**:
  - Ensemble learning for non-linear relationships.
  - Achieved **MSE: 0.00302**, **R² Score: 0.9028**.
- **Neural Network**:
  - Fully connected network for complex relationships.
  - Achieved **MSE: 0.00549**, **R² Score: 0.8234**.

---

## Insights
1. **Top Influencing Features**: Internal Memory, RAM, Display Size.
2. **Model Performance**:
   - Random Forest is superior for small-to-medium datasets.
   - Deep Learning shows potential with larger datasets.
3. **Market Trends**:
   - Lower-priced products dominate the market.
   - Larger screens and higher internal memory are preferred by premium segments.

---

## Future Work
- Expand dataset with additional features like **Processor Type** and **Camera Quality**.
- Incorporate real-time market data for dynamic predictions.
- Experiment with advanced deep learning architectures for scalability.

---

## Repository Structure
- **`data/`**: Contains the dataset.
- **`notebooks/`**: Jupyter notebooks for data exploration, preprocessing, and modeling.
- **`models/`**: Saved machine learning and deep learning models.
- **`visualizations/`**: Graphs and plots illustrating key findings.
- **`report.pdf`**: Detailed project report.

---

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/product-data-analysis.git
   
2. Install required libraries:
   
## Contributor
* Abdullah Awan
  - <mlkabawan336@mgmail.com>
  
* Ifra Ejaz
  - <ifraejaz07@gmail.com>

