# 📊 Customer Lifetime Value (CLV) Analysis

This project simulates the work of a data analyst supporting marketing and customer success teams. It aims to segment customers based on their CLV and propose targeted strategies to improve retention and ROI.

---

## 🎯 Project Objective

- Calculate Customer Lifetime Value (CLV) using RFM metrics  
- Segment customers into value tiers using quantiles  
- Visualize behavior trends across segments  
- Recommend retention strategies for each segment

---

## 🗂 Folder Structure

CLV-project/
├── data/                         # All data files
│   ├── raw/                      # Original dataset
│   │   └── online_retail.csv
│   └── cleaned/                  # Cleaned dataset with CLV
│       └── clv_cleaned.csv
├── notebooks/                   # Jupyter Notebook with analysis
│   └── clv_analysis.ipynb
├── report/                      # Summary slide deck (PDF)
│   └── clv_summary.pdf
├── dashboards/                  # Tableau dashboard (optional)
│   └── clv_dashboard.twbx
├── visuals/                     # Optional: saved charts
│   ├── clv_histogram.png
│   ├── clv_segment_chart.png
│   └── clv_recency_boxplot.png
├── README.md                    # Project documentation


---

## 🧰 Tools Used

- 🐍 Python (Pandas, NumPy, Seaborn, Matplotlib)
- 📓 Jupyter Notebook
- 📊 Excel (for initial cleanup)
- 📈 Tableau (for CLV dashboards)

---

## 📈 Key Insights

- CLV distribution is **right-skewed** — most customers have low CLV
- High CLV customers are more **frequent and recent** buyers
- Clear trends in recency and frequency across segments

---

## 💡 Segment-Specific Recommendations

| Segment     | Strategy                                  |
|-------------|--------------------------------------------|
| 🔴 Low      | Re-engagement campaigns, discount offers   |
| 🟠 Mid-Low  | Loyalty programs, referrals                |
| 🟡 Mid-High | Upselling, product bundling               |
| 🟢 High     | VIP experience, early access, premium care |

---

