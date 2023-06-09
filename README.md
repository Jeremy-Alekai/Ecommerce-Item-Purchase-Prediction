# Ecommerce-Item-Purchase-Prediction

Source: https://archive.ics.uci.edu/ml/datasets/Online+Shoppers+Purchasing+Intention+Dataset


# Introduction
This dataset contains the online shoppers' behaviors and intentions from a leading Brazilian e-commerce company. The dataset consists of 12,330 online sessions from their website. The dataset includes 10 numerical and 8 categorical attributes.

The goal is to predict if a visitor will make a purchase (revenue) during a session based on their actions on the website.

Dataset Information
1. Administrative: Number of pages of this type (administrative) that the user visited.
2. Administrative_Duration: Total amount of time spent on pages of this type.
3. Informational: Number of pages of this type (informational) that the user visited.
4. Informational_Duration: Total amount of time spent on pages of this type.
5. ProductRelated: Total number of product-related pages visited by the visitor.
6. ProductRelated_Duration: Total amount of time spent on product-related pages.
7. BounceRates: Average bounce rate (percentage of visitors who enter the site and then leave rather than continuing to view other pages within the same site) of the pages visited by the visitor.
8. ExitRates: Average exit rate (the percentage of pageviews on the website that were the last in the session) of the pages visited by the visitor.
9. PageValues: Average page value of the pages visited by the visitor.
10. SpecialDay: Closeness of the site visiting time to a special day (e.g. Mother’s Day, Valentine’s Day) in which the session occurred.
11. Month: Month of the year in which the session occurred.
12. OperatingSystems: Operating system used by the visitor.
13. Browser: Browser used by the visitor.
14. Region: Geographic region from which the session originated.
15. TrafficType: Traffic source by which the visitor has arrived at the website (e.g. banner, SMS, direct).
16. VisitorType: Visitor type as ‘New Visitor’ ‘Returning Visitor’ and ‘Other’.
17. Weekend: Boolean value indicating whether the date of the session is weekend.
18. Revenue: Class label indicating whether the visit has generated revenue (1) or not (0).


# Business Problem:

The e-commerce industry is growing rapidly and competition among businesses is increasing. One of the challenges businesses face is predicting which customers are likely to make a purchase, and which are not. This is where machine learning comes in handy, by building models that can help businesses to identify potential customers and target them with personalized marketing messages.

This project aims to predict online shoppers' purchase behavior using machine learning. The dataset used is sourced from the UCI Machine Learning Repository, and contains various features such as the type of product, whether the user is a returning visitor, the time of day and week, the duration of the session, and various page views and interactions.


# Data:

The data used in this project was sourced from Kaggle (https://www.kaggle.com/carrie1/ecommerce-data). The data includes information about customer purchases from an online store. The dataset consists of 17 variables/columns: Administrative,	Administrative_Duration,	Informational,	Informational_Duration,	ProductRelated, ProductRelated_Duration,	BounceRates,	ExitRates,	PageValues,	SpecialDay,	Month,	OperatingSystems,	Browser,	Region,	TrafficType,	VisitorType and	Weekend	Revenue. The dataset has over 500,000 rows of data and 8 features.


# Data Cleaning and Exploration

During the data cleaning process, missing values, inconsistent data formats, and outliers were addressed. Categorical features were appropriately encoded for modeling purposes.

Exploratory data analysis (EDA) was performed to better understand the relationships between features and the target variable. This involved analyzing distributions of individual features, correlations between features, and how they relate to the target variable.


![image](https://user-images.githubusercontent.com/57034956/232239128-cead82be-872e-4bd6-bf39-27b728b5a3f2.png)

85% of customers return back to site, which is a good indication. Meaning that customers are satisfied with what they are getting. 13.74% of customers are new customers

![image](https://user-images.githubusercontent.com/57034956/232239180-cdb7612f-568d-488e-9725-5d98626f3e72.png)
Less people visit this site during weekdays than weekends

![image](https://user-images.githubusercontent.com/57034956/232239260-bb3f42bb-3c9c-44ac-8c33-667e87b80f9e.png)
The returning visitors seem to make more purchases that new visitors

![image](https://user-images.githubusercontent.com/57034956/232239428-85b3b0f2-b478-410f-b6f3-be99f7451d31.png)


# Modeling

Various classification models were trained and evaluated, including Logistic Regression, Decision Trees, Random Forests, and Gradient Boosting. The models were trained and evaluated using cross-validation techniques to ensure robustness of the results.

# Evaluation

The performance of the various models was evaluated using standard classification metrics such as accuracy, precision, recall, and F1-score. The best performing model was selected based on these metrics and further analyzed.

Results:

Our model had an F1 score of 0.90, which is a good performance. This means that our model is able to predict with good accuracy which customers are likely to make a purchase, and which are not. By identifying potential customers, businesses can focus their marketing efforts on these customers, and improve their chances of making a sale.

Recommendations:

We recommend that businesses use this model to predict which customers are likely to make a purchase. By targeting these customers with personalized marketing messages, businesses can improve their chances of making a sale, and increase their revenue.
