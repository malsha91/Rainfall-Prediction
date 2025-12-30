# Rainfall Prediction using Machine Learning

## Project Overview
This project applies machine learning techniques to predict rainfall using meteorological data.  
The dataset, sourced from Kaggle, includes features such as temperature, humidity, wind speed, atmospheric pressure, and other weather-related parameters.


## Workflow
1. **Data Preprocessing**
   - Handled missing values

2. **Exploratory Data Analysis (EDA)**
   - Visualized feature distributions
   - Explored correlations between variables
   - Identified overall data patterns

3. **Model Development**
   - **Logistic Regression** (baseline model)
   - **Random Forest**
   - **Support Vector Machine (SVM)**
   - **XGBoost**
   
   Each model was trained and evaluated to compare predictive performance.

4. **Model Evaluation**
   - Metrics: Accuracy, Precision, Recall, and F1-score
   - Confusion matrices for detailed error analysis
   - Hyperparameter tuning to improve efficiency and performance

5. **Model Selection & Serialization**
   - **Random Forest was selected as the best-performing model**, achieving higher accuracy and balanced precision/recall compared to Logistic Regression, SVM, and XGBoost.
   - The chosen model was serialized using **Pickle**, enabling reuse for future rainfall predictions without retraining.


## Results Summary
- **Logistic Regression**: Served as a baseline, moderate accuracy.  
- **Random Forest**: Best overall performance, strong accuracy and balanced metrics.  
- **SVM**: Competitive but weaker than Random Forest.  
- **XGBoost**: Good performance, but Random Forest was more consistent and interpretable.  

