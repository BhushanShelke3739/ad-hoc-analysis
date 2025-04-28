# 🛒 E-commerce Sales Analysis Report

This project explores an e-commerce sales dataset through ad-hoc analysis and professional visualizations. It highlights customer behavior, regional sales performance, discount effectiveness, product trends, and seasonal sales patterns — all compiled into a multi-page PDF report.

## 📂 Dataset Overview

Sample data format:
```
Sale ID  Product Name    Category    Price   Quantity  Customer Age  Customer Gender  Discount  Payment Method  Region          Sale Date   Total Sales
1        Smartphone      Electronics  109.89  3         57            Male             0.23      Debit Card      South America   2/13/2024    253.85
2        Smartwatch      Electronics  370.32  3         19            Female           0.23      Debit Card      South America   9/18/2023    855.44
3        Smartwatch      Electronics  1308.22 3         27            Male             0.11      PayPal          Asia            7/13/2024    3492.95
...
```

* **Total Records:** 20,000
* **Date Range:** 2023–2024
* **Regions:** Asia, South America, Africa, Europe, North America

## 📊 Key Analyses

* Customer Demographics and Spending Patterns
* Regional Sales and Discount Impact
* Top-Selling Products and Pricing Segments
* Discount Behavior and Correlation with Sales
* Monthly, Weekly, and Quarterly Seasonality Trends

## 🛠️ Visualizations

Visualization functions used:
* `plot_demographics(age_spending, gender_spending, age_category)`
* `plot_regional(region_stats, discount_effect)`
* `plot_products(top_products, price_segments)`
* `plot_discounts(discount_corr, discount_groups)`
* `plot_seasonality(monthly, dow, quarterly)`

All charts are collected into a single professional **PDF report** using `matplotlib.backends.PdfPages`.


## 📄 Output

* A multi-page **PDF report** showcasing all visualizations
* Ready-to-share insights for business decision-making or data storytelling

* ![image](https://github.com/user-attachments/assets/9b702a6a-fc50-4e21-b194-5671dfaede8f)
* ![image](https://github.com/user-attachments/assets/c929c1f7-f605-4f17-af2d-b9708eee2d85)


## 📊 Sample Visualizations

The report includes:
- Demographics analysis (age groups, gender)
- Regional performance heatmaps
- Product category breakdown
- Discount effectiveness charts
- Seasonal trends analysis

## 🔍 Key Findings

- Electronics category drives the highest revenue
- Medium discount range (11-20%) optimizes total sales
- South America region shows strongest performance
- First Quarter generates highest revenue of sales
- Customer demographics influence product preferences

## ✨ Final Note

This project focuses on **insightful exploration**, **clear visualizations**, and **professional presentation** of e-commerce sales data.

## 📚 Dependencies

- pandas
- numpy
- matplotlib
- seaborn
