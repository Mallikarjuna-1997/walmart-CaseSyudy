# Walmart Use Case Analysis

## Overview
This project performs an in-depth analysis of Walmart's customer purchase data to understand various factors influencing purchase behavior. The dataset includes demographic attributes, product categories, and purchase amounts. The analysis aims to derive actionable insights based on age, gender, marital status, and city category.

## Dataset
The dataset used in this analysis consists of the following columns:

- `User_ID`: Unique identifier for the customer
- `Product_ID`: Unique identifier for the product
- `Gender`: Gender of the customer (M/F)
- `Age`: Age group of the customer
- `Occupation`: Occupation code for the customer
- `City_Category`: City tier (A/B/C) where the customer resides
- `Stay_In_Current_City_Years`: Number of years the customer has stayed in the current city
- `Marital_Status`: Whether the customer is married or not
- `Product_Category`: Category of the purchased product
- `Purchase`: Purchase amount

## Insights Derived
1. **Age Group Analysis**:
   - Customers in the 26-35 age group have the highest purchase frequency.
   - Confidence intervals for average spending indicate that older age groups, particularly 51-55, tend to spend more.

2. **Gender Analysis**:
   - Men spend more on average compared to women in Walmart.
   - The confidence interval for male customers shows a slightly higher range compared to female customers.

3. **City Category Analysis**:
   - City B has the highest number of customers, followed by City C and City A.
   - There are fewer outliers in purchase behavior in City C compared to Cities A and B.

4. **Marital Status**:
   - Married and unmarried customers have nearly equal average spending, with slight differences in the confidence intervals.

## Key Methods Used
- **Data Cleaning & Transformation**:
   - Missing values were handled effectively.
   - Categorical attributes were converted to the appropriate data types (`category`).

- **Univariate and Bivariate Analysis**:
   - Histograms and count plots were used to visualize the distribution of categorical and numerical variables.
   - Correlation heatmaps were generated to analyze the relationships between numerical variables.

- **Outlier Detection**:
   - Outliers in the `Purchase` column were detected using the IQR (Interquartile Range) method.

- **Confidence Intervals**:
   - Confidence intervals were calculated for average spending across different demographic groups (gender, marital status, and age) to provide a range of expected spending behavior.

## Visualizations
- Distribution of purchase amounts
- Purchase distribution by gender, age group, and city category
- Heatmaps showing correlations between occupation, marital status, product category, and purchase behavior

## Tools & Libraries Used
- **Python**: Data analysis and visualization
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical calculations
- **Matplotlib** & **Seaborn**: Visualization libraries
- **SciPy**: For statistical analysis (confidence intervals)

## Conclusion
The analysis reveals important behavioral trends based on customer demographics. These insights can help Walmart optimize marketing strategies, product placements, and promotional campaigns to better cater to different customer segments.

## How to Run
1. Clone the repository.
2. Install required libraries:  
   bash
   pip install pandas numpy matplotlib seaborn scipy
   
3. Run the Jupyter notebook `Walmart_usecase.ipynb` to explore the data and visualize the results.

## Contact
For any questions or collaboration, feel free to reach out.

