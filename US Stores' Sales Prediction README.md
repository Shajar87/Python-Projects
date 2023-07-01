## Project: US Stores' Sales Prediction
### About The Project
**Tool used: Python**

---
In this project, the goal was to predict the sales of stores located in the USA with the help of machine learning techniques. 

This dataset contains information about Sales Values in Dollars of American Stores between 2010 and 2011. In particular, this dataset contains:

- Stores' Area, State, Region, and Size;
- Products' ID, Description, Type, Category, and Sale Date;
- Accounting Info, such as Budget Margin, Profit, Total Expenses, and Marking.


| S.No | Area Code | State       | Market | Market Size  | Profit | Margin | Sales | COGS  | Total Expenses | Marketing | Inventory | Budget Profit | Budget COGS | Budget Margin | Budget Sales | ProductId | Date                | Product Type | Product    | Type    |
|------|-----------|-------------|--------|--------------|--------|--------|-------|-------|----------------|-----------|------------|----------------|-------------|---------------|--------------|-----------|---------------------|--------------|------------|---------|
| 0    | 203       | Connecticut | East   | Small Market | 107.0  | 176.0  | 292.0 | 116.0 | 69.0           | 38.0      | 962.0      | 110.0          | 110.0       | 160.0         | 270.0        | 2         | 04/01/10 00:00:00   | Coffee       | Columbian  | Regular |
| 1    | 203       | Connecticut | East   | Small Market | 75.0   | 135.0  | 225.0 | 90.0  | 60.0           | 29.0      | 1148.0     | 90.0           | 80.0        | 130.0         | 210.0        | 2         | 07/01/10 00:00:00   | Coffee       | Columbian  | Regular |
| 2    | 203       | Connecticut | East   | Small Market | 122.0  | 195.0  | 325.0 | 130.0 | 73.0           | 42.0      | 1134.0     | 130.0          | 110.0       | 180.0         | 290.0        | 2         | 11/01/10 00:00:00   | Coffee       | Columbian  | Regular |



---
**The steps involved were as:**
1. Cleaned the data e.g.
- Changed the date datatype and format.
- Dropped some irrelevant columns.
2. Visualized various features through different plots, e.g. **regression plot, histogram, line plot,**, etc.
3. Build a machine-learning model using the machine-learning technique **(Random Forest Regressor)**.
- Calculated and plotted **mutual information score** for discrete & continuous features.
- Did preprocessing and label encoding of data using **StandardScaler** and **LabelEncoder** respectively.
- Finally, created a predictive model using Random Forest Regressor.
  

**For more details, please visit the Kaggle notebook link:**
https://www.kaggle.com/code/mohd647/us-store-sale-prediction
