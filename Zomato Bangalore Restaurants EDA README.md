
## Project: EDA of Bangalore-based Restaurants
### About The Project
**Tool used: Python**

---
**Problem Statement:** 
This project aims to analyze **Bangalore-based restaurants' data registered on Zomato** and get valuable insights. Our goal is to understand the restaurant landscape in Bangalore, identify popular cuisines, explore the impact of online ordering and table booking, analyze cost distributions, and make recommendations to improve customer satisfaction and business growth. It can also help people in finding the best restaurants according to their preferences and needs in the city.

**Kaggle Notebook Link:** 
https://www.kaggle.com/code/mohd647/zomato-bangalore-data-eda

**Dataset:** 
The dataset used for this analysis consists of Bangalore-based restaurants registered on Zomato. It includes several columns with relevant information such as
- restaurant names
- online order availability
- ratings, location 
- restaurant type, etc. 


**Cleaned Dataset Review**

| name              | online_order | book_table | rate | votes | location      | rest_type       | cuisines                            | cost2persons | type   |
|-------------------|--------------|------------|------|-------|---------------|-----------------|-------------------------------------|--------------|--------|
| Jalsa             | Yes          | Yes        | 4.1  | 775   | Banashankari  | Casual Dining   | North Indian, Mughlai, Chinese       | 800.0        | Buffet |
| Spice Elephant    | Yes          | No         | 4.1  | 787   | Banashankari  | Casual Dining   | Chinese, North Indian, Thai          | 800.0        | Buffet |
| San Churro Cafe   | Yes          | No         | 3.8  | 918   | Banashankari  | others          | Cafe, Mexican, Italian               | 800.0        | Buffet |



---
**Steps that are taken in this analysis are as follows:**

**Step 1. Data Profiling and Cleaning**
- Checked Data Dimensions: Check the dimensions of the dataset to understand the number of rows and columns.
- Checked Data Types: Examine the data types of each column to ensure they are correctly assigned and handle any inconsistencies.
- Handled Missing Values: Identify missing values in the dataset and decide on an appropriate strategy to handle them (e.g., imputation or removal).
- Dropped Redundant Columns: Dropped some of the columns as they were not helpful in this analysis.
- Renamed Columns: Renamed a few columns to make them more readable.
- Changed Some of The Values of a Few Columns: Do so to make the analysis easy.

 
**Step 2. Exploratory Data Analysis (EDA)**

- **Correlation Analysis:** Explored correlations between variables to identify any significant relationships. For example, analyzing the correlation between ratings and votes or ratings and costs can provide insights into customer preferences and pricing strategies.
  
- **Statistical Summary:** Calculated basic statistics of columns such as ratings, votes, and costs. This provides an overview of the data distribution and helps identify any outliers or unusual values.

- **Data Visualization:** Utilized various visualization techniques, such as histogram, bar plot, scatter plot, donut chart, and boxplot to explore the data and gain insights.
  
- **Analysis by Categories:** Analyzed the distribution of ratings, votes, and costs based on different categories such as location, online order availability, and book table service availability. This allows us to understand variations and preferences across various segments.

- **Extraction of Insights:** Extracted meaningful insights from the EDA results, such as popular cuisines, the impact of online ordering and table booking on ratings, customer preferences based on location, and cost distributions. These insights form the basis for making recommendations to any typical customer or a person who wants to open a new restaurant in the city.

