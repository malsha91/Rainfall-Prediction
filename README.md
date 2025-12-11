This project applies machine learning techniques to predict rainfall using meteorological data. The dataset, sourced from Kaggle, includes features such as temperature, humidity, wind speed, atmospheric pressure, and other weather-related parameters.

The workflow includes comprehensive data preprocessing, involving handling missing values, managing outliers, and applying normalization where necessary. An Exploratory Data Analysis (EDA) was conducted with visualizations to understand feature distributions, correlations, and overall data patterns.

Two machine learning models were developed and evaluated: Random Forest and Support Vector Machine (SVM). Model performance was assessed using standard classification metrics, including Accuracy, Precision, Recall, and F1-score. Hyperparameter tuning was also performed to improve the efficiency and performance of the models.

Finally, the best-performing model was serialized using Pickle, allowing it to be reused for future rainfall predictions without retraining.
