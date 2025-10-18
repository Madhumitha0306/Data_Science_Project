Restaurant Data Analysis Project

Overview
This project analyzes a restaurant dataset to gain insights into customer preferences, restaurant ratings, and cuisine popularity.
It is divided into three levels, each containing three tasks, covering data cleaning, visualization, predictive modeling, and customer preference analysis.

The dataset includes features such as:
Restaurant ID, Restaurant Name, City, Cuisines, Aggregate rating, Votes, Price range, Average Cost for two, and more.

📂 Level 1: Data Cleaning & Basic Analysis

Task 1: Dataset Overview
* Load and preview the dataset.
* Check column names, data types, and missing values.
* Understand the basic structure and size of the dataset.

Task 2: Missing Values & Data Cleaning
* Identify and handle missing values in key columns.
* Create derived columns, e.g., Main_Cuisine from Cuisines.
* Ensure numeric columns are correctly formatted for analysis.

Task 3: Exploratory Data Analysis (EDA)
* Generate summary statistics of numeric and categorical features.
* Visualize distributions of key variables using histograms, bar plots, and count plots.
* Identify patterns and outliers for further investigation.

📂 Level 2: Customer Preference Analysis

Task 1: Cuisine Popularity
* Analyze the relationship between cuisine type and restaurant ratings.
* Identify the most common cuisines in the dataset.

Task 2: Popular Cuisines by Votes
* Sum votes per cuisine to identify customer favorites.
* Visualize top cuisines based on total votes using bar charts.

Task 3: High-Rated Cuisines

* Determine which cuisines tend to receive higher ratings.
* Compare popularity and quality by combining votes and average rating.
* Visualize insights with scatterplots to identify cuisines that are both popular and highly rated.

📂 Level 3: Advanced Analysis & Predictive Modeling

Task 1: Predictive Modeling
* Build regression models to predict the Aggregate rating of a restaurant.
* Implement Linear Regression, Decision Tree Regressor, and Random Forest Regressor.
* Split dataset into training and testing sets.
* Evaluate models using RMSE, MAE, and R² score.
* Identify important features influencing ratings.

Task 2: Customer Preference Analysis
* Analyze relationships between cuisine types and restaurant ratings.
* Identify the most popular cuisines based on votes.
* Determine which cuisines consistently receive high ratings.
* Visualize insights using bar charts and scatterplots.

Task 3: Data Visualization
* Visualize the distribution of ratings using histograms and bar plots.
* Compare average ratings across cuisines and cities.
* Explore relationships between features such as Votes, Price range, and Aggregate rating.
* Use scatterplots, boxplots, and correlation heatmaps to gain insights.

📊 Tools & Libraries
* Pandas – data manipulation
* NumPy – numerical computations
* Matplotlib & Seaborn – data visualization
* Scikit-learn – predictive modeling and evaluation

🎯 Key Insights
* Certain cuisines consistently receive higher ratings and are popular among customers.
* Votes and Price range can influence customer perception and rating.
* Predictive models can help estimate restaurant ratings based on key features.
* Visualization aids in identifying trends and relationships across cities and cuisines.
