# QualityWine-Predictor-Using-ML
Utilizing machine learning models, this project predicts the quality of wines based on various chemical properties, aiding in quality assessment and production optimization for winemakers.

conducted a thorough analysis of a dataset containing information about wine quality. Here's a summary of what you've done:

        1.	Data Importing and Understanding: You imported necessary libraries such as NumPy, Pandas, Matplotlib, Seaborn, and Plotly Express. Then, you read the dataset into a Pandas DataFrame and checked its shape and first few rows.
        2.	Data Cleaning: You checked for missing values and found none.
        3.	Data Exploration: You visualized the distribution of the 'quality' variable using a histogram.
        4.	Data Transformation: You converted the 'quality' variable into a binary 'goodquality' variable where wines with a quality score of 7 or higher are considered good.
        5.	Data Preprocessing: You standardized the feature variables using StandardScaler and split the data into training and testing sets.
        6.	Modeling: You trained five different classification models (Decision Tree, Random Forest, AdaBoost, Gradient Boosting, and XGBoost) and evaluated their performance using classification reports.
        7.	Feature Importance: You used Random Forest and XGBoost models to determine the most important features.
        8.	Comparing Top Features: You compared the descriptive statistics of top features between good quality wines and bad quality wines.
        
