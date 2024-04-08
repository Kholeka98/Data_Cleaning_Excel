# Exploratory Data Analysis

### Project Objective 
The primary objective of this project is to provide actionable insights to the marketing team regarding sales performance across various locations and product types. By addressing key questions such as revenue generation per location, the correlation between price and product sales across different product types, and identifying the highest revenue-generating product types, this initiative aims to empower the marketing team to optimize revenue streams effectively. Ultimately, the project seeks to facilitate informed decision-making and the formulation of targeted strategies to enhance overall sales performance and maximize revenue potential.

### Data Source
Supply chain dataset URL:(https://www.kaggle.com/datasets/amirmotefaker/supply-chain-dataset)

### Tools
Python

### Data Understanding
In the initial data understanding step, we performed the following tasks:
- Data Loading and Inspection.
- Determined the total number of observations and fields.
- Analyzed the statistical characteristics of the numeric columns.
- Determined the data types of the columns.
- Calculated the total number of  null values.

 ### Data Preparation
 As part of preparing our dataset, we executed the following tasks:
 - Dropped irrelevant columns and rows to avoid cleaning columns that are irrelevant to our analysis.
 - Identified and removed duplicate rows.
 - Renamed columns and included units  where necessary.

### Data Visualizations
We utilized data visualization to comprehend features by creating bargraphs and scatterplots, and boxplots aiding in addressing the specified inquiry. 

### Results
1. Based on the analysis, we observe that the revenue generated from product sales is distributed as follows:
- 17.76% from Bangalore,
- 20.62% from Chennai,    
- 14.03% from Delhi,         
- 23.73% from Kolkata, and   
- 23.85% from Mumbai.     

2. Upon analyzing the relationship between the number of goods sold and the price of haircare and skincare products, it is evident that there is no clear correlation. This suggests that the number of goods sold is not significantly influenced by the price of these products.  
Contrastingly, when examining cosmetics products, negative relationship between sales volume and pricing emerges. Specifically, as the price of cosmetics increases, the corresponding number of goods sold decreases. This inverse correlation implies that higher pricing negatively impacts the demand for cosmetics products, leading to reduced sales volumgory. These insights could inform pricing strategies and marketing efforts aimed at maximizing sales in the respective product categories.
   
4. It was inferred that overall, skincare generates the highest revenue, accounting for 41.83 % of the total revenue.

