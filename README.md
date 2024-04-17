# **Waze-Churn-Prediction**

# **Waze**
Waze, a free navigation app owned by Google, makes it easier for drivers around the world to reach their destinations. Waze's community of map editors, beta testers, translators, partners, and users helps make each drive better and safer.

### **Churn V/s Retained:**
Churn quantifies users who have uninstalled the app and no longer use the Waze app. Retained users are those who are still using the app and have not uninstalled it.

# **Project Goal**
The objective of this project was to develop a machine-learning model capable of **predicting user churn**. A successful model would not only aid in reducing churn but also contribute to improving user retention and advancing Waze's business growth.

# **Project Details**
Throughout the **Waze project**, I conducted an extensive exploration of user churn dynamics, aiming to develop a robust predictive model to enhance user retention and drive business growth.

## **Exploratory Data Analysis**
The project commenced with an in-depth **Exploratory Data Analysis (EDA)**, where I meticulously scrutinized missing values to discern their randomness and evaluated data distributions to uncover inherent skewness. I delved into feature engineering, crafting new predictors to illuminate the factors influencing user churn and identify pivotal variables for our predictive model. Additionally, I addressed outliers by setting tailored percentile thresholds, ensuring data integrity and realistic expectations.

## **Hypothesis Testing**
Following **EDA**, I conducted a pivotal **two-sample T-test**, scrutinizing ride amounts between **iPhone** and **Android** users to unveil nuanced insights into user behavior. This exploration prompted further hypothesis testing across various variables, enriching our understanding of user engagement and behavior patterns. Subsequently, I employed a **Chi-squared Test of Independence** to ascertain significant associations between categorical variables, enriching our comprehension of user-device interactions.

## **Building Model**
Transitioning to model development, I constructed a **Logistic Regression** framework tailored for churn prediction. Adhering to best practices, I validated assumptions, optimized model parameters, and meticulously evaluated performance metrics. Expanding our predictive arsenal, I explored sophisticated **tree-based methods** including **Random Forest** and **XGBoost**, leveraging **GridSearchCV** for optimal parameter tuning.

A cornerstone of my approach was **a strategic three-way data split**, which involved dividing the dataset into three subsets: **training, validation, and testing**. The training set was used to train the model, the validation set helped tune hyperparameters and select the best model, and the test set evaluated the model’s performance on unseen data. This meticulous methodology provided a robust estimate of model performance and ensured generalizability for future scenarios.

# **Conclusion**
The Waze project encapsulated a holistic data science journey, blending rigorous analysis with advanced modeling techniques to drive actionable insights and fortify user retention strategies. This experience underscores the commitment to leveraging data-driven approaches to empower business growth and enhance user experience.






