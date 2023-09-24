# Instacart Grocery Basket Analysis: Python | Jupyter | Pandas

### B A C K G R O U N D
Instacart wants a deeper understanding of their customers and their purchasing behaviors. They are interested in grouping their customers into profiles, creating targeted marketing campaigns and measuring how these strategies affect proceeding sales. 


### N E E D
Perform an initial exploratory analysis about the customers and their purchasing behaviors, create customer profiles, and suggest marketing strategies for each.


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
   - dataframes were merged together one by one 
   - for-loop if-statements were used to exclude certain customers 
   - for-loop if-statements were used to create conditional columns from which customer profiles were built 
   - random sample of dataframe was taken to reduce dataframe size to 30%


### E X P L O R A T I O N
   - descriptive analysis of each customer profile was performed 
   - analysis performed to answer questions provided by Instacart 
   - visuals created using matplotlib, seaborn to support insight  
