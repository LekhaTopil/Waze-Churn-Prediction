# **Waze-Churn-Prediction**

# **Waze**
Waze, a free navigation app owned by Google, makes it easier for drivers around the world to reach their destinations. Waze's community of map editors, beta testers, translators, partners, and users helps make each drive better and safer.

### **Churn V/s Retained:**
Churn quantifies users who have uninstalled the app and no longer use the Waze app. Retained users are those who are still using the app and have not uninstalled it.

# **Project Goal:**
Develop a machine learning model to predict user churn. An accurate model will help prevent churn, improve user retention, and contribute to the growth of Waze's business. 

# **Project Details**
Throughout the **Waze project**, we embarked on a comprehensive exploration of user **churn dynamics**, aiming to develop a robust predictive model to enhance user retention and contribute to business growth. 

## **Exploratory Data Analysis**
Our journey began with an in-depth **Exploratory Data Analysis (EDA)**, where we meticulously scrutinized missing values to discern their randomness and evaluated data distributions to uncover inherent skewness. We delved into feature engineering, crafting new predictors to illuminate the factors influencing user churn and identify pivotal variables for our predictive model. Additionally, we addressed outliers, applying tailored percentile thresholds to ensure data integrity.

## **Hypothesis Testing**
Following EDA, we conducted a pivotal **two-sample T-test**, scrutinizing ride amounts between **iPhone** and **Android** users to unveil nuanced insights into user behavior. This exploration prompted further hypothesis testing across various variables, enriching our understanding of user engagement and behavior patterns. Subsequently, we employed a **Chi-squared test of independence** to ascertain significant associations between categorical variables, enriching our comprehension of user-device interactions.

## **Building Model**
Transitioning to model development, we constructed a **Logistic Regression** framework tailored for churn prediction. Adhering to best practices, we validated assumptions, honed model parameters, and meticulously evaluated performance metrics. Expanding our predictive arsenal, we explored sophisticated **tree-based methods** including **Random Forest** and **XGBoost**, leveraging **GridSearchCV** for optimal parameter tuning.

A cornerstone of our approach was a strategic **three-way data split**, optimizing model selection on a dedicated validation set to isolate the champion model for rigorous testing on the untouched test dataset. This meticulous methodology provided a robust estimate of model performance and ensured generalizability for future scenarios.

# **Conclusion**
Our Waze project encapsulated a holistic data science journey, blending rigorous analysis with advanced modeling techniques to drive actionable insights and fortify user retention strategies. This experience underscores our commitment to leveraging data-driven approaches to empower business growth and enhance user experience.






