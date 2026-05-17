# 📊 🛒 Retail Sales Forecasting & Business Analytics System using Machine Learning

## 🚀 Overview

This project focuses on analyzing retail store sales data using **data analytics, feature engineering, machine learning, SQL, Excel, and Power BI** to uncover business insights and forecast future sales performance.

The objective is to build an end-to-end **Retail Sales Analytics & Forecasting System** capable of analyzing store performance, customer ordering behavior, regional trends, holiday impact, and discount effectiveness while supporting data-driven business decision-making.

The project integrates:

✅ Data Cleaning & Preprocessing
✅ Exploratory Data Analysis (EDA)
✅ Feature Engineering
✅ Machine Learning Forecasting
✅ SQL Business Analysis
✅ Interactive Power BI Dashboard

---

# 🎯 Objectives

* Analyze retail sales and customer ordering patterns
* Perform data cleaning and preprocessing
* Engineer meaningful business-focused features
* Build a machine learning model for sales prediction
* Perform SQL-based business analysis
* Create an interactive Power BI dashboard for insights and forecasting
* Generate actionable recommendations for retail decision-making

---

# 📂 Dataset Description

The dataset contains retail transaction records with the following features:

| Feature         | Description               |
| --------------- | ------------------------- |
| `id`            | Unique transaction ID     |
| `store_id`      | Unique store identifier   |
| `store_type`    | Store category/type       |
| `location_type` | Store location category   |
| `region_code`   | Region identifier         |
| `date`          | Transaction date          |
| `holiday`       | Holiday indicator         |
| `discount`      | Discount applied or not   |
| `numorder`      | Number of customer orders |
| `sales`         | Total sales revenue       |

---

# 🧠 Problem Statement

Retail businesses generate massive amounts of transactional data daily. However, without proper analytics, it becomes difficult to identify sales trends, evaluate store performance, optimize discounts, and forecast future revenue.

This project aims to develop a **data-driven retail analytics system** capable of transforming raw sales data into meaningful business insights using analytics and machine learning techniques.

---

# 🧹 Data Cleaning & Preparation

The dataset was cleaned and transformed using Python.

### Cleaning Steps Performed:

* Fixed inconsistent column names
* Converted date columns into datetime format
* Removed duplicate records
* Handled missing values
* Cleaned categorical variables
* Removed invalid sales and order values
* Prepared dataset for machine learning and visualization

---

# ⚙️ Feature Engineering

Several new business-oriented features were created to improve analysis and prediction performance.

| Feature            | Description                          |
| ------------------ | ------------------------------------ |
| `year`             | Extracted year from transaction date |
| `month`            | Extracted month                      |
| `day_name`         | Day of the week                      |
| `weekend`          | Weekend indicator                    |
| `quarter`          | Business quarter                     |
| `sales_per_order`  | Revenue generated per order          |
| `avg_store_sales`  | Average store sales                  |
| `holiday_discount` | Combined holiday-discount feature    |
| `high_sales`       | High-sales transaction indicator     |

These engineered features enhanced business analysis and machine learning performance.

---

# 📊 Exploratory Data Analysis (EDA)

Comprehensive exploratory analysis was performed to understand sales behavior and business performance.

---

## Monthly Sales Trend

**Insight:** Sales fluctuate significantly across months, indicating seasonal demand patterns.

**Strategy:** Use forecasting and seasonal planning to optimize inventory and marketing campaigns.

---

## Store Type Performance

**Insight:** Certain store types consistently outperform others in revenue generation.

**Strategy:** Focus investment and expansion on high-performing store categories.

---

## Region-wise Sales Analysis

**Insight:** Sales distribution varies considerably across regions.

**Strategy:** Allocate resources strategically to high-performing regions while improving weaker markets.

---

## Discount Impact on Revenue

**Insight:** Discounts positively influence customer purchasing behavior and order volume.

**Strategy:** Optimize discount campaigns during low-performing periods.

---

## Holiday vs Non-Holiday Sales

**Insight:** Holiday periods significantly impact sales performance.

**Strategy:** Increase inventory and marketing activities before holidays.

---

## Orders vs Sales Relationship

**Insight:** Strong positive correlation exists between order volume and revenue.

**Strategy:** Focus on increasing customer order frequency to improve total revenue.

---

## Weekend vs Weekday Analysis

**Insight:** Customer purchasing behavior changes during weekends.

**Strategy:** Implement weekend-specific promotions and inventory planning.

---

## Correlation Heatmap

**Insight:** Strong correlations exist between sales, orders, and engineered business metrics.

**Strategy:** Use engineered features to improve forecasting model performance.

---

# 📸 Chart Visualizations

## 1. Monthly Sales Trend

![Monthly Sales Trend](YOUR_IMAGE_LINK)

> Displays sales fluctuations across months, helping identify seasonality and business demand cycles.

---

## 2. Sales by Store Type

![Sales by Store Type](YOUR_IMAGE_LINK)

> Compares revenue generation across different store categories, highlighting top-performing business segments.

---

## 3. Region-wise Revenue Analysis

![Region-wise Revenue](YOUR_IMAGE_LINK)

> Visualizes regional performance differences and identifies high-performing regions.

---

## 4. Discount Impact on Sales

![Discount Impact](YOUR_IMAGE_LINK)

> Demonstrates how discounts influence customer purchasing behavior and overall sales revenue.

---

## 5. Orders vs Sales Relationship

