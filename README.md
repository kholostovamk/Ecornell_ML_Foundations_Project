# Ecornell_ML_Foundations_Project


Overview

In ML Foundations Project, we embark on a hands-on journey through the entire machine learning pipeline, focusing on a real-world dataset. Specifically, the lab revolves around the World Happiness Report (WHR) data, aiming to predict happiness scores based on various socio-economic factors.
Structure

Part 1: Load the Data Set

    The data is loaded into a Pandas DataFrame from the CSV file WHR2018Chapter2OnlineData.csv.
    An initial examination of the data is performed to understand its structure.


df = pd.read_csv('data/WHR2018Chapter2OnlineData.csv')

Part 2: Exploratory Data Analysis (EDA)

    Comprehensive EDA is conducted to gain insights into the dataset.
    Techniques include statistical summaries, data type inspection, outlier detection, and visualization.
    Specific attention is paid to missing data handling, including an example of regression-based imputation for the "Delivery Quality" and "Democratic Quality" features.

Part 3: Data Preparation and Feature Engineering

    Various data preparation techniques are applied, such as addressing missingness, renaming features, handling outliers, and encoding categorical variables.
    Feature selection is guided by correlation analysis and domain knowledge.

Part 4: Model Training and Evaluation

    Different regression models are explored, including Linear Regression, Decision Tree Regressor, Random Forest Regressor, and Gradient Boosting Regressor.
    Techniques like GridSearchCV are used for hyperparameter tuning.
    Evaluation metrics such as mean squared error and R² score are used to assess model performance.

Part 5: Model Improvement

    Further model selection and feature selection techniques are applied to refine the model.
    Advanced methods like stacking regressors are explored to combine different models for improved prediction.

Key Learnings

This lab provides a holistic view of the machine learning process, emphasizing practical skills and thoughtful consideration of various modeling challenges. It serves as a valuable resource for anyone seeking to understand how to transform raw data into actionable insights through machine learning.
Technologies and Packages Used

    Language: Python
    Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, scipy
