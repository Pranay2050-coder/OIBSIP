Data Analytics Project Portfolio :-
This repository contains three machine learning & data analysis tasks showcasing Exploratory Data Analysis (EDA), Customer Segmentation using Clustering, and Predictive Modeling with Linear Regression.

Task 1 – Exploratory Data Analysis (EDA) on Retail Sales Data
File: EDA-on-Retail-Sales-Data.ipynb

🎯 Objective :-
Analyze retail sales to gain insights into customer behavior, product performance, and revenue trends.

Explore opportunities to boost sales and customer engagement.

🛠️ Steps Performed :-
Data Loading & Cleaning

Imported retail_sales_dataset.csv and removed duplicates/missing values.

Descriptive Statistics

Computed mean, median, mode, and standard deviation for numerical attributes.

Time Series Analysis

Analyzed sales trends by grouping transactions by date, visualized seasonal patterns.

Customer & Product Insights

Spending analysis by gender and age groups.

Identified best-selling product categories and purchase quantities.

Visualization

Generated line plots, bar charts, and heatmaps for better data storytelling.

🧰 Tools Used :-
Python libraries: Pandas, Matplotlib, Seaborn, NumPy

✅ Outcomes :-
Top categories: Electronics, Clothing, and Beauty contributed most revenue.

Customer insights: Age 25–44 had higher transactions; spending was balanced between genders.

Trends: Seasonality detected with sales spikes during certain months.

Task 2 – Customer Segmentation Analysis
File: Customer-Segmentation-Analysis.ipynb

🎯 Objective :-
Segment customers of an e-commerce business based on demographics and purchase behavior.

Provide targeted marketing recommendations.

🛠️ Steps Performed :-
Data Exploration

Loaded ifood_df.csv with ~2205 customers and 39 features.

Data Cleaning & Feature Engineering

Created TotalPurchases and TotalCampaignsAccepted.

Checked missing values (none).

Descriptive Statistics

Income, age, spending, and web visits summarized.

K-Means Clustering

Features scaled using StandardScaler.

Optimal number of clusters determined via Elbow Method (k=4).

Visualization

Cluster distribution and characteristics compared across income, age, purchase frequency, etc.

🧰 Tools Used :-
Python libraries: Pandas, Scikit-learn (KMeans, StandardScaler), Matplotlib, Seaborn

✅ Outcomes :-
Formed 4 clusters of distinct customer groups.

Cluster 0: High-income, high spenders, frequent buyers.

Cluster 1: Low-income, minimal engagement.

Cluster 2: Older, loyal customers with large purchases.

Cluster 3: Moderate income, average spenders.

Insights helped tailor marketing campaigns toward high-value vs. low-engagement customers.

Task 3 – Predicting House Prices with Linear Regression
File: Predicting-House-Prices-with-Linear-Regression.ipynb

🎯 Objective :-
Predict house prices using features like area, bedrooms, bathrooms, furnishing status, and more.

Build a Linear Regression model for price estimation.

🛠️ Steps Performed :-
Data Loading & Exploration

Loaded Housing.csv dataset with 545 entries, 13 features.

Data Cleaning & Encoding

Converted categorical features (furnishing status, amenities) using One-Hot Encoding.

Model Training

Split data into train/test sets.

Applied Linear Regression model from Scikit-learn.

Model Evaluation

Measured performance using MSE, RMSE, and R².

Compared predicted vs. actual prices via scatter plots.

🧰 Tools Used :-
Python libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

✅ Outcomes
Built a Linear Regression model that can predict housing prices with reasonable accuracy.

Found area, number of bedrooms, and location-related features to be the strongest predictors.

Visual correlation between actual and predicted values confirmed model usefulness.


