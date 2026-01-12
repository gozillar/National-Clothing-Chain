# Market Analysis & Targeted Marketing Strategy
## Project Overview
This project presents a market analysis and customer segmentation study for a fictional national online clothing retailer in the US. The objective was to design a data-driven targeted marketing strategy by analyzing customer behavior, demographic data, and product performance.
Using Microsoft Power BI, I integrated multiple real-world datasets, performed statistical analysis, and built interactive dashboards to uncover patterns that inform which products should be marketed to which customers and in which locations.
This project demonstrates skills in data modeling, DAX, Power Query (M), statistical analysis & regression, and business analytics, marketing strategy & storytelling.

## Business Problem
Sales for the national clothing chain have stagnated. The company wants to:
- Re-engage lost customers
- Advertise specific products to specific customers
- Focus marketing spend on high-impact geographic locations

The products under consideration:
- Shirt – $25
- Sweater – $100
- Leather Bag – $1,000


The challenge was determining who to target, what to advertise, and where—using data.

## Data Sources
This analysis integrates multiple datasets:
1. U.S. Census Bureau Data (Average household income, Population by state, Geographic and demographic indicators)
2. Customer Data (Customer ID and name, Age and location, Purchase history)
3. Business & Product Data (Product prices, Customer ratings, Product return rates)

These datasets were cleaned, transformed, and modeled using Power Query (M) and connected through a relational data model in Power BI.


## Key Analyses Performed
### Sales vs. Income Correlation
- R² = 0.78
- Strong positive correlation between average income and average sales
- Indicates higher-income regions generate higher customer spending

### Customer Ratings vs. Return Rate
- R² = 0.69
- Moderate negative correlation
- Higher-rated products are returned less frequently

### Predictive Modeling
- Linear regression formulas were created to predict customer income from sales behavior
- Census income data was used to infer missing customer income values

### Highest Predicted Income Customer
- Jon Little (Age 38, Illinois)
- Customer ID: JLit30836

### Product Marketing Recommendations
| Income Segment | Customers | Avg Sales | Recommended Products |
| -------------- | --------- | --------- | -------------------- |
| < $100,000     | 707       | $123.47   | Shirt                |
| $100k–$150k    | 216       | $507.83   | Sweater, Shirt       |
| $150k–$200k    | 56        | $954      | Sweater, Shirt       |
| $200k–$250k    | 18        | $1,417    | Leather Bag, Sweater |
| > $250k        | 3         | $3,366    | Leather Bag          |

### Final Recommendation
- Shirt ($25) should be advertised the most (Largest customer segment, Best price-to-volume fit)
- Sweater ($100) is a strong secondary product
- Leather Bag ($1,000) should be highly targeted to elite, high-income customers

### Customer Demographics Insight
- Total customers analyzed: 1,000
- California has the highest customer concentration (150 customers)
- Majority of California customers earn less than $100,000 and fall within the 40–49 age range


## Power BI Dashboard Features
The Power BI report includes:
- Histogram – Income distribution
- Heat Map – Household income by location
- Scatter Plot with Trendline – Income vs. Sales correlation
- KPI Card – R² correlation values
- Cross-filtering between visuals
- Custom DAX measures and regression calculations


## Conclusion
This project demonstrates how data analytics can directly inform marketing strategy, helping businesses allocate resources efficiently and improve customer targeting. It showcases my ability to work with real-world data, apply statistical reasoning, and deliver actionable insights through professional-grade Power BI dashboards.
