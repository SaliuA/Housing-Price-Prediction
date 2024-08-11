# House Price Prediction
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
 
# Introduction:
The real estate market is complex and dynamic, with numerous factors influencing the prices of homes. Understanding these factors and accurately predicting house prices is crucial for buyers, sellers, real estate agents, and investors. Our House Price Prediction Model is designed to provide reliable price estimates for homes based on a comprehensive set of features.

### Problem Statement:
Accurately predicting house prices is a critical challenge in the real estate market, influenced by a multitude of factors including dwelling types, zoning classifications, lot features, property conditions, and sale conditions. Traditional methods of property valuation often rely on limited data and subjective assessments, leading to inconsistencies and inaccuracies. This creates uncertainty for various stakeholders such as home buyers, sellers, real estate agents, and investors, potentially resulting in financial losses and inefficient market operations.


### Objective:
To address these challenges, our goal is to develop a robust House Price Prediction Model that leverages advanced machine learning techniques to analyze a comprehensive set of property features and market data with an accuracy target of 85%. This model aims to provide accurate, data-driven price predictions that can be used by various stakeholders to make informed decisions in the real estate market.


### In this notebook, we aim to answer several Key Questions for Gaining Insights into House prices:

#### General Questions

1. **What is the distribution of house prices?**
   - Understanding the overall spread, central tendency, and any outliers in house prices.

#### Location and Proximity

2. **How does the physical location (Neighborhood) within the city and Zoning influence house prices?**
   - Comparing house prices across different neighborhoods to identify high and low-value areas.

   - Investigating the relationship between different zoning classifications (e.g., residential, commercial) and house prices.

4. **How do proximity features (Condition1, Condition2) affect house prices?**
   - Determining how proximity to various conditions (e.g., arterial streets, railroads, parks) impacts house prices.

#### Feature-Specific Questions

5. **What is the impact of dwelling type (MSSubClass) on house prices?**
   - Analyzing how different types of dwellings (e.g., 1-story, 2-story, duplex) affect house prices.

6. **How does the condition and quality of the house (OverallCond) impact house prices?**
   - Assessing how the overall quality and condition ratings of a house influence its price.

7. **How do different Foundation type relate to house prices?**
    - Examining how foundation types affect house prices.

8. **What is the impact of basement features (e.g., TotalBsmtSF, BsmtQual, BsmtCond) on house prices?**
    - Analyzing how basement size, quality, and condition correlate with house prices.

9. **How do living area features (e.g., GrLivArea) influence house prices?**
    - Investigating the relationship between the total living area and house prices.

10. **How do amenities such as garages (GarageType) impact house prices?**
    - Determining the value added by amenities like  garages.

#### Sale type and Sale Conditions

11. **How do sale type (SaleType) and sale condition (SaleCondition) affect house prices?**
    - Analyzing the influence of different sale types (e.g., warranty deed, cash sale) and sale conditions on house prices.

### Time specific Questions
12. **What is the effect of the year built (YearBuilt) and year remodeled (YearRemodAdd) on house prices?**
   - Analyzing whether newer houses fetch higher prices.

13. **What is the impact of the time of sale (MoSold) on house prices?**
    - Investigating seasonal trends and changes in house prices over time.


By answering these questions through visualizations and statistical analyses during the EDA, i can uncover important insights and relationships that will help inform the house price prediction model.


### Data Sources:

The Ames Housing dataset was compiled by Dean De Cock for use in data science education. It's an incredible alternative for data scientists looking for a modernized and expanded version of the often cited Boston Housing dataset.

* <a href="https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview" target="_blank">
    <img src="https://img.shields.io/badge/Kaggle-035a7d?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle">
 </a>


### This project also serves as a capstone project for the Data Science Diploma at AltSchool.
* [Alt school Data science](https://altschoolafrica.com/)

### GitHub Project Repository :
* [House Price Prediction](https://github.com/SaliuA/Housing-Price-Prediction)

### Summary :
I applied Linear Regression, Random Forest Regressor, and XGBoost models to the dataset. Among these, XGBoost achieved the lowest RMSE of $23,000 and the highest R-squared of 0.91.

### Built With

```
pandas
seaborn
matplotlib
sklearn
```
