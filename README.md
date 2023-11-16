# Crowdfunding ETL Mini Project

## Introduction
This mini project focuses on building an ETL (Extract, Transform, Load) pipeline using Python, Pandas, and either Python dictionary methods or regular expressions. The goal is to process crowdfunding data, create CSV files, design a database schema, and load the data into a PostgreSQL database.

## Project Structure

### Files
* [main ETL](https://github.com/anderoos/Crowdfunding-ETL/blob/main/ETL_Mini_Project_ACheng_RGajjar.ipynb)
* [schema ETL](https://github.com/anderoos/Crowdfunding-ETL/blob/main/crowdfunding_db_schema.sql)
* [query ETL](https://github.com/anderoos/Crowdfunding-ETL/blob/main/crowdfunding_db_query.sql)

## Approach
1. Extracted and Transformed excel crowdfunding.xlxs.
   - Created category, subcategory, and campaign dataframes
2. Extracted and Transformed excel crowdfunding.xlsx.
   - cleaned dataset and split into the following columns:
            - The "cf_id" column
            - The "contact_id" column
            - The "company_name" column
            - The "blurb" column, renamed to "description"
            - The "goal" column, converted to the float data type
            - The "pledged" column, converted to the float data type
            - The "outcome" column
            - The "backers_count" column
            - The "country" column
            - The "currency" column
  3. Cleaned contacts.xlsx and transformed the data using regular expressions(regex) to create contacts dataframe
  4. All four dataframes were saved to a csv file
  5. Created sql schema by analyzing the csv files
     - assigned primary and foreign keys to define relationships
     - created an ERD
  6. Imported csv files into postgres database named crowdfunding_db

## Images
![ERD](https://github.com/anderoos/Crowdfunding-ETL/blob/main/images/crowdfunding-ERD.png)
![processes](https://github.com/anderoos/Crowdfunding-ETL/blob/main/images/successful%20processes.png)


   





 

 
