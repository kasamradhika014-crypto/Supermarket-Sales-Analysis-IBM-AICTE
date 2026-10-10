# Supermarket Sales Analysis - AI & Data Analytics Internship

**Author:** Radhika Kasam  
**Internship Program:** AICTE | IBM SkillsBuild Data Analytics with AI (Conducted by BharatCares)  
**Dataset:** Supermarket Sales Dataset (500 Transactions)

---

## Project Overview
This project presents an exploratory and predictive analysis of 500 supermarket sales transactions across branches in Mumbai, Jaipur, and Bengaluru. The study examines revenue patterns by branch, top-selling product categories, payment channel adoption, customer segment behaviors (Member vs. Normal), and satisfaction ratings. A machine learning regressor is applied to predict transaction value and identify key sales drivers.

---

## Tech Stack & Dependencies
- **Language:** Python 3.x
- **Data Manipulation:** `pandas`, `numpy`
- **Data Visualization:** `matplotlib`, `seaborn`
- **Machine Learning:** `scikit-learn` (RandomForestRegressor, Train-Test Split, Evaluation Metrics)
- **Environment:** Google Colab / Jupyter Notebook

---

## Key Analytical Findings
1. **Top Performing Branch:** Branch C (Mumbai) generated the highest total sales volume (₹72,469.45).
2. **Leading Category:** Beverages led all categories in revenue generation.
3. **Payment Preferences:** Digital payments dominate, with **UPI** recorded as the most frequent payment mode.
4. **Member vs. Normal Customer Spend:** Normal customers averaged approximately ₹497.07 per transaction, compared to ₹483.14 for loyalty members.
5. **Customer Satisfaction:** Customer ratings averaged ~3.99 out of 5.00 across transactions.
6. **Predictive Analytics:** Random Forest regression revealed that purchase quantity and unit price are the primary deterministic features driving transaction size.

---

## Setup and Execution
1. Clone the repository:
   ```bash
   git clone <YOUR_REPOSITORY_LINK>
   cd <REPOSITORY_FOLDER>