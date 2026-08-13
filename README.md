# Mitchell Aldridge Data Science Portfolio

## About Me
I am a recent graduate of the University of Wisconsin - Green Bay's Masters of Data Science program. I am currently an intern at TruStage on their B2B Sales Analytics team.

# [Project 1: Employee Attrition Prediction & Workforce Segmentation](https://github.com/mitchellaldridge/Capstone_Project/tree/main)

This project developed and evaluated machine learning models to predict employee attrition and explored whether workforce segmentation could improve predictive performance.

* Built an end-to-end machine learning workflow in Python using Pandas, scikit-learn, XGBoost, and imbalanced-learn
* Performed EDA, feature engineering, data cleaning, encoding, scaling, and class-imbalance handling on ~850,000 employee records
* Compared Logistic Regression, Random Forest, and XGBoost models using precision, recall, F1 score, and ROC-AUC
* Tuned Random Forest and XGBoost with RandomizedSearchCV and 5-fold cross-validation
* Improved XGBoost recall from 66.0% to 91.0% through classification-threshold optimization
* Used feature importance to identify stress, burnout, satisfaction, sentiment, and workload as key predictive factors
* Applied K-Means clustering and PCA to segment employees and evaluate whether segmentation improved predictive performance

# [Project 2: Northwind SQL Business Analysis](https://github.com/mitchellaldridge/northwind-sql-analysis)

This project analyzes business performance using the Northwind database to answer real-world sales, customer, product, and employee performance questions using PostgreSQL.

* The analysis is performed in PostgreSQL using complex SQL queries and analytical techniques
* Built multi-table joins across customers, orders, products, categories, and employees to analyze business operations
* Used Common Table Expressions (CTEs) to structure complex analytical queries
* Applied window functions such as `DENSE_RANK()` and `LAG()` to analyze ranking changes and revenue trends
* Performed customer analysis to identify high-value customers and revenue concentration
* Evaluated product performance by ranking products within categories and tracking top performers over time


# [Project 3: House Sale Price Predictions](https://github.com/mitchellaldridge/House-Sale-Price-Prediction)

This is a project done through kaggle for one of their machine learning competitions where the goal is to predict house sale prices.

* The analysis is done in Python using libraries such as Pandas, Numpy and Scikit-Learn
* Performed EDA and Data Cleaning to prepare the data set for model training
* Used a Pipeline to impute missing data
* Gets best score from many different regression techniques such as XGBoost, Lasso, Random Forest
* Selects best models from baseline search and preforms hyperparameter tuning for model improvement


# [Project 4: Predicting E-commerce Customer Reviews](https://github.com/mitchellaldridge/Predicting-Ecommerce-Customer-Reviews)

This project was done as a final project in my masters level machine learning course to predict customer reviews for an ecommerce website.

* The analysis is done in R using libraries such as Tidyverse and Caret
* Performed EDA and Data cleaning to prepare the data set for model training
* Uses Double Cross Validation to select the best honest prediction of the best model between Linear Regression and Random Forest
* Includes variable importance visualizations
* Includes a final report detailing every part of the machine learning process


# [Project 5: Life Expectancy Trends from Healthcare Spending in Tableau](https://github.com/mitchellaldridge/Tableau-Dashboard-Healthcare)

This project was done to showcase how government spending on healthcare affects life expectancy globally

* Performed EDA and Data Cleaning in R
* Found future trends using linear regression
* Created an interactive dashboard in Tableau to allow users hands on visualizations
* The dashboard allows users to view different countries and regions and the differences in life expectancy and healthcare spending