![Orders vs Sales](YOUR_IMAGE_LINK)

> Shows the strong relationship between order volume and revenue generation.

---

## 6. Correlation Heatmap

![Correlation Heatmap](YOUR_IMAGE_LINK)

> Displays relationships among numerical variables and validates feature engineering effectiveness.

---

# 💼 Power BI Dashboard

An interactive **3-page Power BI dashboard** was developed to visualize retail performance, sales forecasting, customer behavior, and regional trends.

---

# 📄 Page 1 — Executive Sales Overview

![Page 1](YOUR_DASHBOARD_LINK)

### Dashboard Highlights:

* Total Revenue
* Total Orders
* Average Sales
* Revenue by Store Type
* Regional Sales Performance
* Monthly Sales Trend
* Discount vs Non-Discount Revenue

> Provides management-level insights into overall retail business performance and KPIs.

---

# 📄 Page 2 — Customer & Sales Behavior Analysis

![Page 2](YOUR_DASHBOARD_LINK)

### Dashboard Highlights:

* Orders vs Sales Analysis
* Day-wise Revenue Trends
* Holiday Impact Analysis
* Top Performing Stores
* Weekend vs Weekday Analysis
* Sales Distribution

> Analyzes customer ordering behavior and purchasing patterns to improve operational strategy.

---

# 📄 Page 3 — Regional Performance & Forecasting

![Page 3](YOUR_DASHBOARD_LINK)

### Dashboard Highlights:

* Regional Sales Mapping
* Store Performance Matrix
* Forecasting Trend Analysis
* Revenue Contribution Analysis
* High Sales Transaction Analysis

> Supports forecasting and strategic business planning through predictive insights.

---

# 🤖 Machine Learning Approach

## 🔹 Problem Type

**Supervised Learning → Regression**

---

## 🔹 Model Used

* **Random Forest Regressor**

---

## 🔹 Workflow

* Data preprocessing
* Feature encoding
* Train-test split
* Feature scaling
* Model training
* Sales prediction
* Model evaluation

---

# 📈 Model Evaluation

| Metric       | Description                  |
| ------------ | ---------------------------- |
| **MAE**      | Mean Absolute Error          |
| **MSE**      | Mean Squared Error           |
| **RMSE**     | Root Mean Squared Error      |
| **R² Score** | Model prediction performance |

👉 The Random Forest model successfully captured retail sales patterns and generated strong predictive performance.

---

# 🗄️ SQL Business Analysis

The cleaned dataset was uploaded to MySQL for business analytics.

### SQL Analysis Included:

* KPI analysis
* Revenue analysis
* Store performance analysis
* Regional analysis
* Ranking queries
* Window functions
* Trend analysis
* Contribution analysis

---

# 📊 Excel Analysis

Excel was used for initial exploration and business understanding.

### Excel Tasks Performed:

* Basic data inspection
* Data formatting
* Pivot tables
* KPI summaries
* Initial trend analysis
* Preliminary charts and business insights

---

# 🔍 Key Insights

1. Certain store types contribute significantly more revenue than others
2. Discounts positively impact sales performance and customer orders
3. Holiday seasons create major sales spikes
4. Regional sales performance varies considerably
5. Higher order volume strongly increases revenue
6. Weekend purchasing behavior differs from weekdays
7. Engineered features improved forecasting performance

---

# 🚀 Strategic Recommendations

1. Focus marketing campaigns on high-performing regions
2. Optimize discount strategies during low-sales periods
3. Increase inventory before holiday seasons
4. Monitor underperforming stores for operational improvements
5. Use forecasting insights for inventory and staffing decisions
6. Implement weekend-specific promotional campaigns
7. Expand high-performing store categories strategically

---

# 🛠️ Tools & Technologies

| Tool                       | Purpose                                   |
| -------------------------- | ----------------------------------------- |
| **Excel**                  | Initial data exploration and KPI analysis |
| **Python (Pandas, NumPy)** | Data cleaning and preprocessing           |
| **Matplotlib, Seaborn**    | Exploratory Data Analysis                 |
| **Scikit-learn**           | Machine learning modeling                 |
| **MySQL**                  | SQL business analysis                     |
| **Power BI**               | Interactive dashboard and visualization   |

---

# 📁 Project Structure

```text
Retail-Sales-Forecasting-Analytics/
│
├── notebook/
│   └── retail_sales_analysis.ipynb
│
├── data/
│   └── retail_sales_dataset.csv
│
├── sql/
│   └── retail_sales_queries.sql
│
├── dashboard/
│   ├── dashboard_page1.png
│   ├── dashboard_page2.png
│   └── dashboard_page3.png
│
├── images/
│   ├── monthly_sales_trend.png
│   ├── sales_by_store_type.png
│   ├── regional_sales.png
│   ├── discount_impact.png
│   └── correlation_heatmap.png
│
├── Retail Sales Dashboard.pbix
│
└── README.md
```

---

# 🏁 Conclusion

This project demonstrates how modern analytics tools and machine learning techniques can be combined to solve real-world retail business problems.

By integrating:

* Excel
* Python
* SQL
* Machine Learning
* Power BI

the project delivers a complete end-to-end retail analytics solution capable of generating actionable business insights and supporting data-driven decision-making.

---

# 👤 Author

## Azmat Tanveer Abbasi

🔗 GitHub: `https://github.com/azmattanveer409`

---

> ⭐ If you found this project useful, consider giving it a star on GitHub!
