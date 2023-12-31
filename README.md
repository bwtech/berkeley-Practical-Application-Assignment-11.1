# berkeley-Practical-Application-Assignment-11.1
Practical Application Assignment 11.1: What Drives the Price of a Car?

Used Car Price Prediction Analysis Report
=========================================

Executive Summary
-----------------

This report presents the findings from a comprehensive data analysis aimed at understanding the key factors influencing used car prices. Utilizing advanced data analysis techniques, including Linear Regression and Random Forest Regression models, our goal was to identify attributes that significantly impact the value of used cars. This information is intended to assist used car dealerships in optimizing their inventory and pricing strategies.

[The Project Notebook](prompt_II.ipynb)

Data Overview
-------------

The analysis was conducted on a dataset comprising various attributes of used cars, such as make, model, year, odometer reading, fuel type, and more. Prior to modeling, the data underwent preprocessing, including normalization of numeric features and one-hot encoding of categorical variables.

Key Findings
------------

### 1\. **Influential Factors on Car Prices**

-   Year of Manufacture: The 'year' of the car emerged as the most significant predictor of its price. Newer models tend to fetch higher prices.
-   Mileage: The 'odometer' reading significantly impacts the price, with higher mileage correlating with lower prices.
-   Fuel Type and Car Type: Specific categories like 'diesel', 'pickup', and 'sedan' were notable influencers, suggesting preferences for certain fuel types and car models.

### 2\. **Model Performance**

-   Random Forest Regressor (100 Estimators): This model exhibited a good balance between learning from the training data and generalizing to new data, with a Training RMSE of 0.1656 and a Test RMSE of 0.4445. The R² value of 0.8027 indicates a robust predictive capability.
-   Linear Regression: Provided moderate predictive accuracy with an R² of 0.6269. This model's simplicity offers interpretability, beneficial for understanding direct relationships between features and prices.

### 3\. **Recommendations for Inventory Management**

-   Focus on Newer Models: Given the strong influence of the car's year, stocking newer models could be more profitable.
-   Diverse Range in Mileage: While lower mileage cars are valued higher, there is a market for higher mileage cars, suggesting a diverse range in odometer readings may appeal to a broader customer base.
-   Special Attention to Diesel and Pickups: The preference for diesel vehicles and pickups should be considered when selecting inventory.

Conclusion
----------

The analysis provides valuable insights into the factors that significantly influence used car prices. By aligning inventory with these findings, used car dealerships can enhance their ability to meet market demand and optimize pricing strategies. It's recommended to continue leveraging data-driven approaches for inventory management to stay competitive in the dynamic used car market.
