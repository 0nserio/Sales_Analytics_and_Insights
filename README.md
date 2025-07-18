# Retail Sales Data Analysis 2024

A comprehensive analysis of retail sales performance across multiple regions and product categories in Kenya, focusing on data cleaning, exploratory analysis, and actionable business insights.

## Project Overview

This project analyzes retail sales data from 2024 to understand performance trends across different regions (Nairobi, Mombasa, Nakuru, Kisumu) and product categories (Electronics, Home & Living, Groceries, Clothing). The analysis provides insights to support strategic decision-making and optimize future performance.

## Dataset

- **Source**: retail_sales_data.csv
- **Size**: 500 transactions
- **Columns**: Store ID, Date, Total Sales, Region, Product Category, Units Sold
- **Time Period**: January 2024 - December 2024

## Key Findings

### Regional Performance
- **Nairobi** leads with KES 710,256.84 in total sales
- **Mombasa** follows closely with KES 710,064.10
- Strong market presence across all four regions

### Product Category Performance
- **Home & Living** generates the highest category sales
- **Electronics** shows the lowest performance, indicating potential for improvement
- Average monthly sales: KES 221,521.49

### Seasonal Trends
- **Peak month**: August (highest sales)
- **Low period**: July (significant dip)
- Notable recovery patterns in May and November

## Technical Approach

### Data Cleaning
- Verified data integrity (no missing values or duplicates)
- Standardized date formats and column structures
- Performed statistical validation

### Analysis Methods
- Descriptive statistics and trend analysis
- Regional and categorical performance comparison
- Time series analysis for seasonal patterns

### Visualizations
- Bar charts for category performance comparison
- Line graphs for monthly sales trends
- Clean, professional styling with seaborn/matplotlib

## Tools & Libraries

```python
pandas          # Data manipulation and analysis
matplotlib      # Data visualization
seaborn        # Statistical data visualization
numpy          # Numerical computing
```

## Business Recommendations

1. **Leverage Nairobi's Strong Performance**: Increase inventory and marketing focus in the top-performing region
2. **Address Electronics Underperformance**: Review pricing and marketing strategies for the electronics category
3. **Seasonal Planning**: Align inventory and promotional activities with identified peak/low periods
4. **Mid-year Strategy**: Investigate causes of July sales dip and implement targeted interventions



## Getting Started

1. Clone this repository
2. Install required dependencies: `pip install pandas matplotlib seaborn numpy`
3. Run the analysis script: `python sales_analysis.py`

## Future Enhancements

- Customer segmentation analysis
- Predictive modeling for sales forecasting
- Interactive dashboard development
- Advanced time series analysis

---

*This analysis was conducted as part of a data analyst mentorship by Phoenix Ke Analytics interview project, demonstrating skills in data cleaning, exploratory analysis, and business insight generation.*
