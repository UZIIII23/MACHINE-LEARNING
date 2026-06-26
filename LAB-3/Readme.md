## Machine Learning Lab 3 : Missing Data Handling, Outlier Detection & Holiday Feature Engineering

Overview:

This repository contains the implementation of essential **data preprocessing techniques** for the American Electric Power (AEP) hourly electricity consumption dataset. The experiments demonstrate **missing value handling**, **outlier detection using the IQR method**, and **holiday feature engineering** to prepare the dataset for machine learning applications and time series forecasting.

### Author:

* Uzair-ur-Rehman
* Registration No: 22JZELE0471
* Department: Electrical Engineering

Repository Contents:

* Lab_3_22jzele0471.ipynb
* AEP_hourly.csv
* processed_holiday.csv
* AEP_Introducing_holidays.csv

Objectives:

* Explore and understand the AEP hourly power consumption dataset.
* Identify duplicate records and missing timestamps.
* Handle missing values using interpolation.
* Detect outliers using the Interquartile Range (IQR) method.
* Replace outliers with interpolated values.
* Introduce holiday information as a new feature.
* Prepare a clean dataset for machine learning and forecasting tasks.

Experiments Included:

### **Part A: Handling Missing Data**

* Load and explore the AEP hourly dataset.
* Convert the Datetime column into datetime format.
* Remove duplicate timestamps.
* Sort the dataset chronologically.
* Detect missing hourly timestamps.
* Resample the dataset to include missing timestamps.
* Fill missing values using linear interpolation.
* Save the cleaned dataset.

### **Part B: Outlier Identification Using IQR**

* Load the cleaned dataset.
* Detect outliers using the Interquartile Range (IQR) method.
* Replace detected outliers with NaN values.
* Fill missing values using time-based interpolation.
* Save the outlier-free dataset.

### **Part C: Introducing Holiday Feature**

* Load the cleaned dataset.
* Import the processed holiday dataset.
* Extract the date from the Datetime column.
* Merge holiday information with the AEP dataset.
* Create a binary Holiday feature:

  * **1 = Holiday**
  * **0 = Non-Holiday**
* Save the final dataset for machine learning applications.

Data Processing Summary:

The preprocessing pipeline performs the following tasks:

* Duplicate timestamp removal
* Missing timestamp identification
* Missing value interpolation
* Outlier detection using IQR
* Outlier replacement through interpolation
* Holiday feature engineering
* Final cleaned dataset generation

Technologies Used:

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook

How to Run:

1. Clone the repository.
2. Install the required libraries:
3. Launch Jupyter Notebook:
4. Open and run: Lab_3_22jzele0471.ipynb

Learning Outcomes:

* Understand the importance of data preprocessing.
* Detect and handle missing values in time series datasets.
* Identify and remove duplicate records.
* Apply interpolation techniques to recover missing data.
* Detect outliers using the IQR method.
* Perform feature engineering by introducing holiday information.
* Prepare high-quality datasets for machine learning and forecasting models.

License:

This project is submitted for academic and educational purposes.

