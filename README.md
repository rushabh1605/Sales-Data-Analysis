#Sales Data Analysis

This project explores comprehensive sales data from an online retail company to derive insights such as sales performance by month, top-selling products, popular purchase combinations, and optimal advertising times.

The analysis was performed using `pandas`, `matplotlib`, and Python’s built-in tools to clean, manipulate, and visualize data from multiple months of sales.

---

## Repository Structure
```bash
├── Sales Analysis.ipynb              # Main analysis notebook
├── Sales_Data/                       # Raw monthly sales data files
├── all_data.csv                      # Combined dataset
├── LICENSE                           # MIT License
└── README.md                         # Project documentation
```
---

## Objectives

- Combine and clean multiple CSV files containing monthly sales data.
- Derive new features (month, city, hour, total sales).
- Perform exploratory data analysis to answer key business questions.

---

## Key Features

- **Best Month for Sales**: Identified based on total revenue.
- **Top Performing Cities**: Based on total sales.
- **Optimal Advertisement Time**: Based on order volume per hour.
- **Most Common Product Pairs**: Frequently bought together items.
- **Top-Selling Products**: Based on quantity sold and price comparison.

---

## Sample Visualizations

- Bar chart of monthly sales
- Sales by city
- Order volume by hour
- Quantity vs. price plots per product

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/rushabh1605/Sales-Data-Analysis.git
cd Sales-Data-Analysis
```

 2.	Install dependencies:
```bash 
pip install pandas matplotlib
```
3.	Run the Jupyter Notebook:
```bash
jupyter notebook "Sales Analysis.ipynb"
```
## Insights Extracted

- **December** had the highest total sales.  
- **San Francisco, CA** led in sales volume, followed by **New York City, NY**.  
- Peak purchase hours were **11 AM** and **7 PM**, ideal for ad placements.  
- Products often bought together included:
  - *iPhone & Lightning Charging Cable*
  - *Google Phone & USB-C Charging Cable*
- **AAA and AA batteries** sold the most due to their low price and high necessity.

---

## Contact

**Rushabh Thakkar**

🔗 [LinkedIn](https://www.linkedin.com/in/rushabhthakkar)  
🔗 [GitHub](https://github.com/rushabh1605)

