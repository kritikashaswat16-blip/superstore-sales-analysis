# 🛒 Superstore Sales Analysis

Analysis of retail sales data to find which products, categories, regions, customer segments, and time periods drive sales, and where the growth opportunities are.

## 📌 Business Problem
A retail company wants to understand where its sales come from so it can plan marketing, stock, and expansion. This project answers:
1. Which categories and sub-categories sell the most?
2. Which regions and states perform best?
3. How do sales change over time (growth and seasonality)?
4. Who are the top products and customers?
5. Which customer segments and ship modes matter most?

## 📂 Dataset
- **Source:** Superstore Sales dataset (Kaggle)
- **Size:** ~9,800 rows, 18 columns (orders, customers, products, location, sales)
- **File:** `data/superstore.csv`

## 🛠 Tools Used
Python · pandas · matplotlib · seaborn · Jupyter Notebook (VS Code)

## 🧹 Data Cleaning
- Removed duplicate rows
- Converted `Order Date` and `Ship Date` to datetime (day-first format)
- Dropped rows with invalid dates
- Created `Year`, `Month`, and `Shipping Days` columns

## 🔍 Key Insights
> Replace these with your real findings after running the notebook.

1. **Category:** *(top category and its share of sales)*
2. **Region:** *(best and weakest region)*
3. **Trend:** *(growth per year and seasonal peak months)*
4. **Customers and products:** *(top products/customers, any concentration)*
5. **Segment:** *(which segment contributes the most)*

### Charts
![Category](images/q1_category.png)
![Region](images/q2_region.png)
![Monthly Trend](images/q3_monthly_trend.png)

## ✅ Recommendations
1. Increase stock and marketing for top categories and sub-categories.
2. Invest in the strongest region and study the weakest one.
3. Plan campaigns and inventory before the seasonal peak.
4. Reward top customers and the leading segment with loyalty offers.

## ▶️ How to Run
```bash
git clone https://github.com/<your-username>/superstore-sales-analysis.git
cd superstore-sales-analysis
pip install -r requirements.txt
jupyter notebook notebooks/superstore_analysis.ipynb
```

## 👤 Author
**Your Name** · [LinkedIn](https://linkedin.com/in/your-profile) · [GitHub](https://github.com/your-username)
