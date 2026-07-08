# Zomato Dataset Analysis

Analysis of restaurant and review data to extract insights on ratings,
cuisines, location preferences, and factors affecting ratings.

## ⚠️ Data Note
The original CSV files provided for this task contained only header rows
with no actual data. To complete the analysis, a realistic **synthetic
Zomato-style dataset** (1,500 Bangalore restaurants) was generated with
the same schema. The full pipeline can be re-run unchanged on the real
Kaggle dataset: https://www.kaggle.com/datasets/bhanuprataphbiswas/zomato

## Files
- **Zomato_Dataset_Analysis.ipynb** — Full notebook: data cleaning,
  exploration, and visualizations (heatmaps, wordclouds, charts)
- **Zomato_Analysis_Report.pdf** — PDF report with key findings and
  5 recommendations for a food-delivery platform
- **zomato_synthetic.csv** — The dataset used in the analysis

## Key Findings
- Table booking availability correlates with higher ratings (+0.18)
- Online ordering correlates with higher ratings (+0.12)
- Price and rating are only weakly correlated (r = 0.20)
- Street Food, Chinese, and Andhra cuisines rate highest on average
- HSR Layout and MG Road combine strong ratings with good restaurant volume
