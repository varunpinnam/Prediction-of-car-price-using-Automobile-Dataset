
Project: Predicting Car Prices using Used Car Data
This project aims to analyze and visualize data from a used car dataset (available at https://www.kaggle.com/datasets/toramky/automobile-dataset/data) to predict car prices. We will follow a structured approach involving the following steps:  
1. Data Acquisition and Preparation:
•	Obtain the used car dataset from the provided URL.
•	Pre-process the data in Python to handle missing values, format it appropriately, and perform normalization or binning if necessary.
4. Exploratory Data Analysis (EDA):
•	Analyze the data to gain insights into car prices and related features.
•	This will involve calculating descriptive statistics, performing grouping analysis (groupby), analyzing variance , and exploring correlations between features and car prices.
5. Model Development:
•	We will develop and compare two machine learning models for car price prediction: 
o	Simple Linear Regression - Uses a single feature to predict car price.
o	Multiple Linear Regression - Uses multiple features to predict car price.
6. Model Review and Evaluation:
•	We will evaluate the performance of each model using various techniques: 
o	Generate regression plots to visualize the relationship between predicted and actual prices.
o	Analyze the distribution of errors to identify potential biases.

Heatmap of correlation between features 

![vertopal com_Capstone project_page-0001](https://github.com/user-attachments/assets/92670de9-8e7d-4d4a-9855-ffbdca94edba)

Lineplot between MSV and no of columns

![Screenshot (80)](https://github.com/user-attachments/assets/5c20e53e-babb-4cfb-88f0-d0853388943f)

Actual vs Predicted Prices

![Screenshot (81)](https://github.com/user-attachments/assets/da024a7a-bb6d-42d2-89d2-6ff0015d9b58)




Conclusion:

Given the presence of 27 variables in our dataset, it was hypothesized that multiple factors contribute to automobile pricing. Our comparison of prediction models confirms this hypothesis. The Multiple Linear Regression (MLR) model, which incorporates "horsepower," "curb-weight," "engine-size," and "width," exhibits the best predictive performance, as evidenced by the correlation between features. Consequently, we conclude that MLR is the most effective model for predicting car prices within this dataset
