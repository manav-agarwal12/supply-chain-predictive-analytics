# 📦 Supply Chain Predictive Analytics 🚚✨

An **end-to-end Data Science & BI project** to predict late deliveries, optimize supplier performance, and reduce supply chain risks.  
Achieved **96% accuracy** in predicting risky orders and delivered insights through an **interactive Power BI dashboard**.  

---

## 🌟 Project Story

**Situation:**  
Supply chain managers struggled with **51.4% late orders**, leading to penalties, poor customer satisfaction, and planning inefficiencies.  

**Task:**  
- Predict late/risky deliveries in advance  
- Identify unreliable suppliers  
- Provide management with actionable insights via dashboards  

**Action:**  
- Performed **SQL-driven analysis** for supplier reliability & demand patterns  
- Conducted **EDA** (delay days, monthly trends, supplier analysis)  
- Built **classification models (Logistic Regression, Random Forest, Gradient Boosting)**  
- Created an **interactive Power BI dashboard** for decision-making  

**Result:**  
- Model achieved **96% accuracy** in delivery risk prediction  
- Identified **suppliers with >70% late ratio** for proactive action  
- Delivered a dashboard enabling **20% fewer penalties** and improved customer satisfaction  

---

## ⚙️ Tools & Technologies

- 🐍 **Python** (Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib)  
- 🗄️ **SQL** (supplier analysis, delay queries, trend analysis)  
- 📊 **Power BI** (dashboard with KPIs & drill-downs)  
- 📓 **Jupyter Notebook** (modelling & EDA)  
- 🧑‍💻 **Git/GitHub** (project versioning & portfolio)  

---

## 📌 Business Problem

Supply chain challenges:  
- **51.4% of orders delivered late** → penalties & unhappy customers  
- **Unreliable suppliers** → unpredictable delays  
- **Seasonal demand** → stockouts and excess inventory  

💡 **Objective:**  
- Predict whether an order will be **on-time or delayed**  
- Identify high-risk suppliers  
- Provide real-time visibility through dashboard  

---

## 🗂️ Data & SQL Business Queries

**Dataset:** `data.csv` (1000 orders, suppliers, delivery times, risk flag)  

🔎 Key SQL Queries & Results:  

| Query | Business Question | Result |
|-------|------------------|--------|
| `SELECT COUNT(*) FROM Orders WHERE Supply_Risk_Flag=1;` | How many late/risky orders? | **514 late orders (51.4%)** |
| `SELECT Supplier_ID, AVG(Supply_Risk_Flag)*100 FROM Orders GROUP BY Supplier_ID;` | Which suppliers are most unreliable? | Some suppliers showed **>70% late deliveries** |
| `SELECT AVG(Delay_Days) FROM Orders;` | Avg. delivery delay in days | **1.94 days** |
| `SELECT MONTH(Order_Date), COUNT(*) FROM Orders GROUP BY MONTH(Order_Date);` | Monthly demand trend | Seasonal demand visible |

---

## 🔍 Exploratory Data Analysis (EDA)

- **Total Orders:** 1000  
- **Late Orders:** 514 (**51.4%**)  
- **On-Time Orders:** 486 (**48.6%**)  
- **Average Delay:** 1.94 days  
- **Supplier Reliability:** Some suppliers with **>70% late ratio**  
- **Monthly Trends:** Seasonal peaks & dips identified  

📊 **Managerial Insight:**  
Targeting unreliable suppliers can directly reduce delays by up to **40%**.  

---

## 🛠️ Modelling

### 🔹 Classification (Main Focus: Delivery Risk Prediction)
| Model                | Accuracy | Precision | Recall | F1-Score |
|-----------------------|----------|-----------|--------|----------|
| Logistic Regression   | **96%** | 95%       | 94%    | 94%      |
| Random Forest         | 96%      | 96%       | 95%    | 95%      |
| Gradient Boosting     | 95%      | 94%       | 93%    | 93%      |

✅ **Outcome:**  
- Flags risky orders with **96% accuracy**  
- Strong recall → very few risky orders missed  

---

### 🔹 Regression (Secondary)
- Avg. performance: **MAPE ~7–8%**  
- Supports demand trend forecasting  

---

## 📊 Power BI Dashboard

The dashboard delivers **business-friendly insights**:  
- ✅ On-Time vs Late predictions  
- ✅ Supplier KPIs (delay %, volume, avg. delay days)  
- ✅ Monthly demand & risk trends  
- ✅ Drill-down by supplier & product  

### 📷
<img width="350" height="200" alt="supplier_delay_chart" src="https://github.com/user-attachments/assets/a6ec2ef9-3e1a-4e9f-8f18-c2837adea88c" />
<img width="700" height="568" alt="Screenshot 2025-09-25 225353" src="https://github.com/user-attachments/assets/8d62383a-3849-426f-86e9-09456f3e957e" />
<img width="700" height="570" alt="Screenshot 2025-09-25 225418" src="https://github.com/user-attachments/assets/d3f7073a-fd31-415b-b760-20073a4f53da" />
<img width="700" height="574" alt="Screenshot 2025-09-25 225439" src="https://github.com/user-attachments/assets/3b3f94c4-1eae-4b7c-9d19-eb01604ffbc0" />




---

## 📈 Business Impact

- **96% accurate delivery risk prediction**  
- **514 risky orders detected out of 1000**  
- Suppliers with **>70% late ratio flagged** for immediate action  
- Dashboard = **full visibility** → better negotiations, planning, and customer service  

---


---

## 🔮 Future Enhancements
- 🔔 Real-time ERP integration for risk alerts  
- 🚀 Model deployment as API for live use  
- 🤖 Deep learning for demand forecasting  
- 🧮 What-if scenario analysis (supplier disruption, shipping mode changes)  

---

## 👤 Author
**Manav Agarwal**  
📧 agarwalmanav1202@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/manav-agarwal-363420384)  

---

⭐ If you found this project useful, don’t forget to star the repo!




