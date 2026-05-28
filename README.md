# 🚗 Coupon Acceptance Analysis

## 📌 Project Overview
This project analyzes customer behavior to determine what factors influence whether a driver accepts a mobile coupon while driving. Using exploratory data analysis (EDA), we identify patterns across demographics, behavior, and contextual conditions.

The dataset originates from the UCI Machine Learning Repository and simulates real-world decision-making scenarios involving coupon offers for restaurants, bars, and coffee houses.

---

## 🎯 Objectives
- Understand overall coupon acceptance behavior
- Identify key factors influencing acceptance rates
- Perform targeted analysis on bar coupons
- Derive actionable insights using visualization and statistical summaries

---

## 📊 Dataset Description
The dataset includes three categories of features:

### 1. User Attributes
- Gender, Age, Marital Status
- Income, Education, Occupation
- Frequency of:
  - Bar visits
  - Coffee house visits
  - Restaurant visits

### 2. Contextual Attributes
- Destination (Home, Work, No urgent destination)
- Weather (Sunny, Rainy, Snowy)
- Time (10AM, 2PM, 6PM)
- Passenger (Alone, Friends, Partner, Kids)
- Temperature

### 3. Coupon Attributes
- Coupon type (Bar, Coffee House, Restaurant, etc.)
- Expiration (2 hours / 1 day)

### Target Variable
- `Y = 1` → Accepted coupon
- `Y = 0` → Rejected coupon

---

## ⚙️ Tools & Technologies
- Python (Pandas, NumPy)
- Visualization: Matplotlib, Seaborn
- Jupyter Notebook

---

## 🔍 Key Findings

### ✅ Overall Behavior
- **56.8% of drivers accepted coupons**
- Indicates moderate willingness to engage with offers

---

### 🍺 Bar Coupon Analysis
- Acceptance rate: **~41%** (lower than overall)
  
#### Key Drivers:
- **Frequent bar visitors**
  - Acceptance increases from ~29% → ~69%
- **Age factor (25+)**
  - Older individuals show higher engagement

---

### 📈 Behavioral Insights
- Past behavior is the strongest predictor of acceptance
- Users are more likely to accept coupons aligned with their lifestyle
- Demographics (age) amplify behavioral tendencies

---

## 🧠 Hypothesis
> Drivers who frequently engage in a specific activity (e.g., visiting bars) are significantly more likely to accept coupons related to that activity.

---

## 📊 Visualizations Included
- Coupon distribution (bar chart)
- Temperature distribution (histogram)
- Behavioral segmentation (group comparisons)

---

## 📁 Repository Structure│
├── assignment5_1.ipynb   # Main analysis notebook
├── data/
│   └── coupons.csv                # Dataset
├── images/                        # Visualizations
├── README.md                      # Project summary
└── requirements.txt               # Dependencies
