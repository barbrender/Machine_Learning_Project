I used interactive charts in my project in order to see it properly please use this link:
https://nbviewer.org/github/barbrender/Machine_Learning_Project/blob/main/Machine_Learning_Project.ipynb

# Model Fitness - Machine Learning Project
Customer retention strategy based on analytical data

## Description:
Model Fitness, a leading gym chain, is developing a data-driven customer interaction strategy to address the issue of customer churn. By identifying unique churn indicators for the fitness industry, the project aims to detect and address potential customer attrition more effectively. This will involve analyzing gym attendance patterns, such as a month-long absence, to determine if a customer is likely to discontinue their membership and implementing targeted engagement strategies to improve retention rates.

## Project goal:
To analyze customer profiles and come up with a customer retention strategy.

## Methodology:
### Prepearing the data:
1. Cheking the overview data.
2. Checking the data for missing values, duplicates and outliers.
3. Check if data types are right.
4. Data preprosscing and calculcation.

### The research:
1. Churn Prediction: Utilize machine learning algorithms to analyze historical customer data and predict the probability of churn for each customer in the upcoming month.
2. Customer Segmentation: Perform a cluster analysis to identify the most prominent customer groups and describe their key characteristics, creating distinct user portraits.
3. Churn Factor Analysis: Conduct a feature importance analysis to determine the factors that have the most significant impact on customer churn.
4. Recommendations and Improvement Strategies:
- Identify Target Groups: Based on the user portraits and churn factor analysis, pinpoint the customer segments most at risk of churning.
- Churn Reduction Measures: Propose data-driven strategies tailored to each target group to address the identified churn factors and improve customer retention.
- Additional Patterns: Analyze any other emerging patterns in customer interactions to further enhance the customer experience and foster long-term loyalty.

## Libraries:
- pandas
- numpy
- seaborn
- matplotlib.pyplot
- plotly.express
- stats from spicy
- math

- StandardScaler, LabelEncoder from sklearn.preprocessing
- train_test_split from sklearn.model_selection 
- LogisticRegression from sklearn.linear_model 
- DecisionTreeRegressor, DecisionTreeClassifier from sklearn.tree 
- RandomForestRegressor, RandomForestClassifier from sklearn.ensemble 
- mean_absolute_error, mean_squared_error, r2_score, confusion_matrix, accuracy_score, precision_score, recall_score, f1_score, roc_auc_score, silhouette_score from sklearn.metrics
- KMeans from sklearn.cluster 
- dendrogram, linkage from scipy.cluster.hierarchy
