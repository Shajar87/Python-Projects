# Bank Customers Churn Analysis & Prediction

### About The Project
**Tool used: Python**

---
In this project, I have to analyze customers' data from a bank. I performed an exploratory analysis in order to gain insights into the primary factors influencing customer churn. 

Additionally, I also developed a machine learning model to accurately predict customer churn with an accuracy of 99.9%.

The dataset contains the bank customer's details like his\her 
- Credit Score,	Age, Tenure,	
- having a credit card or not,	
- active member or not, Exited or not, etc.

**Dataset Review**

| RowNumber | CustomerId | Surname   | CreditScore | Geography | Gender | Age | Tenure | Balance   | NumOfProducts | HasCrCard | IsActiveMember | EstimatedSalary | Exited | Complain | Satisfaction Score | Card Type | Point Earned |
|-----------|------------|-----------|-------------|-----------|--------|-----|--------|-----------|---------------|-----------|----------------|-----------------|--------|----------|--------------------|-----------|--------------|
| 1         | 15634602   | Hargrave  | 619         | France    | Female | 42  | 2      | 0         | 1             | 1         | 1              | 101348.88       | 1      | 1        | 2                  | DIAMOND   | 464          |
| 2         | 15647311   | Hill      | 608         | Spain     | Female | 41  | 1      | 83807.86  | 1             | 0         | 1              | 112542.58       | 0      | 1        | 3                  | DIAMOND   | 456          |
| 3         | 15619304   | Onio      | 502         | France    | Female | 42  | 8      | 159660.8  | 3             | 1         | 0              | 113931.57       | 1      | 1        | 3                  | DIAMOND   | 377          |


---
**A series of steps that were taken were as follows:**

1. Importing the Required Libraries:
   - Pandas: Data manipulation and analysis.
   - NumPy: Mathematical operations and array processing.
   - Matplotlib: Data visualization.
   - Seaborn: Enhanced data visualization.
   - Plotly: Interactive data visualization.
   - Scikit-learn: Machine learning algorithms and evaluation metrics.
     
2. Data Loading:
   - Read the churn data into a Pandas DataFrame.

3. Data Cleaning and Preprocessing:
   - Dropped some redundant features.
   - Converted categorical columns (Geography, Gender, Card Type) to 'category' data type.
   - Encoded categorical variables using the pandas get_dummies function.
   - Scaled numerical features using StandardScaler.

5. Exploratory Data Analysis (EDA):
   - Performed data profiling and summary statistics.
   - Visualized key insights and patterns using various charts and plots:
     - Histograms, bar plots, scatter plots, etc.
     - Analyzed distributions, correlations, and relationships between variables.
     - Explored customer churn patterns by different factors.

6. Feature Engineering:
   - Selected relevant features for model training.
   - Defined the target variable (Exited) and predictor variables.

7. Model Selection and Training:
   - Split the data into training and testing sets.
   - Trained the machine learning model 'Random Forest Classifier'.
   - Evaluated model performance using various metrics like accuracy score, precision, F1-Score, etc.

8. Hyperparameter Tuning:
   - Used GridSearchCV to optimize the model hyperparameters.
   - Defined the hyperparameter grid for the Random Forest Classifier.

9. Model Evaluation:
   - Compared model performance using accuracy, precision, recall, and F1-score metrics.
   - Assessed the performance of the tuned model using the best hyperparameters.

10. Analysis Findings and Recommendations:
    - Summarize key findings from the analysis, such as customer demographics, churn patterns, and factors influencing churn.
    - Provide insights into the causes behind the findings.
    - Make recommendations based on the analysis, such as strategies to decrease churn rate.



**For more details, please visit the Kaggle notebook link:**

https://www.kaggle.com/code/mohd647/bank-customers-churn-analysis-prediction


