# 📈 Marketing Channel Performance Analysis

## Project Overview

This project analyzes a marketing dataset to evaluate the performance of different acquisition channels based on three key business metrics:

- **Best Performing Channel** (Highest ROI)
- **Most Cost-Effective Channel** (Lowest Average CAC)
- **Highest Revenue Channel**

The goal is to identify which channels deliver the most value and guide future marketing strategies.

---

## Dataset Description

The dataset includes the following columns:

| Column Name | Description |
|:------------|:------------|
| **Marketing_Channel** | The marketing channel used to acquire customers (e.g., Social Media Ads, Email Marketing, Online Ads) |
| **Average_CAC (USD)** | Average Customer Acquisition Cost (USD) per channel |
| **Total_Revenue (USD)** | Total revenue generated from each channel |
| **ROI** | Return on Investment (Revenue / Spend) for each channel |

---

## Key Findings

- 🚀 **Best Performing Channel (Highest ROI)**: **Social Media Ads**  
- 💸 **Most Cost-Effective Channel (Lowest CAC)**: **Email Marketing**  
- 💰 **Highest Revenue Channel**: **Online Ads**

---

## How to Run the Project

You can run the analysis easily in **Google Colab**:

1. Upload the dataset (`marketing_channel_summary.csv`) to your Colab session.
2. Load the data using `pandas`.
3. Perform simple data analysis and visualization.
4. Summarize insights.

Example code snippet:

```python
import pandas as pd

# Load dataset
df = pd.read_csv('marketing_channel_summary.csv')

# Display dataset
print(df)

# Find best channels
best_roi = df.loc[df['ROI'].idxmax(), 'Marketing_Channel']
lowest_cac = df.loc[df['Average_CAC (USD)'].idxmin(), 'Marketing_Channel']
highest_revenue = df.loc[df['Total_Revenue (USD)'].idxmax(), 'Marketing_Channel']

print(f"Best Performing Channel (Highest ROI): {best_roi}")
print(f"Most Cost-Effective Channel (Lowest CAC): {lowest_cac}")
print(f"Highest Revenue Channel: {highest_revenue}")
```

---

## Skills Demonstrated

- Data Manipulation with **pandas**
- Business Metrics Analysis (ROI, CAC, Revenue)
- Google Colab Environment Usage
- GitHub Project Organization
- Data-Driven Insights for Marketing Strategy

---

## About Me

👋 Hi, I'm **Ali Malek**, a Python Developer passionate about data analysis and business intelligence!  
Feel free to connect with me:

- [GitHub Profile](https://github.com/alimalek80)
- [LinkedIn Profile](https://linkedin.com/in/ali-malek-work/)
- 📧 Email: alimalekwork@gmail.com

---

## License

This project is open-source and free to use. 🚀
