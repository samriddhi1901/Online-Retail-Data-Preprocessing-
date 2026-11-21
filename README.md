# Online-Retail-Data-Preprocessing-
# Online Retail Data Preprocessing and Feature Engineering

## Project Overview
This project focuses on performing data preprocessing and feature engineering on a real-world Online Retail dataset using Python. The objective is to improve data quality and prepare the dataset for effective machine learning model development.

## Aim
To perform data preprocessing and feature engineering by handling missing values, normalizing numerical features, encoding categorical variables, and visualizing the data.

## Dataset
- **Source:** UCI Machine Learning Repository
- **Dataset:** Online Retail
- **Link:** https://archive.ics.uci.edu/dataset/352/online+retail
- **Domain:** E-commerce and Retail Analytics

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Project Workflow

### 1. Data Loading and Exploration
- Imported the dataset using Pandas.
- Examined the dataset structure, columns, and data types.
- Generated descriptive statistics.

### 2. Data Cleaning
- Identified and handled missing values.
- Removed duplicate records.
- Checked data quality.

### 3. Outlier Detection
- Used boxplots to visualize outliers.
- Applied the Interquartile Range (IQR) method to identify unusual observations.

### 4. Feature Engineering
Created new features:
- TotalAmount
- InvoiceYear
- InvoiceMonth
- InvoiceDay
- InvoiceHour
- IsWeekend

### 5. Numerical Normalization
Applied Min-Max Scaling to numerical features using Scikit-learn.

### 6. Categorical Encoding
Applied One-Hot Encoding to transform categorical country values into numerical columns.

### 7. Data Visualization
Created:
- Histograms
- Boxplots
- Correlation heatmaps
- Country-wise transaction charts

## Project Files
- `Online_Retail_Data_Preprocessing.ipynb` – Complete implementation and analysis.
- `README.md` – Project documentation.
- `requirements.txt` – Required Python libraries.

## Key Learnings
- Understanding real-world datasets.
- Handling missing and duplicate values.
- Detecting outliers using statistical techniques.
- Creating meaningful features.
- Applying normalization and encoding techniques.
- Visualizing data using Python libraries.

## Conclusion
The project demonstrates the importance of data preprocessing and feature engineering in preparing real-world data for machine learning applications.

## Author
Data Science Student

## Acknowledgement
Dataset provided by the UCI Machine Learning Repository. Please refer to the original dataset page for licensing and attribution information.
