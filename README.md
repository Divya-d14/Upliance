# Upliance Customer Orders Analysis

## Objective

The objective of this project is to analyze datasets related to user behavior, cooking preferences, and order trends. This analysis will provide insights into how user characteristics and preferences influence cooking sessions and order trends. By merging and cleaning three datasets, we aim to explore the relationship between cooking sessions, user demographics, and their ordering behavior. 

## Datasets

This project uses three datasets:

1. **UserDetails**: Contains information about users such as their age, gender, location, and registration date.
2. **CookingSessions**: Contains details about cooking sessions, including the dishes prepared, session duration, and time of day.
3. **OrderDetails**: Contains information on user orders, such as dish names, order amounts, and session ratings.

## Tasks

The project involves the following steps:

1. **Data Cleaning and Merging**:
   - Merge the three datasets (`UserDetails`, `CookingSessions`, and `OrderDetails`) based on relevant keys
     ( This is done by using XLookUp in Excel and used the final merged dataset).
   - Handle missing values, duplicates, and inconsistent data.

2. **Exploratory Data Analysis (EDA)**:
   - Analyze the relationship between cooking sessions and user orders.
   - Identify popular dishes ordered during different times of the day (breakfast, lunch, dinner).
   - Explore demographic factors (e.g., age, location) that influence user behavior.
   - Look for patterns in session ratings, duration, and order amounts.

3. **Data Visualization**:
   - Create visualizations to showcase key insights, including hist plots, bar plots, and correlation heatmaps.
   - Visualize the proportions of different dishes ordered during breakfast, lunch, and dinner.
   - Visualize the relationships between user behavior and demographic features.

4. **Business Insights and Recommendations**:
   - Provide insights based on the analysis of user preferences and behavior.
   - Offer business recommendations on how to optimize cooking sessions, improve user experience, and increase order amounts.

## Approach

1. **Data Understanding**:
   - Inspect the structure, size, and content of each dataset.
   - Identify key variables and relationships between datasets.
   
2. **Data Cleaning**:
   - Handle missing values, duplicate entries, and data inconsistencies.
   - Format data appropriately (e.g., standardizing column names, date formats).
   
3. **Data Analysis**:
   - Group and aggregate data based on relevant columns.
   - Calculate correlations between variables and explore trends.

4. **Data Visualization**:
   - Create various visualizations using **Matplotlib** and **Seaborn** (pie charts, bar plots, heatmaps, etc.).
   - Highlight significant patterns and relationships between different factors (e.g., age, session ratings, and order amounts).

5. **Insights and Recommendations**:
   - Interpret the findings and offer actionable insights.
   - Recommend strategies based on the data analysis (e.g., optimizing cooking session times, targeting specific user demographics for promotions).

## Tools and Libraries Used

- **Python**: Programming language used for data analysis and visualization.
- **Pandas**: Library for data manipulation and cleaning.
- **Matplotlib**: Library for creating static, animated, and interactive visualizations.
- **Seaborn**: Library for statistical data visualization based on Matplotlib.
- **Jupyter Notebooks**: For running and documenting the analysis.

## Conclusion:
The analysis highlights key customer behavior trends, including preferred meal types, spending patterns, and the impact of session duration on customer satisfaction.
Recommendations include targeting younger age groups (25-27), optimizing dishes for different times of day, and promoting popular dishes like Spaghetti and Grilled Chicken. 
There is also an opportunity to re-engage customers with underperforming dishes like Oatmeal and Veggie Burger. Please refer the collab for detailed analysis, insights and recommendations
