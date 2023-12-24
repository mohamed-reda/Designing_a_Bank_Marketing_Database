# Project: Bank Marketing Campaign Database Design

## Introduction
In this project, we aim to assist a bank in setting up a PostgreSQL database to store data collected during a marketing campaign. The dataset, provided in a CSV file named "bank_marketing.csv," includes information on clients, campaign details, and economic indicators. Our task involves cleaning and structuring the data for efficient storage in a relational database. The database schema is designed to accommodate future campaigns seamlessly.


clean and store the data of Bank Marketing Database with Numpy and Pandas as part of a recent marketing campaign, which aimed to get customers to take out a personal loan. They plan to conduct more marketing campaigns going forward to store this campaign's data, designing the schema in a way that would allow data from future campaigns to be easily imported.

## 1. Loading and Splitting Data
We start by loading the dataset into a pandas DataFrame and splitting it into three subsets: client, campaign, and economics, as per the specified database tables.

## 2. Renaming Columns
We rename columns to align with the desired schema, ensuring consistency and clarity in the database.

## 3. Data Cleaning
Cleaning involves handling missing values, converting data types, and standardizing categorical values, enhancing the overall quality of the dataset.

## 4. Creating Additional Columns
We add necessary columns such as campaign_id and last_contact_date to the campaign table for improved organization.

## 5. Saving to CSV
The cleaned and formatted data is saved to separate CSV files: client.csv, campaign.csv, and economics.csv.

## 6. SQL Table Creation
SQL code is generated for creating tables: client, campaign, and economics. The \copy command is included to load data from corresponding CSV files into the tables.

## Conclusion
This project ensures a well-organized and clean database setup for the bank's marketing campaign data. The provided SQL code can be executed to create tables and import data efficiently. Future campaigns can seamlessly leverage this structured database design.
