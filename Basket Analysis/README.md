# 🛒 Basket Analysis Optimization

This repository contains the analysis and recommendations for a **Basket Analysis** project aimed at maximizing cross-sell opportunities in a grocery store. The project leverages transactional sales data to identify product pairs with high purchase affinity, enabling strategic placement of promotional bins to enhance the customer shopping experience.

---

## 📋 Project Overview

### **Objective**
Identify top product pairs for cross-promotion in grocery stores using metrics like **Support**, **Lift**, and **Confidence**, with the goal of:
- Maximizing cross-sell opportunities.
- Enhancing the overall shopping experience.

---

## 🔍 Key Insights & Recommendations

### **Executive Summary**
The basket analysis evaluated **170 product pairs** across **14,963 transactions** from **Jan 1, 2014, to Dec 30, 2015**. Recommendations are based on:
- **Support > 0.45%**
- **Lift > 1**
- Ranked by **Confidence** within each pair.

#### **Top 5 Recommended Product Pairs**:
1. **Small Milk** in bin, next to **Fish** location:
   - Rare pair, but occurs **9.07x** more frequently than expected.
   - **80% chance** to purchase small milk after buying fish.
   - Suggest **A/B testing** for validation.
   
2. **Salad Dressing** in bin, next to **Other Vegetables** location:
   - Common combination for salad preparation.

3. **Sauces** in bin, next to **Chicken** location:
   - Popular recipe combination, aligned with competitor practices.

4. **Soda** in bin, next to **Rolls/Buns** location:
   - Affordable, popular meal combo appealing to budget-conscious shoppers.

5. **Herbs** in bin, next to **Pork** location:
   - Ideal for promoting convenient meal solutions.

#### **Runner-Up Pairs**:
Additional pairs were identified but excluded due to logistical or contextual limitations:
- **Bottled Beer & Sausage**: Excluded due to Canadian liquor sale regulations.
- **Shopping Bags & Large Milk**: Placement near bins unnecessary due to checkout availability.

---

## 📂 Repository Contents

| File Name                           | Description                                                  |
|-------------------------------------|--------------------------------------------------------------|
| **`Basket_Analysis_Data.xlsx`**     | Transactional sales data used for the analysis.              |
| **`Basket_Analysis_Report.pdf`**    | Detailed report with analysis, recommendations, and visuals. |
| **`Basket_Analysis_Instructions.pdf`** | Original project instructions and requirements.             |

---

## 📊 Methodology

1. **Data Preparation**:
   - Cleaned and preprocessed transactional data.
   - Extracted product pair purchase frequencies.

2. **Metric Calculation**:
   - **Support**: Frequency of pairs appearing together.
   - **Lift**: Measure of association strength.
   - **Confidence**: Probability of purchasing one item given the purchase of another.

3. **Recommendation Selection**:
   - Filtered pairs based on support, lift, and confidence thresholds.
   - Prioritized practical considerations, such as bin placement and store layout.

---
