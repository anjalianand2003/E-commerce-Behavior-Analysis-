# E-commerce-Behavior-Analysis-
# 📊 Ecommerce Behavior Analysis

This project explores user interaction patterns on an e-commerce platform. It focuses on user types, purchase intent, state-wise traffic, and how frequently users visit the website.

## 📦 Dataset

- **File:** `ecommerce-data.csv`
- **Observations:** Varies (based on provided file)
- **Features include:**
  - `profile`: User type (e.g., Parent, Teacher)
  - `intentWasPlanningToBuy`: Purchase intent (e.g., Yes, No, Maybe)
  - `country`, `region`: User geography
  - `behavNumVisits`: Numeric site visit frequency

---

## 🎯 Questions Explored

1. Dataset size and structure
2. Frequency of visitors by **country** and **state**
3. Two-way table: **Purchase intent** vs **User profile**
4. Proportions of **Parents vs Teachers** who planned to purchase
5. Most common **state of origin** among users
6. **Histogram** and **boxplots** for visit distribution
7. **Profile-based comparison** of site visits

---

## 🧠 Key Techniques

- Frequency and proportion tables
- Cross-tabulations for subgroup analysis
- Histogram with kernel density overlay
- Boxplots for group comparison
- State and country-wise user analytics

---

## 📈 Visualizations

- Histogram of user visits with density overlay
- Horizontal boxplots of visit counts
- Profile-wise comparisons of visit behavior

---

## 💻 How to Run

```r
# Required environment: R or RStudio
# Required packages: base R (no additional libraries needed except 'graphics')

source("ecommerce_behavior_analysis.R")
