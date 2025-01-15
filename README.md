# Real Estate Analysis: Alameda County Housing Market
**Project Overview**

This project dives into the real estate trends in Alameda County, focusing on factors like property types, pricing trends, and neighborhood clusters. Using data scraped from the MLS (Multiple Listing Service), we conducted comprehensive data analysis and modeling to uncover insights and predict housing prices.

**Introduction**

The housing market in Alameda County features a diverse range of property types and pricing trends. This project leverages machine learning and statistical analysis to explore these factors and provide actionable insights for potential buyers, sellers, and investors.


**Data Source**

The data for this project was collected from the Multiple Listing Service (MLS), which aggregates property listings. After collection, the data underwent rigorous preprocessing to ensure accuracy and usability.

**Methodology**


Data Collection: Web scraping to gather real estate data.
Data Preprocessing:
Dropped rows with null values.
Converted data types for analysis.
Extracted and normalized location data (Address, City, Zip Code).
Removed currency symbols for price fields.
Exploratory Data Analysis:
Visualized trends and distributions.
Analyzed correlations and significant features.
Modeling:
Implemented linear regression, multiple regression, and clustering models.
Evaluated model performance using RMSE and prediction accuracy.

**Research Questions**


What property types are prevalent in Alameda County?
What are the recent trends in selling prices across different property types and neighborhoods?
How do property prices differ based on factors like property type, size, and the number of bedrooms and bathrooms?
What is the average mortgage amount in Alameda County?
Can we predict house prices using features like size, bedrooms, and HOA fees?
How can clustering analysis assist in identifying unique neighborhood clusters?

**Findings**


Property Trends:
Single-family homes dominate in price and volume.
Fremont leads in townhouses, and Dublin in condos.
Price Distribution:
75% of homes are priced below $2 million.
Piedmont shows the greatest price fluctuations.
Neighborhood Clusters:
Cluster 0: Affordable townhouses in Hayward, Union City, Newark.
Cluster 1: Vintage family homes in Berkeley, Livermore, Oakland.
Cluster 2: Balanced housing options in Fremont.
Cluster 3: Luxury homes in Pleasanton.

**Models and Results**


Linear Regression:
Independent Variable: Square footage.
Dependent Variable: Price.
Observations: Strong positive correlation; larger homes have higher prices.
Multiple Regression:
Features: Beds, Baths, Square Footage, HOA Fees.
RMSE: 170.39.
Predictions: Range $591K to $859K.
Clustering:
Neighborhood categorization using k-means.
Identified four distinct clusters based on price, property type, and HOA fees.
Technologies Used

Python: Data preprocessing, analysis, and modeling.
Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Statsmodels.
Tools: Jupyter Notebook.
