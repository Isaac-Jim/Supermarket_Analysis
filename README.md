
# Supermarket Sales Analysis
This project analyzes supermarket sales data to visualize key business metrics such as sales trends, customer behavior, and product performance across multiple cities. Using Python for data manipulation and visualization, this analysis provides actionable insights that can inform strategic business decisions.

## Project Overview

The primary objective of this project is to:
- Explore sales trends over time, by day of the week, and by product line.
- Identify top-performing products and customer preferences, such as preferred payment methods by city and product type.
- Analyze gross income performance across various departments and locations, providing key insights for business optimization.

The analysis uses Python libraries such as **pandas**, **matplotlib**, and **seaborn** to achieve these goals.

## Key Insights

### 1. Sales Trends by Day of the Week

Different cities exhibited unique sales patterns, shedding light on consumer behavior and potential market opportunities:
- **Yangon**: Sales were steady throughout the week, with a slight dip on Fridays and a peak on Saturdays, underscoring the importance of weekend sales in driving revenue.
- **Naypyitaw**: This city showed higher volatility, with peaks on Tuesdays and Fridays, suggesting that midweek and end-of-week promotions could be especially effective.
- **Mandalay**: The most unpredictable of the three cities, Mandalay saw major spikes on Wednesdays and Fridays, followed by a significant drop on Sundays. This suggests that local market factors play a significant role in driving sales in Mandalay.

### 2. Preferred Payment Methods by Product

Identifying payment preferences by city and product category provided key insights into customer behavior:
- In **Mandalay**, credit cards were the most popular payment method for food and beverage purchases. This insight could help tailor marketing strategies and promotions to boost customer engagement by aligning with payment preferences.

### 3. Gross Income by Product Line

Analysis of gross income across different product lines uncovered which departments were most profitable:
- By identifying which product lines generate the highest and lowest gross income, the business can focus on strategic discounts or promotions during peak sales periods to optimize revenue further. This kind of data-driven decision-making can enhance the company's overall profitability.

### 4. Top 5 Sales Dates

A closer look at the top 5 sales dates revealed contributing factors such as product ratings, unit prices, quantities sold, and marketing campaigns. Conversely, the five lowest-performing dates suggest potential market conditions or product shortages that warrant further investigation.

### 5. Sales Trends Over Time

Analyzing sales trends revealed seasonal patterns, such as a spike in early April 2019, which may correlate with regional events or marketing campaigns. These insights present opportunities to refine sales strategies based on region-specific dynamics.

### 6. Data Correlation Insights

A detailed correlation analysis revealed:
- A strong positive correlation between total sales and quantity sold, showing that higher volume sales drive revenue.
- A linear relationship between cost of goods sold (COGS) and total sales, suggesting efficient scaling of operations with increasing sales.
- Gross income trends aligned with both sales quantities and COGS, indicating that product volume drives profitability.
- Interestingly, no clear relationship between product ratings and sales was found, which may imply that other factors like customer loyalty, promotions, or availability are more influential in driving sales.

### 7. Unit Price vs. Gross Income

The relationship between unit price and gross income revealed that higher-priced items do not always generate more income. Instead, lower-priced, high-volume items contribute significantly to gross income, an insight that can help guide pricing strategies.

### Additional Insights

This project has enabled a deeper understanding of customer purchasing patterns, sales cycles, and profitability, highlighting critical areas for business growth and operational improvement. The analysis also underscores the importance of regional variations in sales behavior, suggesting that city-specific strategies could further optimize revenue.

## Technical Features

1. **Data Cleaning and Preparation**
   - Handled missing data, duplicates, and ensured consistency across the dataset.
   - Checked for and removed any duplicate rows (`df.duplicated().sum()`) and ensured no missing values (`df.isnull().sum()`).

2. **Data Exploration and Visualization**
   - Used **pandas** for data manipulation and aggregation to uncover key insights.
   - Created detailed visualizations using **matplotlib** and **seaborn** to illustrate sales patterns, gross income trends, and payment preferences.
   - Generated heatmaps, bar charts, and line graphs to provide a visual narrative of the data.

3. **Correlation Analysis**
   - Analyzed relationships between key metrics such as total sales, quantity sold, and gross income to understand revenue drivers.
   - Evaluated the relationship between cost of goods sold (COGS) and total sales, which revealed the proportional scaling of sales operations.

## Technologies Used

- **Python**: Core language for data analysis.
- **pandas**: Data manipulation and aggregation.
- **matplotlib** & **seaborn**: Data visualization.
- **Jupyter Notebook**: An interactive environment combining code, documentation, and analysis.

## How to Run the Project

1. **Clone the repository**:
   ```
   git clone https://github.com/Isaac-Jim/Supermarket_Analysis.git
   ```
2. **Install necessary libraries**:
   ```
   pip install -r requirements.txt
   ```
3. **Run Jupyter Notebook**:
   - Open the notebook and execute the cells to run the full analysis and visualize the findings.

## Conclusion

This supermarket sales analysis uncovers critical insights that could enhance business decision-making, optimize promotional strategies, and better understand customer preferences. The project demonstrates strong analytical skills in data manipulation, visualization, and statistical analysis, offering valuable insights into both sales performance and business operations.

<img width="971" alt="Screenshot 2024-09-25 at 09 16 27" src="https://github.com/user-attachments/assets/5dff51b5-cc79-431a-aa88-2c9f527099d6">
<img width="934" alt="Screenshot 2024-09-25 at 09 23 18" src="https://github.com/user-attachments/assets/d237810c-d07b-411d-9e03-2e66ff38cf01">
<img width="923" alt="Screenshot 2024-09-25 at 09 54 09" src="https://github.com/user-attachments/assets/e7046d75-6f2f-4156-aecd-248809fec0df">
<img width="1157" alt="Screenshot 2024-09-25 at 10 06 08" src="https://github.com/user-attachments/assets/bace39f7-b381-46a5-be7a-cf6626b12102">
<img width="985" alt="Screenshot 2024-09-25 at 11 54 23" src="https://github.com/user-attachments/assets/a5e19b29-f979-4f55-9dd9-5feb309da61c">
<img width="936" alt="Screenshot 2024-09-25 at 15 30 10" src="https://github.com/user-attachments/assets/6147649f-e000-4c64-ba6d-3dd48e21a282">
<img width="982" alt="Screenshot 2024-09-27 at 16 36 38" src="https://github.com/user-attachments/assets/b6612f56-c349-40f1-b051-fabb5cc99f7b">
<img width="1073" alt="Screenshot 2024-09-28 at 09 08 57" src="https://github.com/user-attachments/assets/251b6323-758e-4b4c-855e-544e46e26c78">

