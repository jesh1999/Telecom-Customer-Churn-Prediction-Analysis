#  **📊 Telecom Customer Churn Prediction🔑 📈**
The aim of the Telecom Customer Churn Prediction project is to develop a predictive model to identify customers at risk of leaving, enabling targeted retention efforts and reducing churn rates. This enhances customer loyalty and improves overall business performance in a competitive market. 🌟

**📚Overview**
Customer churn is a critical metric in the telecommunications industry. This analysis aims to predict customer churn using machine learning techniques. 📈
**1.🔑Churn Distribution:🎯**
![image](https://github.com/user-attachments/assets/16e097e7-0157-4cd6-8da0-003ae65d351b)

**Output**
You should see a bar chart displaying two bars:
1.One for customers who have churned (usually labeled as "Yes" or "1").
2.One for customers who have not churned (usually labeled as "No" or "0").
This visualization will provide a clear overview of your customer churn situation.

**2.🔮Churn distribution with respect to gender:📈**

output will be a grouped bar chart displaying:

![image](https://github.com/user-attachments/assets/b5da748c-22d8-4488-88f6-76daa0c705cc)

1.The number of male and female customers who have churned.
2.The number of male and female customers who have not churned.

**3.👤Customer Contract distribution:📜**

![image](https://github.com/user-attachments/assets/4e75e0e8-9217-4ece-9955-cd22d33492ef)

This will allow you to see which contract types are most common among your customers.
**4.Payment Methods:📝**
![image](https://github.com/user-attachments/assets/a21dad03-8b53-48ee-82e6-b41e4761870d)


The output will be a bar chart displaying the number of customers for each payment method. This visualization will help you understand which payment methods are most popular among your customers.

**5.Internet services:📚**

![image](https://github.com/user-attachments/assets/9bb56d9a-6ef4-486e-a81b-8ed1e722d6ea)

The output will be a bar chart displaying the number of customers for each type of internet service. This visualization will provide insights into the preferences of your customers regarding internet services.

**6.Dependent distribution:🏷️**
![image](https://github.com/user-attachments/assets/5bd699ef-cdf3-4c8c-9fca-fbb40b08dfd8)

This visualization provides insights into the demographic characteristics of your customers, which can be valuable for understanding customer behavior and potential churn.
**7.Online Security:🚪**
![image](https://github.com/user-attachments/assets/32a29f5b-7bae-4738-ab87-44781a960449)

This visualization will provide insights into how many customers value online security services and can help correlate this information with churn rates. 
**8.Senior Citizen:📊**

![image](https://github.com/user-attachments/assets/14e8bbec-9bb6-433b-82eb-9dd65e65c1e5)
This visualization provides insights into the age demographics of your customers, which can be important for understanding customer needs and potential churn patterns.
**9. Paperless Billing:🔄**
![image](https://github.com/user-attachments/assets/e65420bd-fbcf-4ed9-b483-d9598d2741b3)

This visualization can help you understand customer preferences for billing and may provide insights into their behavior regarding churn.
**10.Tech support:📉**
![image](https://github.com/user-attachments/assets/0462391c-2bfa-41ad-9b4c-b798eb954e08)


This visualization will provide insights into how much customers value tech support services and can help identify any potential correlations with customer retention and churn.
**11.Distribution w.r.t Charges and Tenure:🔍**
![image](https://github.com/user-attachments/assets/e5ee24c6-8d4a-4a25-ab08-2e366b7d7b06)
![image](https://github.com/user-attachments/assets/bb81d353-9e2d-4bf2-b1cc-850ac95717ee)

**🌟🛠️Machine Learning Model Evaluations and Predictions:🎯**

Accuracy: 0.79
ROC AUC: 0.84
Confusion Matrix:
[[942  94]
 [203 170]]
Classification Report:
              precision    recall  f1-score   support

           0       0.82      0.91      0.86      1036
           1       0.64      0.46      0.53       373

    accuracy                           0.79      1409
   macro avg       0.73      0.68      0.70      1409
weighted avg       0.78      0.79      0.78      1409
