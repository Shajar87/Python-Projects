## Project: Zomato Bangalore Restaurants Project
### About The Project
**Tool used: Python**

---
In this project, I performed exploratory data analysis (EDA) of Bangalore-based restaurants.
The dataset was taken from Kaggle. 

The task was to perform exploratory data analysis to uncover insights into restaurants' menus and services. From identifying popular cuisines to analyzing ratings and reviews.

This analysis will help new restaurants in deciding their theme, menus, cuisine, cost, etc for a particular location.

**Dataset Review**

|   | address                                                   | name             | online_order | book_table | rate  | votes | phone               | location      | rest_type          | dish_liked                                              | cuisines                          | approx_cost(for two people) | reviews_list                                            | menu_item | listed_in(type) | listed_in(city) |
|---|-----------------------------------------------------------|------------------|--------------|------------|-------|-------|---------------------|----------------|--------------------|---------------------------------------------------------|-----------------------------------|-----------------------------|---------------------------------------------------------|-----------|-----------------|-----------------|
| 0 | 942, 21st Main Road, 2nd Stage, Banashankari, ...          | Jalsa            | Yes          | Yes        | 4.1/5 | 775   | 080 42297555       | Banashankari   | Casual Dining      | Pasta, Lunch Buffet, Masala Papad, Paneer Laja...      | North Indian, Mughlai, Chinese   | 800                         | [('Rated 4.0', 'RATED\n A beautiful place to ... | []        | Buffet          | Banashankari    |
| 1 | 2nd Floor, 80 Feet Road, Near Big Bazaar, 6th ...          | Spice Elephant   | Yes          | No         | 4.1/5 | 787   | 080 41714161       | Banashankari   | Casual Dining      | Momos, Lunch Buffet, Chocolate Nirvana, Thai G...      | Chinese, North Indian, Thai      | 800                         | [('Rated 4.0', 'RATED\n Had been here for din... | []        | Buffet          | Banashankari    |
| 2 | 1112, Next to KIMS Medical College, 17th Cross...          | San Churro Cafe  | Yes          | No         | 3.8/5 | 918   | +91 9663487993      | Banashankari   | Cafe, Casual Dining | Churros, Cannelloni, Minestrone Soup, Hot Choc...      | Cafe, Mexican, Italian           | 800                         | [('Rated 3.0', "RATED\n Ambience is not that ... | []        | Buffet          | Banashankari    |


---
**The steps involved in the analysis are:**
1. Cleaned the data
- Dropped some irrelevant columns from the dataset.
- Renamed some columns for of making the analysis easier.
- Filled NAN values with the mean of the respective column.
2. Exploratory data analysis e.g.
- Found locations which are best under Rs. 1000 budget for 2 persons.
- Plotted heatmap to show a correlation between different features.
- Found location which has the most number of restaurants. 
- Compared online/offline orders with respective rates.
- Found Favourite cuisine in Banglore etc.



**For more details, please visit the Kaggle notebook link:** https://www.kaggle.com/code/mohd647/zomato-bangalore-data-eda
