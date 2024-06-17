# Machine Learning #

## Machine Learning Techniques ##
- Supervised ML
- Unsupervised ML
- Reinforcement Learning

### Supervised ML Technique ###
- We have dataset with dependent(output) and independent variables(input).
- We train the model using data and then make predictions using trained model.
- E.g. we have a dataset with No. of rooms(independent variable) in house vs house price(dependent variable).
- Theere are 2 types of problem statement in Supervised ML technique:
    1) **Regression** problem statement
        - The dependent variable is continous.
        - E.g. the house price example above.
    2) **Classification** problem statement
        - The dependent variable is categorical.
        - E.g a data with no. of study hours(input) and pass or fail(output).
        - In this example we have only two category in output(pass or fail). Thus, called *Binary Classification*
        - If ther is multiple category like(pass or fail or maybe) then it is calles *MultiClass Classification*
- ALGORITHMS:
    - Linear Regression (Regression)
    - Ridge & Lasso (Regression)
    - ElasticNet (Regression)
    - Logistic Regression (Classification)
    - Decision Tree (Both Regression and Classification)
    - Random Forest (Both Regression and Classification)
    - AdaBoost (Both Regression and Classification)
    - Xgboost (Both Regression and Classification)

### Unsupervised ML Technique ###
- We don't know the output feature.
- We don't need to predict anything. Instead, we need to find out similar clusters or groups.
- E.g. Customer Segmentation - we have a data of salary of people and their spending score, then we create differnt clusters of people like high salary low spending people, high salary high spending people etc. And e-commerce website have to send a email with discount coupon it will share it with a specific cluster of people.
- ALGORITHMS:
    - K Means
    - Hierarichal Mean
    - DB Scan clusteirng

### Reinforcement Learning ###
- Learns itself.
