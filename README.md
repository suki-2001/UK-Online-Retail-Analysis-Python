# UK-Online-Retail-Analysis-Python


## 1 Project Title

**Customer Segmentation and Revenue Prediction using RFM Analysis**

---

## 2 Short Description / Purpose

A data-driven machine learning workflow that segments customers based on their purchasing behavior using RFM analysis and predicts revenue using linear regression. Built for retail strategists, marketing analysts, and decision-makers aiming to personalize campaigns and forecast customer value.

---

## 🛠3 Tech Stack

* **Python (Pandas, NumPy)**
  For data manipulation, aggregation, and feature engineering.

* **Scikit-learn**
  Used for clustering (KMeans) and building linear regression models.

* **Matplotlib & Seaborn**
  For visualizing distributions, relationships, and cluster patterns.

* **Jupyter Notebook**
  For interactive development and EDA.

* **Excel / CSV Files**
  Raw transactional data used as the foundational data source.

---

## 4 Data Source

* **Source:** Transactional data from UCI Machine Learning Repository.
* **Fields include:** Invoice No, Stock Code, Description, Quantity, Invoice Date, Unit Price, Customer ID, and Country.
* The dataset includes historical purchase records of customers, useful for behavioral segmentation and revenue analysis.

---

## 5 Features and Highlights

### Business Problem

Retailers often lack clarity on which customers are truly valuable. Without clear segmentation, marketing budgets are spread thin and re-engagement efforts fall flat.

### Goal of the Dashboard

To create business-friendly customer segments and build a predictive model that enables:

* Targeted marketing
* Re-engagement strategies
* Revenue forecasting

### Walkthrough of Key Visuals and Components

* **RFM Table Construction:**
  Recency, Frequency, and Monetary metrics were computed per customer.

* **Customer Clustering (KMeans):**
  5 customer segments were derived using the elbow method and silhouette analysis.

* **Segment Profiles Visualization:**
  Each cluster is visualized by its RFM values to understand behavior.

* **Revenue Prediction Model:**
  A simple linear regression predicting monetary value using recency and frequency.

* **Insights Section:**
  Strategic recommendations tied to each customer segment for marketing optimization.

### Business Impact & Insights

* **Segment 0:** High-value loyalists; reward and retain.

* **Segment 1:** At-risk customers; reactivate with offers.

* **Segment 2:** Low-value one-timers; focus less.

* **Segment 3:** Potential loyalists; upsell opportunities.

* **Segment 4:** New/low-spend recents; nurture.

* **Recency was the key** in predicting future purchases.

* **Pareto principle confirmed:** \~20% of customers generate 80% of revenue.

✅ *Outcome:* The project enables focused marketing, improves retention, and guides budget allocation.

---

## Detailed Findings & Strategic Insights

### 1. Customer Segments Are Not Created Equal

Using KMeans clustering on RFM features:

* Segment 0: VIP buyers with high recency and spend.
* Segment 1: Formerly active, now dormant.
* Segment 2: Low-value, low-frequency buyers.
* Segment 3: Consistent but moderate spenders.
* Segment 4: Recent activity, low monetary value.

**Action:** Tailor offers and engagement strategies based on behavior.

### 2. Recency is a Strong Predictor of Engagement

Customers who bought recently were much more likely to buy again.

**Action:** Monitor recency KPIs regularly to prevent churn.

### 3. Revenue Prediction Validates Segment Value

Regression showed:

* Recency ↓  → Monetary ↓
* Frequency ↑ → Monetary ↑

**Action:** Target frequent and recent buyers for cross-sell campaigns.

### 4. Strategic Business Recommendations

* Focus retention efforts on top 2 segments.
* Design onboarding flows for new buyers.
* Re-target dormant customers with discounts.

✅ **Result:** Improved ROI, more personalized marketing, and data-driven decision making.

---

