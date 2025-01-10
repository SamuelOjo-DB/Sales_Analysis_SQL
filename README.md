# Sales_Analysis_SQL

### Project Overview
This project seeks to implement ETL principles with Excel and SQL. Retail sales data will be imported into SQL after transforming it into an appropriate format from Excel and the database will be queried to answer business questions.

### Data Source
The Retail dataset was obtained from [Kaggle](https://www.kaggle.com/datasets/mohammadtalib786/retail-sales-dataset?resource=download)

### Tools
- EXCEL
- SQL

### Data cleaning/Validation
I checked for Null values/blank cells, checked spelling errors and correlated datatypes with columns using Power Query

![1](https://github.com/user-attachments/assets/2652c874-44cd-46ae-a9e4-774df396b553)

### Importing data (SQL)
Created a database and imported the dataset into the table

![2](https://github.com/user-attachments/assets/381de64f-67a1-4b45-ba2e-6b72638ac58c)

![3](https://github.com/user-attachments/assets/fe1c8cda-b793-4409-a201-6ddf8d232473) ![4](https://github.com/user-attachments/assets/c0c9c2ff-e696-4955-ba22-4af830522ba2)


### Formating data (SQL)
- I first converted the date column from string to date
- Renamed date column to (Sales_date) for clarity

![5](https://github.com/user-attachments/assets/720917cd-4fca-4592-b0a8-da1094eae0ae)

![6](https://github.com/user-attachments/assets/d9bb4e0b-b9c1-46e4-a975-ef0b031516de) ![7](https://github.com/user-attachments/assets/eeb0502c-a697-48d1-afdc-d0875d69a36a)

- Inserted the correct datatypes into the columns of the retail_sales_dataset table

![8](https://github.com/user-attachments/assets/6235ddc6-3479-4bae-9414-f3ea3458f184)

### Querying table (answering business questions)
- Total sales generated from the store?
  
![10](https://github.com/user-attachments/assets/6de10fc2-e171-4b0d-b10d-54f00cd487f2)

- What gender contributes the most to the total sales?

![11](https://github.com/user-attachments/assets/29e9ed2c-a6f3-43f2-9907-eaae7c2068fc)

- What are the top best-performing product categories?

![12](https://github.com/user-attachments/assets/a9d29fc0-e2ff-4941-94eb-ccd892ce02a9)

- What top 10 ages buy the most products?

![13](https://github.com/user-attachments/assets/6100d433-a594-4765-9bcf-ee10493d5b1a)

- How does the quantity of sales reflect in total product sales?

![14](https://github.com/user-attachments/assets/99f7c7c5-405b-4ae5-9796-f1fe314a96fe)








