# Video Game Sales Forecasting Project

## Objective  
Predict video game sales and identify the factors that drive commercial success using Python-based data analysis and forecasting techniques.

## Context  
As part of the TripleTen Data Science program, this project explores a dataset of over 16,000 video games across multiple platforms and genres. The goal is to uncover patterns behind high-performing titles and build a predictive model for global sales.

---

## Project Workflow

### 1. Data Exploration
- Imported and cleaned a dataset containing release year, platform, genre, critic and user scores, and regional sales
- Assessed missing values, duplicates, and data types
- Identified outliers and anomalies in scoring variables

### 2. Data Preparation
- Standardized column names, handled missing values, and converted data types
- Filtered out incomplete entries for accurate statistical modeling
- Normalized categorical data for analysis compatibility

### 3. Exploratory Data Analysis (EDA)
- Examined platform and genre performance trends
- Visualized relationships between user/critic scores and global sales
- Determined which platforms and genres dominated different eras

### 4. Hypothesis Testing
- Compared average user and critic scores using t-tests and correlation analysis
- Verified whether platform differences were statistically significant

### 5. Forecasting Model Development
- Built and evaluated predictive models to forecast future sales
- Compared multiple regression approaches to determine feature importance
- Interpreted results and discussed business implications for future releases

---

## Key Insights
- Sales correlate strongly with critic scores and moderately with user ratings
- Platform choice heavily influences success—older systems underperform post-2010
- The action genre consistently leads across regions, but preferences vary by market

---

## Technologies Used
**Languages:** Python  
**Libraries:** Pandas, NumPy, Matplotlib, Seaborn, SciPy, Scikit-learn  
**Techniques:** Data Cleaning, EDA, Hypothesis Testing, Regression Analysis, Forecasting

---

## Results
Created a regression-based forecasting model that identifies the most influential features behind video game sales. The analysis provides actionable insights for product strategy and market forecasting.

---

## Links
- **Full Notebook:** [View on GitHub](#)  
- **Dataset:** Included (`games.csv`)  
- **Author:** Dr. Danisha L. Thomas
