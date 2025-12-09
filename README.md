# 📊 Telecom Customer Churn Analysis  
A complete data analytics project using **Python**, **Machine Learning**, and **Power BI** to analyze and predict telecom customer churn.

---

## 📁 Project Structure

telecom-churn-analysis/
│
├── churn_analysis.ipynb # Full EDA + ML notebook
├── Telecom_Churn_Dashboard.pbix # Power BI dashboard
├── telco_customer_churn.csv # Dataset
├── images/ # Dashboard screenshots (optional)
└── README.md # Project documentation


---

## 📝 Project Overview

Customer churn is a major challenge for telecom companies.  
This project focuses on understanding **why customers leave** and building a **predictive model** + **Power BI dashboard** to help the business take action.

This project demonstrates:

🔹 Data cleaning & preprocessing  
🔹 Exploratory Data Analysis (EDA)  
🔹 Machine Learning modeling  
🔹 Feature importance analysis  
🔹 Power BI dashboard creation  
🔹 Actionable insights for business decisions  

---

## 🛠 Technologies Used

- **Python** (Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn)
- **Jupyter Notebook**
- **Power BI**
- **Git & GitHub**

---

## 📂 Files Included

| File | Description |
|------|-------------|
| `churn_analysis.ipynb` | Python notebook with EDA + model building |
| `Telecom_Churn_Dashboard.pbix` | Full Power BI dashboard |
| `telco_customer_churn.csv` | Dataset used for analysis |
| `images/` | Dashboard screenshots (add optional images here) |
| `README.md` | Project documentation |

---

## 🔍 Key Insights

- **Customers with 0–12 months tenure churn the most**
- **Month-to-month contracts** show the highest churn  
- **Electronic check** users churn significantly more  
- **Fiber optic** subscribers churn more than DSL  
- **High monthly charges** strongly correlate with churn  
- Lack of **OnlineSecurity** and **TechSupport** increases churn  

---

## 🤖 Machine Learning Model

Best model: **Random Forest Classifier**

### **Performance:**
- **Accuracy:** ~78%
- Good precision for "No churn"
- Identifies important churn-driving features such as:
  - TotalCharges  
  - Tenure  
  - MonthlyCharges  
  - InternetService (Fiber Optic)  
  - PaymentMethod (Electronic Check)

---

## 🚀 How to Run the Project

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/telecom-churn-analysis.git
cd telecom-churn-analysis
```


2️⃣ Install dependencies (optional)

pip install -r requirements.txt

3️⃣ Run the Jupyter Notebook

jupyter notebook churn_analysis.ipynb

4️⃣ Open the Power BI Dashboard

   Use Power BI Desktop → Open Telecom_Churn_Dashboard.pbix

---

## ⭐ Business Recommendations

Based on the analysis:

 -Offer discounts or loyalty perks for first-year customers

 -Promote 1-year & 2-year contracts to reduce churn

 -Encourage auto-pay methods instead of Electronic Check

 -Provide security add-ons & tech support for high-risk users

 -Re-evaluate pricing strategy for customers with high monthly charges

 -Improve onboarding experience to prevent early-tenure churn

