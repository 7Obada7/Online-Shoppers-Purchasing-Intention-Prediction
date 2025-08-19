# Online Shoppers Purchasing Intention Prediction 🛒📊

A **data analysis and machine learning project** focused on predicting whether an online shopping session will lead to a purchase.  
The project uses the **Online Shoppers Purchasing Intention Dataset** and applies multiple machine learning algorithms to model customer behavior and purchasing intent.  

---

## 🎯 Project Objective
The aim of this project is to:
- Analyze user browsing behavior on e-commerce websites.  
- Predict **purchase intentions** using session-level features such as page visits, bounce rates, exit rates, and time spent on product pages.  
- Improve personalization and sales strategies through predictive modeling.  

---

## 🗂 Dataset
**Online Shoppers Purchasing Intention Dataset**  
- 12,330 sessions from an e-commerce website.  
- 17 features including:
  - Page categories: *Administrative, Informational, Product Related* (+ durations).  
  - Google Analytics metrics: *Bounce Rate, Exit Rate, Page Value*.  
  - Special event proximity: *Special Day*.  
  - Technical & demographic info: *Operating System, Browser, Region, Traffic Type, Visitor Type, Weekend, Month*.  
- **Target Variable**: `Revenue` (whether the session resulted in a purchase).  

---

## 🛠 Methods & Techniques
Applied machine learning algorithms:
- Logistic Regression  
- Decision Trees  
- Random Forest  

Key steps:
1. Data preprocessing and feature engineering.  
2. Training and evaluation of models.  
3. Comparison of models using accuracy, precision, recall, and F1-score.  

---

## 📊 Results
- Models achieved meaningful performance in predicting online purchasing intention.  
- **Random Forest** yielded the best trade-off between precision and recall.  
- Insights show that **page-related features** and **special event proximity** strongly influence purchasing behavior.  

---

## 💡 Tech Stack
- **Python**  
- Pandas, NumPy, Scikit-learn  
- Matplotlib / Seaborn (visualization)  
- Jupyter Notebook  

---

## 🙏 Acknowledgments
- Dataset: [Online Shoppers Purchasing Intention Dataset](https://archive.ics.uci.edu/ml/datasets/online+shoppers+purchasing+intention+dataset)  
- Project developed as part of a university Introduction to Data Science course.  
