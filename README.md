# E-Commerce Data Analysis and Cleaning

## About the Project

This project focuses on exploratory data analysis (EDA), data cleaning, and preprocessing of an e-commerce dataset using Python.

The main goal is to understand the dataset's structure, identify data quality issues, handle missing values and duplicate records, standardize inconsistent data, detect outliers, and explore patterns through statistical analysis and visualizations.

This project was developed as part of my data science training.

## Objectives

- Explore the dataset's structure and summary statistics.
- Identify missing values and calculate missing data percentages.
- Handle missing numerical values using median imputation.
- Handle missing categorical values using mode imputation.
- Convert order dates into datetime format and extract date-related features.
- Detect and remove duplicate records.
- Standardize inconsistent city and category names.
- Identify and remove logically invalid records.
- Detect outliers using the Interquartile Range (IQR) method.
- Visualize numerical distributions using histograms, box plots, and count plots.
- Analyze category frequencies, customer types, payment methods, and key numerical variables.
- Compare average order totals across categories and average customer ratings across customer types.

## Dataset

The dataset contains e-commerce-related information, including order dates, cities, product categories, payment methods, customer types, unit prices, total amounts, delivery times, and customer ratings.

**Dataset source:** [Add dataset source or download link]

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn (if used)

## Data Analysis and Preprocessing

### 1. Initial Data Exploration
- Displaying the first and last 10 rows
- Checking the number of rows and columns
- Examining column names, data types, and summary statistics
- Separating numerical and categorical columns

### 2. Missing Value Analysis
- Calculating missing value counts and percentages
- Identifying columns with the highest missing value rates
- Inspecting rows containing missing values
- Filling missing numerical values with the median
- Filling missing categorical values with the mode

### 3. Date Feature Engineering
- Converting the order date column to datetime format
- Extracting the order year, month, day, and day of the week

### 4. Data Cleaning
- Detecting and removing duplicate records
- Standardizing inconsistent city names
- Standardizing inconsistent product category names
- Identifying and removing logically invalid records

### 5. Outlier Analysis
- Calculating Q1, Q3, IQR, and lower and upper bounds for unit prices
- Identifying records containing outliers
- Visualizing total amount distributions with histograms and box plots

### 6. Exploratory Data Analysis
- Examining product category frequencies
- Calculating customer type percentages
- Visualizing payment method counts
- Analyzing descriptive statistics for unit price, total amount, and customer rating
- Comparing average total amounts by category
- Comparing average customer ratings by customer type

## Key Questions

- Which product category has the highest average total amount?
- Which customer type has the highest average customer rating?
- What data quality issues exist in the dataset?
- How do the numerical variables and categorical distributions differ?

## How to Run

1. Clone or download this repository.
2. Install the required Python libraries.
3. Open the notebook or Python script.
4. Update the dataset path if necessary.
5. Run the analysis.

Install the dependencies with:

```bash
pip install pandas numpy matplotlib seaborn
```

## What I Learned

Through this project, I practiced data exploration, missing value handling, data standardization, duplicate removal, date feature engineering, outlier detection, descriptive statistics, and data visualization using Python.

I also gained experience in preparing a dataset for further analysis by identifying and addressing common data quality issues.

## Author

Sude  
Second-year Computer Engineering Student at Başkent University

Interested in Data Science, Machine Learning, Artificial Intelligence, and Software Development.
