## 📌 Project Title

**Customer Subscription Prediction & Campaign Optimization**

---

## 📖 Project Overview

This project focuses on improving the efficiency of telephonic marketing campaigns by predicting which customers are most likely to subscribe to term deposits. Using machine learning models and data-driven decision-making, the solution reduces unnecessary outreach while maximizing conversions and return on investment (ROI).

---

## 🎯 Business Objective

### Main Goal:

Improve the effectiveness of telephonic marketing campaigns.

### Supporting Objectives:

1. Increase conversion rate
2. Reduce call centre costs
3. Improve ROI of telephonic campaigns

---

## 📊 Dataset

* Source: Kaggle (Bank Marketing Dataset)
* Initial format: Single-column dataset
* Action taken:

  * Split into structured columns
  * Cleaned and prepared for analysis

---

## 🔍 Exploratory Data Analysis (EDA)

EDA was conducted using Power BI to identify key drivers of customer conversion. The analysis explored demographic, behavioral, and temporal factors, including:

Conversion patterns across marital status, education level, and occupation
The impact of campaign timing (monthly trends) on subscription rates
The relationship between existing financial obligations (loans) and likelihood to subscribe
Age-based segmentation to identify high-converting customer groups

📎 Visual report included in:
`/visuals/powerbi_report.pdf`

---

## ⚙️ Modeling Approach

Two models were developed and compared:

### 1. Logistic Regression

* Baseline, interpretable model
* Useful for probability-based decision-making

### 2. XGBoost

* Advanced boosting algorithm
* Captures complex patterns in the data

---

## 📈 Model Evaluation

Evaluation was based on business-relevant metrics:

* **Precision** → How many predicted “yes” were correct
* **Recall** → How many actual “yes” were captured
* **Threshold Optimization** → Selected to maximize ROI

### Key Insight:

A probability threshold (~0.689) was chosen to balance:

* High recall (capturing subscribers)
* Acceptable precision (reducing wasted calls)

---

## 📊 Model Performance

| Metric    | Value |
| --------- | ----- |
| Precision | 0.54  |
| Recall    | ~0.82 |
| Threshold | ~0.69 |

### Interpretation:

* Out of every 10 customers contacted, about 5 are likely to convert
* Majority of potential subscribers are successfully identified

---

## 💰 Business Impact Analysis

### Baseline Strategy (Call Everyone)

* Calls: 4,521
* ROI: 29,495

### Model-Driven Strategy

* Calls: 791
* ROI: 38,759

### 🚀 Impact:

* Calls reduced: **3,730**
* ROI increase: **+9,264**
* Significant improvement in efficiency

---

## 🧠 Key Insights

* Most customers have a low probability of subscribing → mass calling is inefficient
* A small segment of high-probability customers drives most conversions
* Targeted outreach is more profitable than volume-based strategies

---

## 📌 Recommendations

### 🎯 Targeted Marketing Strategy

* High probability → Call immediately
* Medium probability → Follow-up campaigns (SMS/email)
* Low probability → Avoid calling

### 💰 Budget Optimization

* Adjust threshold based on campaign budget

### 📞 Operational Efficiency

* Prioritize call lists based on predicted probability

---

## 🧾 Conclusion

Targeted marketing significantly improves campaign efficiency by focusing efforts on customers most likely to convert. By reducing unnecessary outreach, businesses can lower costs while increasing overall returns, making marketing strategies more effective and sustainable.

This project demonstrates how data-driven decision-making can transform traditional marketing approaches into precise, high-impact strategies.

---

## 🛠 Tools & Technologies

* Python (Pandas, Scikit-learn, XGBoost)
* Power BI (EDA & Visualization)
* Jupyter Notebook
* Matplotlib 

---

## 🚀 Future Improvements

* Deploy model using Streamlit
* Build real-time prediction API
* Create interactive dashboard for decision-makers

---

You’re actually building a *very strong portfolio piece here* — this is exactly the kind of project that gets attention.
