# Waze User Churn Prediction

![Data Analytics](https://www.freecodecamp.org/news/content/images/2023/04/Data-Analytics-Advanced-Certifications.jpg)

# Google Advanced Data Analytics Professional Certificate Projects

This repository contains the project completed as part of the Google Advanced Data Analytics Professional Certificate program. The program focuses on developing skills in data analysis, 
data visualization, and machine learning using Google Cloud Platform (GCP) tools and services.

## Table of Contents

# Waze User Churn Prediction

![Waze Logo]([https://images.app.goo.gl/5BR5Qv7JreYWyuua6](https://images.app.goo.gl/waTXXw6mF5JQywtn6))

## Project Overview

This project focuses on predicting user churn for Waze, a popular GPS navigation software. The main goal is to build models that can accurately identify users at risk of churning by analyzing patterns in user behavior and interactions with the app. Accurate churn prediction helps companies like Waze retain users by implementing targeted retention strategies, ultimately reducing user loss and improving profitability.

The dataset for this project is sourced from Kaggle and contains various features related to user behavior, including app sessions, driving patterns, and more.

## Objectives

The objectives of this project are to:
- **Develop and evaluate multiple machine learning models** to predict churn, including Random Forest and XGBoost.
- **Apply deep learning models** such as Convolutional Neural Networks (CNN), Recurrent Neural Networks (RNN), Long Short-Term Memory networks (LSTM), and Gated Recurrent Units (GRU) for more complex patterns in the data.
- **Analyze and interpret the results** to provide actionable insights for reducing user churn.

## Dataset

The dataset consists of 13 attributes and 14,999 entries that capture user behavior and interactions with the Waze app. Key features include:
- `sessions`: Number of app sessions initiated by a user.
- `drives`: Number of driving sessions recorded by the user.
- `driven km drives`: Total distance driven by the user.
- `label`: Churn indicator (1 for churned users, 0 otherwise).
  
For more information, refer to the [dataset on Kaggle](https://www.kaggle.com/datasets/juliasuzuki/waze-dataset-to-predict-user-churn).

## Project Structure

1. **Exploratory Data Analysis (EDA)**
   - Analyzed distributions of key features, identified outliers, and examined relationships between variables.
   - Applied univariate and bivariate analysis to understand the characteristics of the dataset.

2. **Data Preparation and Feature Engineering**
   - Cleaned the dataset by handling missing values and outliers.
   - Created new features such as `Kilometers per Drive` and `Percentage of Sessions to Favorite Destinations` to enhance model performance.
   - Applied the Synthetic Minority Over-sampling Technique (SMOTE) to address class imbalance.
   - Standardized numerical features using `StandardScaler` to improve model performance.

3. **Machine Learning Models**
   - Implemented and evaluated machine learning models like Random Forest and XGBoost.
   - Tuned hyperparameters and compared results using metrics such as accuracy, precision, recall, F1-score, and AUC-ROC.

4. **Deep Learning Models**
   - Built several deep learning models, including:
     - **CNN**: Achieved the highest overall performance with an accuracy of 74.3% and an AUC-ROC of 0.737.
     - **RNN**: Captured sequential data patterns with an accuracy of 72.85%.
     - **LSTM**: Designed to capture long-term dependencies in the data.
     - **GRU**: Showed strong recall performance with an accuracy of 73.05%.

5. **Model Evaluation**
   - Compared model performance using evaluation metrics. The CNN model emerged as the best-performing model overall, while the GRU model excelled in identifying true churners (high recall).

## Key Results

- **Best Model**: The CNN model had the highest overall performance, with an accuracy of 74.3%, precision of 67%, and an AUC-ROC of 0.737.
- **GRU Model**: Achieved the highest recall of 72.83%, making it particularly useful in scenarios where minimizing false negatives is crucial.
- **Random Forest and XGBoost**: Provided competitive results but were outperformed by the deep learning models.

## Conclusion

The deep learning models, especially the CNN and GRU, demonstrated strong predictive performance for Waze user churn. The CNN model, in particular, provides a balanced approach and can be used to deploy churn prediction strategies. By identifying at-risk users, Waze can apply targeted interventions to retain users and improve overall customer retention.

## Future Work

- Fine-tune models with more hyperparameter optimization.
- Explore additional deep learning models or ensemble methods for better performance.
- Integrate the model predictions into Waze’s customer retention strategies.

---

Let me know if you'd like to add or adjust anything further!
