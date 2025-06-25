# Real-world-E-commerce-data-analysis

This is a data analysis project on data released by Olist, an ecommerce site of Brazil. This project is magnificent compilation of things like, understanding business problem, formulating it to ML problem, looking things with business eye and from various perspectives, EDA (exploratory data analysis), statistics, visually appealing charts, and drawing some actionable insights. 

Data is available in 9 different CSVs with information of over 100K orders. I merged these datasets, dealt with missing values, extracted some useful features out of existing ones, looked upon target feature by the lens of univariate, bivariate, and multivariate analyses, and drew actionable insights.

Data:
  - Datasets (9 files): customers data, orders data, payment, reviews, orders, products, sellers, and product category name translation data.
  - File format: CSV (all files)
  - Records: Approximately 100K

## Key techniques
- Univariate analysis:
  - Distributions of numeric and categorical features, along with split on target.
  - Elucidated using plot like bar chart, pie chart, linechart, Pareto chart, etc.
- Bivariate analysis:
  - Correlation matrix for numerical features like price, freight, payment, product dimesnions, etc.
  - Identifying trends using scatter plot and Pairplot.
- RFM analysis
  - Based on recency, frequency, and monetary gave scores to customers, grouped into several clusters. Based on scores we can address those customers.

## Outcomes
- This Exploratory Data Analysis (EDA) gives a clear grasp of the data's layout, trends, customer satisfaction, etc.
- Based on what's happening, business can take some decisions based on extracted insights.
- If we were to built ML model, things we need to be cautious about, such as: imbalance data, important features, etc. are clearly mentioned.

## Technologies
- Language: 100% Python
- Libraries- Pandas, Numpy, Matplotlib, seaborn, etc.
- Platform- Jupyter notebook 
