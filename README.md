# 🐍 Superstore Sales Analysis | Python

## 📌 Project Overview

This project analyzes the **Sample Superstore** dataset using Python to explore sales performance, profitability, discounts, customers, products, trends, correlations, and potential outliers.

The project focuses on **exploratory data analysis (EDA)** and uses Python to identify patterns and translate them into business insights and recommendations.

## 🎯 Project Goals

The analysis focuses on:

- Understanding the structure and quality of the dataset
- Identifying missing values and duplicate records
- Exploring sales and profit distributions
- Investigating the relationship between discounts and profitability
- Comparing category and sub-category performance
- Analyzing customer profitability
- Identifying trends over time
- Measuring correlations between key variables
- Detecting potential outliers
- Developing business insights and recommendations

## 🛠️ Tools & Technologies

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Jupyter Notebook**

## 🧹 Data Quality Analysis

The dataset was first reviewed for data quality issues.

The analysis included:

- Dataset structure and data types
- Missing value checks
- Duplicate record checks
- Descriptive statistics

### Data Quality Results

- **9,994 rows**
- **21 columns**
- No missing values
- No duplicate rows

## 📊 Exploratory Data Analysis

### Sales and Profit Distribution

Histograms were used to examine the distribution of sales and profit values and identify high-value transactions and unusually large gains or losses.

### Discount and Profitability Analysis

Average profit was analyzed across different discount levels.

The analysis showed that:

- Average profit was positive at lower discount levels.
- Average profit became negative at higher discount levels.
- Higher discount levels were associated with lower profitability.

This analysis shows an association between discounts and profitability but does not prove causation.

## 📈 Category Analysis

Sales, profit, and profit margin were compared across product categories.

### Key Findings

- **Technology** generated approximately **$145.5K** in profit with a profit margin of approximately **17.4%**.
- **Office Supplies** generated approximately **$122.5K** in profit with a profit margin of approximately **17.0%**.
- **Furniture** generated approximately **$742K** in sales but only **$18.5K** in profit, resulting in a much lower profit margin of approximately **2.5%**.

This demonstrates that high sales volume does not necessarily translate into high profitability.

## 🔎 Sub-Category Analysis

The analysis identified several sub-categories with negative total profit.

The most significant profitability issue was:

- **Tables:** approximately **$207K in sales** and **-$17.7K in profit**

Tables were further analyzed by discount level, showing increasingly negative profitability at higher discount levels.

## 👥 Customer Analysis

Customer-level analysis was performed to compare sales and profitability.

One notable finding was that **Sean Miller** generated approximately **$25K in sales but had negative total profit**.

This demonstrates that sales volume alone is not sufficient to evaluate customer performance.

Loss-making customers were also analyzed to identify potential profitability issues.

## 📅 Time Series Analysis

Sales and profit were analyzed by year and month to identify trends and potential seasonal patterns.

Overall:

- Sales increased from approximately **$484K in 2014** to **$733K in 2017**.
- Profit increased from approximately **$49.5K in 2014** to **$93.4K in 2017**.
- Annual sales and profitability did not always move in the same direction.

## 🔗 Correlation Analysis

Correlation analysis was performed for:

- Sales
- Quantity
- Discount
- Profit

### Key Findings

- Sales and Profit: **0.48 correlation**
- Discount and Profit: **-0.22 correlation**
- Quantity and Profit: **0.07 correlation**

The results indicate a moderate positive relationship between Sales and Profit and a negative relationship between Discount and Profit.

Correlation indicates association and does not prove causation.

## ⚠️ Outlier Analysis

Potential outliers were identified using the **Interquartile Range (IQR)** method.

The analysis identified approximately:

- **1,167 potential Sales outliers**
- **1,881 potential Profit outliers**

These values were treated as potential statistical outliers rather than automatically being classified as errors.

One notable transaction generated approximately **$22.6K in sales but resulted in a loss of approximately $1.8K**, demonstrating that large transactions can still be unprofitable.

## 💰 Overall Business KPIs

The dataset contained:

- **Total Sales:** approximately **$2.30M**
- **Total Profit:** approximately **$286.4K**
- **Total Orders:** **5,009**
- **Total Customers:** **793**

## 💡 Key Business Insights

- High sales volume does not always result in high profitability.
- Furniture generated substantial sales but had a significantly lower profit margin than Technology and Office Supplies.
- Higher discount levels were associated with lower profitability.
- Tables, Bookcases, and Supplies generated negative total profit.
- Some high-value customers and transactions generated negative profit.
- Sales and profit generally increased over the analyzed period, although they did not always move together.

## 📌 Business Recommendations

- Review high-discount transactions, especially discounts of 30% or more.
- Investigate the profitability of Tables, Bookcases, and Supplies.
- Review high-value orders with negative profit.
- Evaluate customers and products using both sales and profitability metrics.
- Monitor Furniture profitability closely.
- Consider profitability thresholds or additional review for heavily discounted transactions.

## 🎓 Skills Demonstrated

- Python data analysis
- Pandas
- NumPy
- Matplotlib
- Exploratory Data Analysis (EDA)
- Data quality validation
- Data aggregation
- Business KPI analysis
- Profitability analysis
- Correlation analysis
- Outlier detection
- Data visualization
- Business insights and recommendations

## 📁 Project Structure

```text
python-superstore-analysis/
│
├── README.md
└── Superstore_Sales_Analysis_Python.ipynb
