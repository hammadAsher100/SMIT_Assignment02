# SMIT_Assignment02

🎯 Objectives

This project aims to:

- Load and clean the dataset
- Generate univariate and multivariate data distributions
- Provide a dataset overview and statistical summary
- Perform detailed EDA
- Present visual insights
- Summarize findings in a clear and actionable way

🧼 Data Cleaning Performed

- Removed duplicate rows
- Checked for missing values
- Converted date columns to datetime format
- Corrected data types (e.g., postal codes)
- Ensured consistency in categorical fields

📊 Visualizations Included

The following plots were used to explore the data:
1.Histogram (Sales)

2.KDE Plot (Profit)

3.Count Plot (Segment)

4.Box Plot (Profit by Category)

5.Violin Plot (Sales by Category)

6.Scatter Plot (Sales vs Profit)

7.Line Plot (Sales over Time)

8.Bar Plot (Profit by Region)

9.Pair Plot (Sales, Quantity, Discount, Profit)

10.Correlation Heatmap

11.Joint Plot (Sales vs Profit)

These visualizations help identify trends, patterns, and relationships within the dataset.

📈 Summary of Insights

- Sales distribution is right-skewed, dominated by low-value transactions.
- Many orders result in negative profit, signaling loss-making products or discount misuse.
- Higher discounts correlate with lower profits.
- Technology drives the highest sales; Furniture shows unstable profitability.
- Popular products include Binders, Papers, Phones, and Chairs.
- Consumer segment generates the most revenue.
- West and East regions outperform others in sales.
- States like California and New York are consistently profitable.
- Improving Furniture margins and controlling discounts can boost profitability.

🛠 Tools & Libraries

This project uses:

- Python 3
- pandas 
- numpy 
- matplotlib 
= seaborn 
