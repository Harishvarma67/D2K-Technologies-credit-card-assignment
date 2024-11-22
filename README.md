# Credit card customer analysis

Name : Harish Addada

## About Dataset

- A manager at the bank is disturbed with more and more customers leaving their credit card services. 
- They would really appreciate if one could predict for them who is gonna get churned so they can proactively go to the customer to provide them better services and turn customers' decisions in the opposite direction

- Now, this dataset consists of 10,000 customers mentioning their age, salary, marital_status, credit card limit, credit card category, etc. There are nearly 18 features.

- We have only 16.07% of customers who have churned. Thus, it's a bit difficult to train our model to predict churning customers.

### Part 1: Data Exploration and Preprocessing

- Data Understanding: Load the dataset and perform an initial exploration to understand its structure, identify missing values, and gather basic statistics.
- Preprocessing: Clean the dataset by handling missing values, outliers, and any erroneous data points. Document your decisions.

### Part 2: Data Analysis and Visualization

- Customer Demographics Analysis: Analyze the demographics of the credit card holders (e.g., age, salary, marital status) and visualize the distributions.
- Credit Usage Analysis: Explore how different demographics correlate with credit card limit, balance, and category. Identify any interesting patterns.

### Part 3: Customer Segmentation

- Segmentation Model: Use clustering techniques (e.g., K-Means) to segment the customers based on their credit card usage and demographic data. Determine the optimal number of clusters.
- Segment Analysis: Analyze each customer segment to identify unique behaviors and characteristics. Provide actionable insights for targeted marketing strategies.

### Part 4: Predictive Modeling

- Churn Prediction: Build a predictive model to forecast customer churn based on the features available in the dataset. Experiment with at least two different algorithms and compare their performance.
- Model Evaluation: Assess the models using appropriate performance metrics. Discuss the strengths and weaknesses of each model.

### conclusion

- After the above steps i trained and tested my data with 2 models Logistic regression and xgbclassifier
- I got high accuracy score from xgbclassifier which is 0.96.
