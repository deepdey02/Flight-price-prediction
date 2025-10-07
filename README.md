# Flight-price-prediction
Project Overview

This project aims to analyze and predict flight prices using real-world flight data. The notebook covers the complete data preprocessing, exploratory analysis, and feature engineering pipeline, forming a strong foundation for applying machine learning models to predict flight fares.

Key Steps Performed
1. Data Loading & Exploration

Imported the dataset using Pandas from an Excel file.

Performed initial data inspection:

Checked top records, dataset shape, and statistical summary.

Identified and handled null values and duplicate records.

Verified data types and structure for further processing.

2. Feature Engineering

Extracted Day, Month, and Year from the Date_of_Journey column.

Processed time-related columns like Dep_Time and Arrival_Time to derive meaningful features.

Cleaned and transformed categorical variables such as Airline, Source, and Destination for model compatibility.

3. Exploratory Data Analysis (EDA)

Identified:

The most preferred airline among travelers.

The major source cities from which flights take off.

The top destinations with maximum arrivals.

Visualized patterns and relationships between independent features (like duration, stops, and airline) and the target variable (price).

Used Matplotlib and Seaborn for detailed insights and data visualization.

4. Data Cleaning

Dealt with missing values using appropriate imputation techniques.

Removed or replaced inconsistent entries.

Ensured all columns were clean and consistent before model training.

Libraries Used

NumPy – Numerical operations

Pandas – Data manipulation and analysis

Matplotlib & Seaborn – Data visualization

Scikit-learn – Data preprocessing (imputation, encoding)

 Outcomes

Cleaned and transformed dataset ready for model training.

Identified key factors influencing flight prices such as Airline, Source, Destination, and Journey Date.

Built a strong EDA and feature engineering foundation for applying machine learning models like Random Forest, XGBoost, or Linear Regression for price prediction.

 Future Work

Apply ML algorithms to predict flight fares.

Tune hyperparameters to improve prediction accuracy.

Deploy the model using Flask or Streamlit for real-time flight price prediction.
