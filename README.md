# 📈 Sales Analytics – Retail Sales Prediction using Machine Learning

> 🏫 **College Final Project – BCA 4th Semester**  
> 🏢 **INVERTIS UNIVERSITY**, Bareilly, U.P. (India)  
> 🎓 **Department of Computer Applications**  
> 💼 **CSED (Centre for Skill and Entrepreneurship Development)**  
> 📘 **Subject:** Machine Learning  
> 📗 **Subject Code:** IIOT4  
> 👨‍🏫 **Mentor:** Mr. Mayank Singh  
> 👥 **Team:** Team-4 | Team Leader: Abhishek Kumar
> > 👥 **Me:**  Abhishek Maheshwari | EDA & Docs 
> 📅 **Academic Year:** 2024–2025

---

## 🗂️ Project Overview

**Sales Analytics** is a machine learning-based project focused on **predicting weekly retail sales** using real-world historical data. Retailers generate massive data every day. This project helps transform that raw data into meaningful insights that support inventory optimization, strategic marketing, and workforce planning.

By using **data cleaning, EDA (Exploratory Data Analysis), feature engineering, and machine learning models**, we aim to forecast future sales effectively.

---

## 📌 Problem Statement & Objectives

### 🎯 Goal:
Predict retail weekly sales and understand what factors influence them the most.

### ✅ Objectives:
- Identify key sales drivers like store type, holidays, size, etc.
- Preprocess and clean raw datasets
- Explore patterns via EDA
- Build and evaluate machine learning models
- Visualize final results for better decision-making

---

## 🧰 Tools & Technologies Used

- **Programming Language:** Python 3.x  
- **IDE:** Jupyter Notebook / VS Code  
- **Libraries:**  
  - Pandas  
  - NumPy  
  - Matplotlib  
  - Seaborn  
  - Scikit-learn  

---

## 📁 Repository Contents

| File/Folder                   | Description                                      |
|------------------------------|--------------------------------------------------|
| `Sales_Analytics.ipynb`      | Jupyter Notebook with full code and analysis     |
| `features.csv`               | Store-level features (fuel price, holidays, etc.)|
| `sales.csv`                  | Weekly department-wise sales data                |
| `stores.csv`                 | Store info like size and type                    |
| `images1-5`                  | Graphs & visuals from EDA                        |
| `Sales_Analytics_PPT.pptx`   | Final PowerPoint presentation                    |
| `Sales_Analytics_Report.pdf` | Full documentation/report                        |

---

## 📊 Project Flow

### 1. 📥 Data Preprocessing
- Converted date formats
- Handled missing values
- Label-encoded categorical columns
- Scaled temperature, fuel prices, etc.

### 2. 📈 Exploratory Data Analysis (EDA)
- Analyzed sales trends across stores
- Studied holiday impacts
- Visualized sales patterns by store type and time

### 3. ⚙️ Feature Engineering
- Extracted Month, Week, Year from Date
- Created `IsHoliday` binary flag
- Calculated Sales per Area for normalization

### 4. 🔄 Correlation & Multicollinearity
- Created heatmaps
- Applied Variance Inflation Factor (VIF)
- Removed redundant correlated features

### 5. 🤖 Model Building
- Trained and tested models including:
  - ✅ Random Forest Regressor (Best performer)

### 6. 📊 Evaluation Metrics
- **R² Score** – Used to evaluate model fit
- High R² score indicated strong prediction performance

---

## 🔍 Key Insights

- Store size and promotions are highly influential on sales
- Holiday impacts vary by department and time
- Store Type A showed highest sales volume
- Random Forest produced the most accurate predictions
- Visualization helped understand seasonality and high-performing departments

---

## 📌 Future Work

- Optimize promotions during peak seasons
- Add department-level holiday analysis
- Use time series forecasting (e.g., Prophet)
- Build real-time analytics dashboard
- Expand model to support regional store forecasting

---

## 📚 References

- [Python Docs](https://docs.python.org)
- [Scikit-learn](https://scikit-learn.org)
- [Pandas](https://pandas.pydata.org)
- [NumPy](https://numpy.org)
- [Matplotlib](https://matplotlib.org)
- [Seaborn](https://seaborn.pydata.org)

---

## 👥 Team Members

| Name                | Role           |
|---------------------|----------------|
| Abhishek Kumar      | Team Leader    |
| Abhishek Maheshwari | EDA & Docs     |
| Vaishnavi Gupta     | Contributor    |
| Ridhima Maheshwari  | Contributor    |
| Vansh Gupta         | Contributor    |
| Samina Nooreen      | Contributor    |
| Soni                | Contributor    |
| Mohd Sheeban Khan   | Contributor    |
| Ankit Kumar         | Contributor    |
| Sanjay Mishra       | Contributor    |
| Arpit Gupta         | Contributor    |
| Aryan Srivastava    | Contributor    |
| Anubhav Gangwar     | Contributor    |

---

## 🙏 Acknowledgements

Special thanks to **Mr. Mayank Singh** for mentoring and guiding us throughout this academic project. Also, gratitude to our teammates for collaborative efforts in analysis, coding, report writing, and presentation preparation.

---

> 🌟 *If you find this helpful or inspiring, please ⭐ star the repository and share your feedback!*
