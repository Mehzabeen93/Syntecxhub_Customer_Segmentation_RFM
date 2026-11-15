# Customer Segmentation using RFM Analysis

## Project Overview
This project focuses on customer segmentation using RFM (Recency, Frequency, Monetary) Analysis. The objective is to understand customer purchasing behaviour, identify valuable customers, recognize customers at risk of leaving, and recommend targeted marketing strategies.

## Project Objectives
- Clean and prepare transactional retail data.
- Calculate Recency, Frequency, and Monetary values.
- Assign RFM scores to customers.
- Segment customers based on purchasing behaviour.
- Analyze customer segments and sales patterns.
- Provide actionable marketing recommendations.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset
**Online Retail Dataset** from the UCI Machine Learning Repository.

The dataset contains online retail transactions, including invoice numbers, product descriptions, quantities, invoice dates, prices, customer IDs, and countries.

## Project Methodology

1. **Data Understanding:** Explored the dataset structure, columns, data types, and missing values.
2. **Data Cleaning:** Handled missing customer IDs, duplicate records, cancelled invoices, negative quantities, and invalid prices.
3. **Feature Engineering:** Calculated sales using Quantity × UnitPrice.
4. **RFM Calculation:** Calculated:
   - Recency: Days since the customer's last purchase.
   - Frequency: Number of distinct invoices.
   - Monetary: Total amount spent by the customer.
5. **Customer Segmentation:** Assigned RFM scores and grouped customers into meaningful segments.
6. **Exploratory Data Analysis:** Analyzed customer segments, revenue, products, countries, and sales trends.
7. **Business Recommendations:** Suggested targeted marketing strategies for different customer groups.

## Customer Segments
- Champions
- Loyal Customers
- Potential Loyalists
- Recent Customers
- At Risk
- Lost Customers
- Others

## Key Business Insights
- Identified 4,338 unique customers after data cleaning.
- Analyzed customer purchasing frequency and spending behaviour.
- Identified high-value customers and customers who may need re-engagement.
- Examined monthly, quarterly, and yearly sales trends.
- Identified top-performing products and countries by revenue.

## Business Recommendations
- Offer VIP rewards to Champions.
- Provide loyalty benefits to regular customers.
- Encourage repeat purchases from Recent Customers.
- Send personalized offers to Potential Loyalists.
- Use win-back campaigns for At Risk and Lost Customers.

## How to Run the Project
1. Clone or download this repository.
2. Install the required Python libraries:
   `pip install pandas numpy matplotlib seaborn openpyxl`
3. Download the Online Retail dataset from the UCI Machine Learning Repository.
4. Open `customer_segmentation.ipynb` in Jupyter Notebook or VS Code.
5. Update the dataset file path if necessary.
6. Run the notebook cells in order.

## Project File
- `customer_segmentation.ipynb`: Complete Python code, analysis, visualizations, and recommendations.

## Skills Demonstrated
Python, Data Cleaning, Data Preprocessing, Exploratory Data Analysis (EDA), Pandas, NumPy, Data Visualization, RFM Analysis, Customer Segmentation, and Business Insights.
