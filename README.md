# Data_Transformation-and-Date_Modelling
 
# 📦 Orders Data Set

## 📌 Project Overview

This dataset contains Three Tables List of Orders having Order ID, Order Date, Customer Name, City, State, Category, Amount, Profit and Order details Table having Order ID, Category, Sub-Category, Quantity, Amount, Profit and also Sales Target Table having Category, Month of Order Date, Target

It can be used for practicing data analysis, data visualization, Excel, SQL, Python, and Power BI.


## 🎯 Project Objectives

1. Data Import
2. Row Limiting & Data Types
3. Text Formatting
4. Column Creation
5. Conditional Column
6. Merging Data (Joins)
7. Handling Missing Data & Duplicate Data
8. Sorting and Filtering Data
9. Grouping and Aggregating Data
10. Data Modeling



## 🛠️ Tools and Technologies

This dataset can be used with:

- Microsoft Power BI

**###Data Import:**

➢ Imported List of Orders.csv into Power BI. 
➢ Opened the list of orders in the Power Query Editor and used the Transform 
Data option. 

<img width="940" height="483" alt="image" src="https://github.com/user-attachments/assets/c8472cf6-d202-4f45-b663-5b47b247dab2" />

➢ Imported Order Details.csv and Sales Target.csv into Power Query Editor

<img width="940" height="442" alt="image" src="https://github.com/user-attachments/assets/2586be79-395d-4834-b409-9b8cb6530f5d" />

**###Row Limiting & Data Types:**

➢ Kept the first 500 rows in List of Orders table.

<img width="940" height="357" alt="image" src="https://github.com/user-attachments/assets/099112e1-7bc9-48a2-b042-903d6e03ceae" />

➢ Set the Order Date column to the Date data type.

<img width="940" height="347" alt="image" src="https://github.com/user-attachments/assets/60bb3d05-6b6d-4eea-9463-01b5832bce34" />

➢ Change the Amount and Target columns to fixed decimal numbers.

<img width="940" height="356" alt="image" src="https://github.com/user-attachments/assets/26c6d200-05de-46e7-be81-f5380d9a53fc" />

<img width="940" height="357" alt="image" src="https://github.com/user-attachments/assets/eb304162-9546-418c-8316-814880b5fe71" />

**###Text Formatting:**

➢ Format the CustomerName column to proper case to ensure consistent capitalization.

<img width="940" height="356" alt="image" src="https://github.com/user-attachments/assets/b9fcdede-93ee-4868-b582-749abf049d63" />

**###Column Creation:**

➢ Merge the City and State columns to create a new column named Location in the format: City, State

<img width="940" height="355" alt="image" src="https://github.com/user-attachments/assets/8df7547c-5525-4f1e-bb81-8a97ac611bba" />

➢ Create a custom column named Profit Margin calculated as: Profit / Amount (expressed as a percentage)

<img width="940" height="340" alt="image" src="https://github.com/user-attachments/assets/6cae4608-4400-422a-8d62-ae3ac2b14063" />

**###Conditional Column:**
➢ Add a conditional column named Profit Status based on:
■ Profit < 0 → Loss
■ Profit = 0 → Break-Even
■ Profit > 0 → Profit

<img width="940" height="353" alt="image" src="https://github.com/user-attachments/assets/e6122631-f1a3-4a89-b2b3-73fcff5c030e" />

**###Merging Data (Joins):-**

➢ Merge the List of Orders and Order Details tables using Order ID.
➢ Name the merged output table as Orders Data.

<img width="940" height="523" alt="image" src="https://github.com/user-attachments/assets/40dfd5a8-212b-4ebe-8a36-a105c9dc62f2" />

**###Handling Missing Data & Duplicate Data:-**
➢ Identify missing values across all tables.

<img width="940" height="221" alt="image" src="https://github.com/user-attachments/assets/fe5512e6-6672-4da3-b5fe-803f80ea7e14" />

➢ Define and apply appropriate strategies such as:
○ Replacing missing values
○ Removing records
○ Retaining nulls with justification
**Transform → Replace Values**
➢ Identified the duplicate rows in each table and removed duplicates **HomeRemove RowsRemove duplicates**

<img width="940" height="265" alt="image" src="https://github.com/user-attachments/assets/9916a9fd-e473-451d-bc4d-51edf375c0a6" />

### Sorting and Filtering Data:-

➢ Sort records in the Orders Data table by Order Date in descending order.

<img width="940" height="194" alt="image" src="https://github.com/user-attachments/assets/fab02807-9290-44e1-923e-9cc036939f65" />

➢ Apply filters to analyze orders from a specific state (e.g., Tamil Nadu)

<img width="940" height="244" alt="image" src="https://github.com/user-attachments/assets/ee3f5836-1da9-464b-b794-b1acdf84de19" />

### Grouping and Aggregating Data:-

➢ Duplicate the Order Details table and perform the following:
○ Count of Order ID – HomeGroup by used to create the cound of order id

<img width="940" height="236" alt="image" src="https://github.com/user-attachments/assets/1cac4c24-dff7-4aee-b6d0-5f7535d70988" />

○ Average Profit by Category – HomeGroup byused to create average profit margin column

<img width="940" height="204" alt="image" src="https://github.com/user-attachments/assets/b3fd8a09-e4d7-42f8-966b-25ceb303f959" />

○ Total Amount by Sub-Category – HomeGroup by used to find the Total amount of sub-category

<img width="940" height="261" alt="image" src="https://github.com/user-attachments/assets/6edf193c-c86d-4461-83b6-787eae67bdce" />

● Duplicate the Sales Target table and aggregate the total Target by Month of order date.

<img width="940" height="229" alt="image" src="https://github.com/user-attachments/assets/1c2dfe2f-b6e4-4f50-a85c-442f7beb5eb4" />

10. Data Modeling:
● Establish a relationship between:
○ List of Orders and Order Details using Order ID
○ Order Details and Sales Target using Category

<img width="940" height="556" alt="image" src="https://github.com/user-attachments/assets/e44c2258-2265-4eda-ab1e-60fa015b742a" />

2. Use Manage Relationships to ensure relationships are active and correctly defined.

   <img width="940" height="654" alt="image" src="https://github.com/user-attachments/assets/18c5bf74-c679-4271-b92f-4358fba68fad" />

##**Key Learnings**
Through this project, I practiced:

1. Importing the Data in Power BI
2. Row Eliminating and Changed Data type
3. Text formatting
4. Column Creation
5. Merging Data
6. Handling missing Data and Duplicate Data
7. Sorting and Filtering Data
8. Grouping the Data
9. Data Modeling


## 👤 Author

**Bhavani**

Aspiring Data Analyst | Excel | SQL | Python | Power BI

---
