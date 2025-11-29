# 🏦 Banking Customer Churn Analysis

**Uncovering why customers leave and how to keep them.**

A data-driven analysis of 10,000 banking customers to identify churn patterns and provide actionable retention strategies.

---

## 📊 Project Overview

**The Problem:**  
A European bank faces a 20.4% customer churn rate (2,038 customers lost annually).

**The Question:**  
What drives customers to leave, and how can we prevent it?

**The Answer:**  
Behavioral factors (product adoption and engagement) matter far more than demographics (age, gender, location).

---

## 💡 Key Findings

### 1. The 2-Product Sweet Spot
- Customers with **2 products**: 7.6% churn ✅
- Customers with **1 product**: 27.7% churn ❌
- **70% better retention** with the right product count

### 2. Active Membership Matters
- **Active members**: 14.3% churn
- **Inactive members**: 26.9% churn
- Activation cuts churn in **half**

### 3. Demographics Don't Matter
- All countries show ~20% churn (France, Germany, Spain)
- Gender has no impact (Male 20.6%, Female 20.1%)
- Age has no impact (all groups ~20%)
- **Takeaway:** Focus on behavior, not demographics

### 4. High Balance = High Risk (Surprising!)
- Customers with money: 24.1% churn
- Zero balance customers: 13.9% churn
- Don't assume wealthy customers are loyal

### 5. Correlation Misses Patterns
- NumOfProducts shows weak correlation (-0.05)
- Yet it's the **strongest predictor** of churn
- **Lesson:** Always visualize your data!

---

## 🛠️ Tools & Technologies

- **Python 3.9+** - Programming language
- **Pandas** - Data manipulation
- **Matplotlib & Seaborn** - Visualizations
- **Jupyter Notebook** - Analysis environment

---

## 🎯 Top Recommendations

1. **Cross-sell single-product customers** to 2 products (highest impact)
2. **Launch re-engagement campaigns** for inactive members
3. **Stop demographic targeting** - it doesn't work
4. **Proactively manage high-balance customers** - they're at risk
5. **Investigate why 3-4 product customers leave** (80-100% churn)

---

## 📊 Dataset

- **Source:** Maven Analytics
- **Size:** 9,998 customer records
- **Features:** Demographics, account info, product usage, churn status
- **Time Period:** Cross-sectional snapshot

---