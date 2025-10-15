Level 1 – Data Exploration, Descriptive & Geospatial Analysis

 Dataset
The dataset contains information about restaurants, including attributes such as Restaurant Name, Country Code, City, Cuisines, Aggregate Rating, and other related details.

Task 1: Data Exploration and Preprocessing

Objective:
Explore and clean the dataset before performing analysis.

Steps Performed:
* Loaded the dataset using Pandas.
* Identified the number of rows and columns in the dataset.
* Checked for missing values in each column and handled them (using mean/mode fill or by removing rows).
* Verified and converted data types where necessary (e.g., converting ratings to numeric).
* Analyzed the distribution of the target variable – “Aggregate Rating” to identify class imbalance.
* Visualized the distribution using histograms and count plots with Seaborn.

Outcome:
* Clean and ready-to-analyze dataset.
* Understood data quality and missing value patterns.
* Verified the balance of the target variable.

  Task 2: Descriptive Analysis

Objective:
Generate statistical insights and explore categorical data patterns.

Steps Performed:
* Calculated basic statistics (mean, median, standard deviation, min, max) for all numerical columns using describe().
* Explored the distribution of categorical variables such as Country Code, City, and Cuisines.
* Identified the top cuisines and top cities with the highest number of restaurants.
* Created bar plots using Matplotlib and Seaborn to visualize the results.

Outcome:

* Summary of numeric trends and category distributions.
* Found the most common cuisines and restaurant locations.
* Identified key countries and cities contributing to the dataset.

Task 3: Geospatial Analysis

Objective:
Analyze restaurant locations geographically and explore their spatial relationship with ratings.

Steps Performed:
* Verified and used the latitude and longitude columns for mapping.
* Plotted restaurant locations on an interactive map using Folium.
* Visualized the distribution of restaurants across different cities and countries using bar charts.
* Checked for possible correlation between geographic coordinates and ratings using Pearson correlation.
* Displayed scatter plots for latitude vs rating and longitude vs rating.

Outcome:
* Interactive geographical visualization of restaurants.
* Insights into which cities/countries have the highest restaurant density.
* Understood spatial patterns and their relationship with customer ratings.

Tools & Libraries Used

* Python
* Pandas – data handling
* NumPy – numerical operations
* Matplotlib / Seaborn – visualizations
* Folium – geospatial mapping
  
