# Instacart Grocery Basket Analysis: 
Python | Jupyter | Pandas

<br>

### B A C K G R O U N D
Instacart wants a deeper understanding of their customers and their purchasing behaviors. They are interested in grouping their customers into profiles, creating targeted marketing campaigns and measuring how these strategies affect proceeding sales. 

<br>

### N E E D
Perform an initial exploratory analysis about the customers and their purchasing behaviors, create customer profiles, and suggest marketing strategies for each.

<br>

### D A T A S E T S
The datasets utilized for this analysis is part real ("The Instacart Online Grocery Shopping Dataset 2017" accessed via Kaggle) and part fabricated by Career Foundry for educational purposes. 

A total of four datasets were used:

   - orders (real): 
       - data associated with each order
       - order ID, day and time of order, days since prior order
   - orders_products (real): 
       - data associated with each order, including products ordered in each
       - order ID, product ID
   - products (real): 
       - data associated with all products available through Instacart
       - product ID, name, department, price
   - customers (fabricated):
       - data associated with customers
       - name, gender, state, age, family status, dependents, income

<br>

### P R E P A R A T I O N
Data cleaning:
   - missing and duplicated values and outliers addressed
   - consistency check performed 

Data wrangling:
   - data types reviewed and standardized 
   - dataframe subsets created, extracting only relevant data 
   - column names were standardized 
   - dataframes were exported as pickles 

Data transformation: 
   - dataframes merged together one by one 
   - for-loop if-statements used to exclude certain customers 
   - for-loop if-statements used to create conditional columns from which customer profiles were built 
   - random sample of dataframe taken to reduce dataframe size to 30%

<br>

### E X P L O R A T I O N
   - descriptive analysis of each customer profile 
   - analysis performed to answer questions provided by Instacart 
   - visualizations created using matplotlib, seaborn to support insights

<br>

### L I B R A R I E S
   - data processing: Pandas, NumPy, os
   - statistical analysis: SciPy
   - data visualization: Matplotlib, Seaborn
   - data presentation: Jupyter Notebook, Excel

<br>

### S K I L L S
   •  importing datasets
   •  exporting dataframes as .csv and .pkl
   •  comments, markdowns, notebook grammar, best practices
   •  removing missing and duplicate values
   •  renaming column names
   •  dropping columns and rows
   •  changing data types
   •  subsetting dataframes
   •  aggregations (mean, median, min, max)
   •  merging dataframes
   •  if-statements: loc() function, for-loop, user-defined
   •  randomized sampling 
   •  data visualizations (Matplotlib.pyplot and Seaborn): 
      bar, stacked bar, line, histogram, scatterplot
