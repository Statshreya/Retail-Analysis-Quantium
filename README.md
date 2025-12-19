# Quantium Retail Strategy and Analytics - Task 1
This project is part of the Quantium Virtual Internship, focusing on Retail Strategy and Analytics. The primary goal is to analyze customer purchase behavior and transaction data to provide actionable insights for a retail client, specifically focusing on the chips category.

# Table of Contents
1.Project Overview

2.Dataset

3.Key Analysis Steps

4.Installation & Tools

5.Insights & Findings

# Project Overview
The analysis explores customer segments and their purchasing patterns to identify which segments contribute most to chip sales and how their preferences differ. This involved extensive data cleaning, exploratory data analysis (EDA), and customer segmentation.

# Dataset
The project utilizes two main datasets:

1.QVI_purchase_behaviour.csv: Contains customer information, including loyalty card numbers, life stages, and premium statuses.

2. QVI_transaction_data.xlsx: Contains transaction records, including dates, store numbers, product names, quantities, and total sales.

# Key Analysis Steps
1.Exploratory Data Analysis (EDA):

Converted date formats and cleaned product names.

Filtered the dataset to focus exclusively on chip products (removing salsa dips).

Identified and removed outliers, such as a customer making unusually large commercial-sized purchases.

2.Data Merging: Combined transaction and customer data to create a unified dataset for segment-based analysis.

3.Metrics Calculation: Analyzed total sales, number of customers, and average transactions per customer across different segments (e.g., "Mainstream Young Singles/Couples").

4.Market Basket Analysis: Used the Apriori algorithm and association rules to find product affinities within specific customer segments.

# Installation & Tools
To run the analysis locally, ensure you have the following Python libraries installed:


pip install pandas numpy matplotlib mlxtend sklearn xlrd
# Pandas & Numpy: For data manipulation and numerical analysis.

# Matplotlib: For data visualization.

# mlxtend: For Market Basket Analysis (Apriori and Association Rules).

# Scikit-learn: For data preprocessing.

# Insights & Findings
1.Top Segment: "Mainstream Young Singles/Couples" and "Mainstream Midage Singles/Couples" are significant contributors to sales.

2.Brand Preference: Kettle chips are consistently popular across most segments.

Packet Size: The 175g packet size is the most frequently purchased across many customer segments.

Product Placement Strategy: Specific brands like Tyrells and Twisties show higher affinity with Mainstream Young Singles/Couples, suggesting they should be placed near high-traffic brands like Kettle to increase visibility and sales.
