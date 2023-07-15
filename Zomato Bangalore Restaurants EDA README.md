## Project: Zomato Bangalore Restaurants Project
### About The Project
**Tool used: Python**

---
In this project, I performed exploratory data analysis (EDA) of Bangalore-based restaurants.
The dataset was taken from Kaggle. 

The task was to perform exploratory data analysis to uncover insights into restaurants' menus and services. From identifying popular cuisines to analyzing ratings and reviews.

This analysis will help new restaurants in deciding their theme, menus, cuisine, cost, etc for a particular location.

Also it will help people in finding best restaurants in the city.


**Cleaned Dataset Review**

| name              | online_order | book_table | rate | votes | location      | rest_type       | cuisines                            | cost2persons | type   |
|-------------------|--------------|------------|------|-------|---------------|-----------------|-------------------------------------|--------------|--------|
| Jalsa             | Yes          | Yes        | 4.1  | 775   | Banashankari  | Casual Dining   | North Indian, Mughlai, Chinese       | 800.0        | Buffet |
| Spice Elephant    | Yes          | No         | 4.1  | 787   | Banashankari  | Casual Dining   | Chinese, North Indian, Thai          | 800.0        | Buffet |
| San Churro Cafe   | Yes          | No         | 3.8  | 918   | Banashankari  | others          | Cafe, Mexican, Italian               | 800.0        | Buffet |



---
**The steps involved in this analysis are as:**

**Step 1.** Data Profiling and Cleaning
- Checked Data Dimensions: Check the dimensions of the dataset to understand the number of rows and columns.
- Checked Data Types: Examine the data types of each column to ensure they are correctly assigned and handle any inconsistencies.
- Handled Missing Values: Identify missing values in the dataset and decide on an appropriate strategy to handle them (e.g., imputation or removal).
- Dropped Redundant Columns: Dropped ['url', 'address','phone','menu_item','dish_liked','reviews_list','listed_in(city)']
- Renamed Columns: Renamed columns 'approx_cost(for two people)' to'cost2persons' and 'listed_in(type)' to 'type'.
- Changed Values of Some of The Columns: Do so to make the analysis easy.

 
2. Exploratory data analysis e.g.

- Correlation Analysis: Explore correlations between variables to identify any significant relationships. For example, analyzing the correlation between ratings and votes or ratings and costs can provide insights into customer preferences and pricing strategies.
  
- Statistical Summary: Calculate basic statistics of columns such as ratings, votes, and costs. This provides an overview of the data distribution and helps identify any outliers or unusual values.

- Data Visualization: Utilize various visualization techniques, such as histogram, bar plot, scatter plot,donut chart, boxplot to explore the data and gain insights.
  
- Analysis by Categories: Analyze the distribution of ratings, votes, and costs based on different categories such as location, online order availability, and restaurant type. This allows us to understand variations and preferences across different segments.

- Identification of Insights: Extract meaningful insights from the EDA results, such as popular cuisines, the impact of online ordering and table booking on ratings, customer preferences based on location, and cost distributions. These insights form the basis for making recommendations to the client.



**For more details, please visit the Kaggle notebook link:** https://www.kaggle.com/code/mohd647/zomato-bangalore-data-eda
