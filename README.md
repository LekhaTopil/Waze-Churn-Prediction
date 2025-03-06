# **Waze User Churn Prediction**

## 🚀 **EDA | Logistic Regression | Random Forest | XGBoost**

## **Waze**

Waze, a free navigation app owned by Google, makes it easier for drivers around the world to reach their destinations. Waze's community of map editors, beta testers, translators, partners, and users helps make each drive better and safer.

## **Project Goal**

The objective of this project is to develop a machine-learning model capable of predicting user churn. A well-performing model would help reduce churn, improve user retention, and drive Waze’s business growth.

## **Project Details**

**This project was divided into four key phases:**

✔ **Exploratory Data Analysis (EDA)**

✔ **Hypothesis Testing**

✔ **Logistic Regression** 

✔ **Advanced Machine Learning (Random Forest & XGBoost)**

Each phase played a crucial role in understanding churn dynamics and evaluating predictive modeling approaches.

## **1. Exploratory Data Analysis**

The project began with an in-depth Exploratory Data Analysis, where I:

•	Examined missing values to assess patterns and randomness. 

•	Analyzed data distributions to detect skewness.

•	Engineered new features to better capture churn-related behaviors.

•	Handled outliers using percentile-based thresholds to maintain data integrity and realistic expectations.

## **2. Hypothesis Testing**

To gain deeper insights into user behavior, I performed **statistical hypothesis testing**, including:

 •	A **two-sample T-test** to compare ride amounts between iPhone and Android users.

 •	Additional hypothesis tests on various factors to identify key churn-related patterns.

 •	A **Chi-squared Test of Independence** to explore relationships between categorical variables, particularly user-device interactions.

## **3. Logistic Regression Model**

Next, I built a **Logistic Regression Model** to predict churn:

•	Validated assumptions and optimized parameters.

•	Evaluated model performance using key classification metrics.

## **4. Advanced Machine Learning: Random Forest & XGBoost**

To enhance predictive accuracy, I implemented **Random Forest** and **XGBoost**:

•	Used **GridSearchCV** to fine-tune hyperparameters.

•	Assessed feature importance to understand which factors influenced churn.

•	Compared performance with the Logistic Regression model.

To ensure model robustness, I employed a **three-way data split**  (train, validation, test), which helped fine-tune hyperparameters and evaluate generalizability.

## **Conclusion**

While both Logistic Regression and tree-based models (Random Forest & XGBoost) did not yield strong predictive performance, this analysis provided valuable insights into user behavior. The dataset lacked sufficient explanatory power, suggesting that additional relevant features and richer data sources are needed to improve churn prediction. Future work can focus on integrating external data, behavioral patterns, or more granular user engagement metrics to enhance predictive performance.

This project demonstrates the importance of **feature selection, statistical validation, and iterative modeling** in understanding user churn and shaping data-driven retention strategies.












