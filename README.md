# 📊 Data Analytics & Engineering Portfolio

A curated collection of academic and hands-on projects showcasing skills in **Data Cleansing**, **Data Warehousing & Dimensional Modeling**, and **Business / Exploratory Data Analysis**.

---

## 🛠️ Overview of Tech Stack
- **Languages:** Python (`pandas`, `numpy`, `matplotlib`, `seaborn`), SQL (Google Standard SQL)
- **Data Warehouse & Cloud:** Google Cloud BigQuery
- **BI & Data Visualization:** Tableau Desktop, Matplotlib, Seaborn, Microsoft Excel
- **Analytics Tools:** Microsoft Excel (PivotTable, Pivot Chart, Statistical Functions)

---

## 📂 Featured Projects

### 1. 🎬 Top 500 Movies Data Cleaning & Exploratory Analysis
Data cleaning and exploratory analysis of a dataset containing the top 500 highest-budget movies to discover industry trends, budget-to-revenue relationships, and top-performing films.
- **Tech Stack:** Python (`pandas`, `numpy`, `matplotlib`, `seaborn`), Google Colab
- **Key Highlights:**
  - Evaluated dataset schema, imputed missing values, and dropped corrupted/invalid records.
  - Scaled large financial values (budget, gross revenue) to millions of dollars ($M) for standardized analysis.
  - Calculated net profit (`worldwide_gross - production_cost`) and plotted:
    - Genre distributions and release year volume trends.
    - Top 10 most profitable movies vs. top 10 highest-loss movies.
    - Top 10 highest-grossing movies worldwide.

---

### 2. 🏛️ University Class Schedule Data Warehouse & Analytics
End-to-end design and implementation of a university class scheduling data warehouse using Dimensional Modeling on Google Cloud BigQuery, paired with interactive Tableau dashboards.
- **Tech Stack:** Google Cloud BigQuery, Tableau Desktop, Google Standard SQL
- **Key Highlights:**
  - Designed a Star Schema architecture featuring:
    - **Fact Table:** `ClassSchedule` (sections, timings, classrooms, instructors, and terms)
    - **Dimension Tables:** `Course`, `Building`, `Instructor`, and `Date`
  - Authored modular SQL views to aggregate course delivery modes (Lecture/Discussion/Lab/Online), section counts per subject, instructor teaching loads, and building room utilization.
  - Built interactive Tableau visualizations to assist academic resource planning and facility allocation.

---

### 3. 🛒 E-Commerce Sales & Customer Analytics
Performance analytics focusing on product sales, referral channel effectiveness, and customer retention patterns for an online retail business.
- **Tech Stack:** Microsoft Excel (PivotTable, Pivot Chart, Advanced Statistical Formulas)
- **Key Highlights:**
  - Identified the top 5 and bottom 5 selling products based on total order quantity.
  - Evaluated revenue contribution by marketing channel (identifying **Paid Search** as the primary revenue driver).
  - Derived core transaction metrics, including Average Order Value (AOV) and average quantity per order.
  - Analyzed seasonal demand shifts (e.g., product color preferences in Summer vs. Autumn).
  - Investigated coupon redemption data (Groupon) to assess repeat purchase rates and customer loyalty.

---

## 👤 Author
**Napat Boonsej**
