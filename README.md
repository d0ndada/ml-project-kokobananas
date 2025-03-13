# Machine Learning Project - E-Commerce Revenue Prediction

## 📌 Project Overview
This project focuses on predicting **whether a user will generate revenue** in an e-commerce setting using **machine learning models**. The dataset contains user behavior data, such as **page visits, session durations, and special events**, which are analyzed to determine their impact on revenue generation.

## 🛠 Approach
- **Data Cleaning & Preprocessing**
  - Removed duplicate columns and missing values.
  - Identified and handled incorrect/negative values (e.g., Bounce Rates > 1, session durations that don’t match visit counts).
  - Standardized categorical data (e.g., fixing inconsistent month labels like "Sept" vs. "Sep").
  
- **Exploratory Data Analysis (EDA)**
  - Analyzed feature distributions and correlations with revenue.
  - Identified extreme values and patterns in user behavior.
  
- **Feature Engineering**
  - Adjusted session-related features for better representation.
  - Handled categorical variables to improve model interpretability.

- **Model Training & Evaluation**
  - Implemented **classification models** to predict revenue generation.
  - Compared different algorithms and evaluated their performance.
  - Used metrics like **accuracy, precision, recall, and F1-score** for evaluation.

## 🔑 Key Findings
- Certain features, such as **visit duration and special day indicators**, significantly impact revenue prediction.
- Cleaning and normalizing the data improved model performance.
- Handling missing and extreme values was crucial for better predictions.
- Some features showed anomalies that required correction (e.g., "Administrative" time inconsistencies).

## 📌 Conclusion
This project demonstrated how **machine learning models can predict user purchase intent** based on behavioral data. Further improvements could include **feature selection, hyperparameter tuning, and testing advanced models** like ensemble learning or neural networks.

