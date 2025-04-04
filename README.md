---

# **📊 Telecom Customer Churn Prediction – Let’s Find Out Why Customers Leave! 🔍**

## **🚀 Project Goal**
We built a smart system to **predict which customers are likely to leave** a telecom company. Why? So the company can take action early, **keep their customers happy**, and reduce losses. 🛡️💡

---

## **🔎 What We Explored – The Story in Data**

### **1. 🔑 Churn Overview**
We first checked **how many customers are leaving** vs staying.  
📊 **Bar Chart**:  
- One bar shows those who **left** ("Yes")  
- One bar shows those who **stayed** ("No")  
This gives us a clear picture of the churn situation.

---

### **2. 🚻 Churn by Gender**
Do men or women leave more often?  
📈 **Grouped bar chart** shows:  
- Male vs Female  
- Who stayed vs who left  
📌 **Insight**: Helps tailor retention strategies based on gender.

---

### **3. 📝 Customer Contract Types**
We explored **what kind of contracts customers have**:
- Month-to-month  
- One year  
- Two years  

🧾 Shorter contracts had higher churn. People with long-term contracts tend to stay!

---

### **4. 💳 Payment Methods**
Which payment methods are most used?
- Electronic checks 📱
- Mailed checks ✉️
- Bank transfers 🏦
- Credit cards 💳  

👀 Most churn came from those using **electronic checks**.

---

### **5. 🌐 Internet Services**
We checked customer preferences:
- Fiber optic  
- DSL  
- No internet  

📊 Fiber optic users showed slightly higher churn. Interesting, right?

---

### **6. 👪 Dependents Distribution**
Do customers with dependents leave more often?  
- We grouped churn data by whether customers have dependents (like kids or parents).  
✅ **Insight**: Customers with dependents tend to **stay longer**.

---

### **7. 🔐 Online Security**
Does having online security matter?  
🔍 Customers **without** online security services were more likely to churn.  
This tells us that **security services add value!**

---

### **8. 🧓 Senior Citizens**
Are senior citizens more likely to leave?
📊 Yes – **churn was higher** among them.  
Aging customers may need more support or better packages.

---

### **9. 📩 Paperless Billing**
How does billing method affect churn?  
- Customers using **paperless billing** churned more.  
🧠 Maybe they miss the physical reminder?

---

### **10. 🧑‍💻 Tech Support**
Tech support seems to **keep people happy**.  
- Customers with tech support churned **less**.  
💡 Support = Satisfaction!

---

### **11. 💸 Monthly Charges & Tenure**
We looked at:
- How long customers have stayed (Tenure)  
- How much they pay (Monthly Charges)  

🧮 **Insight**: New customers paying **more** were more likely to churn.

---

## **🤖 Our Machine Learning Model – Does It Work?**

We trained a model to predict churn and here’s how it performed:

✅ **Accuracy**: **79%**  
✅ **ROC AUC**: **0.84**

📊 **Confusion Matrix**:
- Correct predictions: 942 (No churn), 170 (Churn)  
- Missed predictions: 94 (False churn), 203 (Missed churn)

📋 **Classification Report**:
- Precision (how accurate are the "churn" guesses?): 64%  
- Recall (how many actual churners did we catch?): 46%  
- F1-score (balance of both): 53%

---

## **🌟 Key Takeaways**
- Most customers churn **early** in their tenure  
- **Month-to-month plans** and **electronic check users** churn more  
- **Senior citizens** and those **without tech/security support** are at higher risk  
- **Personalized retention plans** can make a big difference!

---

## 🖼️ **Infographic Snapshot**
![Click to View Infographic](https://files.chatgpt.com/file-00000000848851f6a6be0a242dacb75a)  
> A visual summary of everything above, presented beautifully!

---
