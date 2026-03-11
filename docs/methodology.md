# Methodology

This project analyzes **customer behavior across the e-commerce lifecycle** using event-level interaction data.

The analysis follows a structured workflow consisting of **five major stages**.

---

# 1. Data Collection

The dataset used in this project is the **E-commerce Behavior Dataset from Kaggle**, containing user interaction data from a multi-category online store.

Key dataset statistics:

• **1,999,840 interaction events**
• **935,717 unique users**

Each record represents a user interaction event such as:

* viewing a product
* adding a product to cart
* completing a purchase

---

# 2. Data Cleaning and Preparation

Data preprocessing steps included:

• Standardizing categorical variables
• Converting timestamps to datetime format
• Removing inconsistent values
• Creating derived features for analysis

Feature engineering included:

* extracting **main product categories**
* generating **price bands**
* computing **session metrics**

---

# 3. Funnel Analysis

Customer interactions were analyzed using a **three-stage conversion funnel**:

```
View → Cart → Purchase
```

This analysis identifies:

* drop-off points in the purchase journey
* category-level conversion performance
* price sensitivity patterns

The goal is to determine where user friction occurs in the purchasing process.

---

# 4. Retention and Engagement Analysis

User engagement was analyzed to understand **repeat behavior**.

Key engagement metrics:

• **Average sessions per user:** 1.68
• **Same-day repeat activity:** 29.97%
• **7-day return rate:** 16.28%

These metrics help evaluate how frequently users return to the platform.

---

# 5. Customer Segmentation

Users were segmented based on behavioral metrics such as:

* product views
* cart activity
* purchases
* session frequency

Segments help identify different user groups such as:

• Browsers
• Cart users
• Purchasers
• Low engagement users

Segmentation enables more targeted marketing and retention strategies.

---

# Analytical Tools Used

| Tool     | Purpose                      |
| -------- | ---------------------------- |
| Python   | Data processing and analysis |
| Pandas   | Data manipulation            |
| SQL      | Analytical queries           |
| Power BI | Dashboard visualization      |

The final outputs include **analytical tables, visualizations, and business insights** derived from the lifecycle analysis.

