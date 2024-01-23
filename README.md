# Telecom-Churn-Prediction
# Predictive Churn Analysis for Telecom Services Using Machine Learning

The project focuses on creating a predictive model to tell which customers are likely to keep of discontinue their telecom operator's services. This entails initial analysis of datasets covering contracts, personal, and internet/phone service usage details. A thorough exploratory data analysis will uncover trends and guide feature engineering. Emphasis will be on one-hot encoding for categorical variables and devising new features that reflect customer behavior.

Using boosting algorithms, the project aims to leverage capacity for binary classification and to fine-tune the predictive model through hyperparameter optimization. The primary performance metric, the AUC-ROC score, will gauge the model's success in finding potential churn from loyal customers, and should result in 0.88 or above.

The project aims to equip the telecom operatoring company with the ability to find those likely to churn and proactively send targeted promotions and customer retention plan options.

## Interconnect's services
Interconnect mainly provides two types of services:
1. Landline communication. The telephone can be connected to several lines simultaneously.
2. Internet. The network can be set up via a telephone line (DSL, digital subscriber line) or through a fiber optic cable.

Some other services the company provides include:
- Internet security: antivirus software (DeviceProtection) and a malicious website blocker (OnlineSecurity)
- A dedicated technical support line (TechSupport)
- Cloud file storage and data backup (OnlineBackup)
- TV streaming (StreamingTV) and a movie directory (StreamingMovies)

The clients can choose either a monthly payment or sign a 1- or 2-year contract. They can use various payment methods and receive an electronic invoice after a transaction.

The data consists of files obtained from different sources:
- contract.csv — contract information
- personal.csv — the client's personal data
- internet.csv — information about Internet services
- phone.csv — information about telephone services
In each file, the column customerID contains a unique code assigned to each client.

![Image1](plots/subplot.png)

The combination of these plots provides a comprehensive view of how monthly charges are distributed among customers. The presence of a large number of customers at the lower end of the spectrum could indicate a base tier of services, while the multiple peaks observed in the KDE and violin plots suggest the existence of several pricing tiers or bundled services.

The box plot's median value is close to the higher end of the lower IQR, indicating that more than 25% of customers pay above the median monthly charge. The outliers in the box plot could be customers with premium services or multiple add-ons.

The cumulative density plot's smooth curve indicates no abrupt changes in the billing structure, which would be seen as steep slopes in such a plot.
