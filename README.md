# ML_Task_01
This project focuses on building a linear regression model to predict house prices based on features like square footage, number of bedrooms, and bathrooms. The goal was to develop a regression line that accurately predicts house prices (dependent variable) based on selected features (independent variables).

# Dataset
The dataset used in this project is sourced from Kaggle: https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data.

# Steps to Use the Dataset
Download all four files from the provided link.
Upload the files to your Google Drive in a folder named Datasets for easier access.
Open Google Colab.
Add a code cell in the provided .ipynb notebook to mount your Google Drive.
Execute the code found in the House_Price_Prediction.ipynb file, using the train.csv file for model training.

# Key Learnings and Process Overview
1. Efficient Data Handling
Focused on using the correct dataset (train.csv) for training and evaluation to ensure feature and target variable accuracy.
Understood the significance of managing multiple datasets effectively for analysis.
2. Feature Engineering and Data Preparation
Selected relevant features like LotArea, BsmtFullBath, BsmtHalfBath, FullBath, HalfBath, BedroomAbvGr, and TotRmsAbvGrd that influence house prices.
Emphasized the importance of preprocessing data to ensure it's ready for machine learning models.
3. Linear Regression Implementation
Developed a linear regression model using scikit-learn.
Trained the model on the dataset and made predictions.
Evaluated the model’s performance using key metrics such as Mean Squared Error (MSE) and R-squared to assess prediction accuracy and model fit.
4. Data Visualization and Interpretation
Created scatter plots to visualize the relationship between actual and predicted house prices.
Learned to include a reference line (perfect prediction line) in visualizations to better interpret model performance.
5. Model Evaluation and Improvement
Analyzed model performance and explored ways to improve predictions using evaluation metrics.
Leveraged visual insights to identify areas where the model could be further optimized.

# Conclusion
This project provided hands-on experience with essential machine learning concepts like data handling, feature selection, model training, evaluation, and visualization. These skills are fundamental for developing and assessing predictive models, especially in real-world applications like house price prediction.
