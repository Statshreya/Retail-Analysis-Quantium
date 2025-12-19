# Quantium Retail Strategy and Analytics - Data Analytics Project

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Library-Pandas-orange.svg)](https://pandas.pydata.org/)
[![Statistical Analysis](https://img.shields.io/badge/Focus-Statistical%20Analysis-green.svg)]()

## 📌 Project Overview
This project was completed as part of the **Quantium Virtual Internship**. It simulates a real-world retail consulting engagement where I acted as a Data Analyst to provide insights into customer segments and evaluate the success of store trials for a large supermarket client.

The analysis is split into two core tasks:
1. **Task 1: Customer Insights & Segmentation** - Identifying "Who" is buying and "What" their preferences are.
2. **Task 2: Experimentation & Store Trial Analysis** - Testing "If" store layout changes actually increased sales.

---

## 📊 Task 1: Customer Insights & Segmentation
**Goal:** Examine transaction data to identify high-value customer segments and chip purchasing patterns.

### Methodology:
- **Data Cleaning:** Handled Excel date formats, removed non-chip products (salsa), and extracted weights/brands from text descriptions.
- **Outlier Removal:** Filtered out bulk-buying commercial customers to focus on general retail behavior.
- **Metric Analysis:** Calculated Total Sales, Customer Counts, and Average Transactions per segment.
- **Market Basket Analysis:** Applied the **Apriori Algorithm** to find brand affinities.

### Key Insights:
- **Primary Segment:** "Mainstream Young Singles/Couples" and "Mainstream Midage Singles/Couples" are the biggest drivers of sales.
- **Affinity:** Mainstream Young Singles/Couples are **23% more likely** to purchase Kettle chips and show a strong preference for 175g packets.
- **Recommendation:** Increase visibility of niche brands like *Tyrells* by placing them near high-traffic *Kettle* products to target the "Mainstream" demographic.



---

## 🧪 Task 2: Experimentation & Store Trial Analysis
**Goal:** Evaluate the impact of new store layouts in Trial Stores 77, 86, and 88 by comparing them against matched Control Stores.

### Methodology:
- **Control Store Selection:** Used correlation and magnitude distance metrics to find stores with similar sales volume and customer traffic during the pre-trial period.
- **Hypothesis Testing:** Conducted **Independent T-Tests** to compare trial month performance against the control stores.
- **Assessment:** Measured the percentage change in Revenue and Customer Counts.

### Key Findings:
- **Success:** Stores **77** and **86** saw a statistically significant increase in both sales and customers during the trial.
- **Inconclusive:** Store **88** did not show a consistent significant uplift, suggesting potential differences in implementation or local store factors.
- **Conclusion:** The trial was successful overall, and a rollout of the new layout is recommended based on the performance of stores 77 and 86.



---

## 🛠️ Tech Stack & Libraries
- **Language:** Python
- **Data Manipulation:** `pandas`, `numpy`
- **Visualization:** `matplotlib`, `seaborn`
- **Statistics:** `scipy.stats` (T-Tests)
- **Association Rules:** `mlxtend` (Apriori & Association Rules)

---

## 📂 File Structure
- `QVI_task1.ipynb`: Notebook for data cleaning and segmentation analysis.
- `QVI_task2.ipynb`: Notebook for control store matching and trial evaluation.
- `QVI_transaction_data.xlsx`: Raw transaction records.
- `QVI_purchase_behaviour.csv`: Customer segment metadata.

---

## 🚀 How to Run
1. Clone the repo:
   ```bash
   git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
