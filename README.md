# DataCamp-Formatting-PostgreSQL-Sales-Data
My work for a DataCamp project to clean and format a PostgreSQL sales data. This project aims to gain insight regarding high sales items from a fictional store database. Here I was able to apply data cleaning and analyzing techniques such as imputing data, and data ranking.

## Description
A Super Store has data regarding their products spread across four tables in their database. The goal of the project is to perform data analysis by showing top 5 products from each category based on sales, and handle missing values by imputing them from available data.

## Dataset
The dataset given is four tables from Super Store database, containing relevant attributes for objects of each table.

<p align="center">
  <img src="https://github.com/user-attachments/assets/a6ddcf2a-78e3-4ec7-836e-97c9763509fa">
</p>
<p align="center">Figure 1. Data dictionary for 'orders' table.</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/aca9316e-3fbc-455d-a467-9806253191c0">
</p>
<p align="center">Figure 2. Data dictionary for 'returned_orders' table.</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/087bbbeb-fc04-4039-b5f8-a613b713e9ff">
</p>
<p align="center">Figure 3. Data dictionary for 'people' table.</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/4392fa44-689d-4230-9007-66ca6e4e2c1d">
</p>
<p align="center">Figure 4. Data dictionary for 'products' table.</p>

## Walkthrough

### 1. Product & Category Sales Ranking
From the dataset, I want to find the highest ranking products based on sales for each category. Here I applied sales and profit grouping for each product and category, and then rank them based on sales performance from high to low. By having knowledge of this, the Super Store is able to gain insight as to the most profitable or popular products. This leads to better data-driven decisions such as in stock management to keep popular products always available.

![image](https://github.com/user-attachments/assets/63b06113-d071-4f81-8d6c-b97ed4b24721)
<p align="center">Figure 5. Data grouping and ranking based on sales.</p>

![image](https://github.com/user-attachments/assets/d11c30cf-a613-464b-8d05-2abb18a33f7e)
<p align="center">Figure 6. Top 5 products in each category based on sales.</p>

### 2. Data Imputing
Next I found that there are some missing values in the 'quantity' column of the 'orders' table. I want to impute those missing values by considering existing data from the database. I have taken pricing factors such as region, market, and discount into consideration so that the imputation result is more accurate.

![image](https://github.com/user-attachments/assets/c26dccd1-fd60-47a8-82fa-6a616a7d4be2)
<p align="center">Figure 7. Imputing quantities based on various pricing factors.</p>

![image](https://github.com/user-attachments/assets/e724275c-3522-4b1c-8022-c2b70b8bc119)
<p align="center">Figure 8. Products with missing quantities and the imputed results.</p>

## Conclusion
Through this project, I demonstrated my SQL proficiency by extracting insights from sales data and accurately imputing missing values using contextual and relevant existing information. This highlights my ability to apply data-driven logic to solve real-world business problems.
