---------------------------------------------------------------------------------------------------------------------------------

# **📊 Telecom Customer Churn Prediction🔑 📈**

## 🧠 **Project Goal**
The goal was simple but powerful: **predict which customers might leave** a telecom service. By doing this early, we can help companies act fast, offer better service, and keep their valuable customers longer. 💡💼

---

## 📚 **Overview**
Customer churn is a major concern in the telecom world. In this project, we explored customer behavior using **visual analysis** and **machine learning** to predict who might leave the service next. Let’s break it down!

---

## 🎯 **1. Churn Distribution**
A simple bar chart that shows:
- How many customers left (churned) ❌
- How many stayed ✅

📊 ![Churn Distribution](https://github.com/user-attachments/assets/16e097e7-0157-4cd6-8da0-003ae65d351b)

> This gives a quick view of the churn ratio in the entire customer base.

---

## 👩‍🦰🧑 **2. Churn by Gender**
Do men or women churn more?

📊 ![Gender vs Churn](https://github.com/user-attachments/assets/b5da748c-22d8-4488-88f6-76daa0c705cc)

> Shows how churn varies across gender.

---

## 📜 **3. Customer Contract Type**
We checked which contract types customers are using:
- Month-to-month
- One year
- Two year

📊 ![Contract Types](https://github.com/user-attachments/assets/4e75e0e8-9217-4ece-9955-cd22d33492ef)

> Month-to-month customers were more likely to churn.

---

## 💳 **4. Payment Methods**
Who prefers what when paying?

📊 ![Payment Methods](https://github.com/user-attachments/assets/a21dad03-8b53-48ee-82e6-b41e4761870d)

> Electronic check users had the **highest churn rate**.

---

## 🌐 **5. Internet Services**
Let’s see the internet service type distribution.

📊 ![Internet Services](https://github.com/user-attachments/assets/9bb56d9a-6ef4-486e-a81b-8ed1e722d6ea)

> Fiber optic users showed **higher churn**.

---

## 👨‍👩‍👧 **6. Dependent Status**
Do customers with dependents churn less?

📊 ![Dependents](https://github.com/user-attachments/assets/5bd699ef-cdf3-4c8c-9fca-fbb40b08dfd8)

> Customers with dependents tend to stay longer!

---

## 🔐 **7. Online Security**
Does online security affect churn?

📊 ![Online Security](https://github.com/user-attachments/assets/32a29f5b-7bae-4738-ab87-44781a960449)

> Yes! Those without online security churn more.

---

## 👵 **8. Senior Citizens**
Are older customers more likely to leave?

📊 ![Senior Citizens](https://github.com/user-attachments/assets/14e8bbec-9bb6-433b-82eb-9dd65e65c1e5)

> Churn is **higher among senior citizens**.

---

## 🧾 **9. Paperless Billing**
Paperless vs traditional billing — who churns more?

📊 ![Paperless Billing](https://github.com/user-attachments/assets/e65420bd-fbcf-4ed9-b483-d9598d2741b3)

> Customers using **paperless billing churn more**.

---

## 🛠️ **10. Tech Support**
Does having tech support reduce churn?

📊 ![Tech Support](https://github.com/user-attachments/assets/0462391c-2bfa-41ad-9b4c-b798eb954e08)

> Tech support plays a role in customer **retention**!

---

## 📈 **11. Monthly Charges & Tenure**
We visualized:
- How much people pay 💸
- How long they've stayed ⏳

📊 ![Monthly Charges](https://github.com/user-attachments/assets/e5ee24c6-8d4a-4a25-ab08-2e366b7d7b06)  
📊 ![Tenure Distribution](https://github.com/user-attachments/assets/bb81d353-9e2d-4bf2-b1cc-850ac95717ee)

> New customers paying **more** tend to churn more!

---

## 🧪 **Machine Learning Model Evaluation**
We trained a model to **predict churn** and here’s how well it performed:

| Metric              | Score   |
|---------------------|---------|
| ✅ Accuracy          | **0.79** |
| 📊 ROC AUC          | **0.84** |
| 📉 Precision (Churn) | **0.64** |
| 🔍 Recall (Churn)    | **0.46** |
| ⚖️ F1-score (Churn)  | **0.53** |

🔢 **Confusion Matrix**  
```
[[942   94]
 [203  170]]
```

> Our model gives a solid base to predict customer behavior and guide business decisions.

---

