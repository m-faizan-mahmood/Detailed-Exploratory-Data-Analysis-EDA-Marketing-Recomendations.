# Data Analysis and Preprocessing  

This project focuses on **data cleaning, preprocessing, exploratory data analysis (EDA), and visualization** using **Pandas** and **NumPy** to uncover key insights.  

## Data Preprocessing  

### Handling Missing Values & Outliers  
- **Numerical Data:** Imputed using the **median**.  
- **Categorical Data:** Filled using the **mode**.  
- **Outliers:** Identified and removed via **boxplots**.  
- **Type Transformations:** Ensured consistency in data formats.  

### Feature Engineering  
- **Age Extraction:** Derived from `Year_Birth`.  
- **Total Purchases:** Summed across all purchase channels.  
- **Revenue Metrics:** Computed **Revenue_Generated** and **TotalAmount_Spent**.  
- **Family Structure:** Created using `Kidhome`, `Teenhome`, and `Marital_Status`.  
- **Campaign Engagement:** `TotalCampaignsAcc` calculated from accepted campaigns.  

## Exploratory Data Analysis (EDA)  

- **Univariate Analysis:** Used **histograms** and **boxplots** to explore data distributions.  
- **Bivariate Analysis:**  
  - **Correlation Heatmaps:** Identified relationships between features.  
  - **Scatter Plots:** Examined spending patterns and engagement trends.  

## Data Visualization  

Using **Matplotlib** and **Seaborn**, the following insights were visualized:  
- **Top Campaign Performance** (bar chart).  
- **Spending by Product Category** (stacked bar chart).  
- **Age Group Spending Trends** (line chart).  
- **Product Performance** (revenue by product).  
- **Geographic Campaign Success** (map visualization).  
