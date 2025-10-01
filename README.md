# vendor-performance-analysis
Effective inventory and sales management are critical for optimizing profitability in the retail and wholesale industry. Companies need to ensure that they are not incurring losses due to inefficient pricing, poor inventory turnover, or vendor dependency. The goal of this analysis is to:

vendor-performance-analysis/
│
├── data/                   
│   ├── sales.csv
│   ├── purchases.csv
│   ├── purchase_prices.csv
│   ├── vendor_invoices.csv
│   ├── begin_inventory.csv
│   └── end_inventory.csv
│
├── notebooks/              
│   └── vendor_performance_analysis.ipynb   # Jupyter notebook with step-by-step analysis
│
├── scripts/                
│   └── data_cleaning.py    # preprocessing and filtering rules
│   └── eda_analysis.py     # exploratory data analysis code
│   └── visualization.py    # charts and plots
│
├── results/                
│   ├── correlations.png
│   ├── turnover_distribution.png
│   ├── vendor_contribution.png
│   └── profit_margin_comparison.png
│
├── README.md               
└── requirements.txt        # libraries like pandas, numpy, matplotlib, seaborn, scipy



# Vendor Performance Analysis 📊

This project explores **vendor performance, inventory efficiency, and profitability** in the retail & wholesale industry using Python.  
The dataset includes **6 files**: `sales`, `purchases`, `purchase prices`, `vendor invoices`, `begin inventory`, and `end inventory`.

---

## 📌 Objective
To analyze vendor contribution, pricing strategies, inventory turnover, and profitability to drive **data-driven recommendations** for better decision-making.

---

## 🔑 Key Analysis & Findings

### 1. Underperforming Brands
- 198 brands show **low sales but high profit margins**.
- Recommendation: Targeted promotions and optimized pricing to boost sales volume.

### 2. Vendor Contribution
- **Top 10 vendors contribute 65.69% of purchases**, indicating over-dependence.
- Recommendation: Diversify vendors to reduce supply chain risk.

### 3. Bulk Purchasing Impact
- Bulk buyers achieve **72% lower unit costs** ($10.78 vs. higher small-order prices).
- Strategy: Encourage bulk orders to sustain competitive pricing.

### 4. Inventory Turnover
- $2.71M in **unsold stock** identified.
- Recommendation: Reduce order quantities, launch clearance sales, or adjust stocking policies.

### 5. Vendor Profit Margins
- **Top vendors (sales-heavy)**: Profit margin ~31.17%.  
- **Low-performing vendors (high-margin)**: Profit margin ~41.55%.  
- Hypothesis testing confirms **significant difference** in vendor models.

---

## 📈 Visual Insights
- 📊 Correlation analysis (sales vs. purchases, turnover vs. profit)  
- 📉 Outlier detection in freight costs & purchase prices  
- 🔄 Inventory turnover distribution  
- 🏷️ Profit margin comparison: high vs. low vendors  

---

## 🛠️ Tech Stack
- **Python**: Pandas, NumPy, Matplotlib, Seaborn, SciPy  
- **Jupyter Notebook** for analysis & visualization  

---

## 📌 Recommendations
- Re-price low-sales, high-margin brands.  
- Diversify vendors to avoid over-reliance.  
- Leverage **bulk purchasing** to optimize costs.  
- Actively manage slow-moving inventory ($2.71M capital locked).  
- Improve marketing & distribution for underperforming vendors.  

---

## 🚀 How to Run
1. Clone the repository:

