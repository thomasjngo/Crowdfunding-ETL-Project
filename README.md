# Crowdfunding-ETL-Project

## Category and Subcategories
Using the contacts and crowdfunding excel files, we extracted and transformed the data to make category and subcategory dataframes that are numbered sequential from 1 to the length of unique categories and subcategories. Afterwards, we used list comprehension to add cat to each category and subcategory ID and made an array which was then used to create new dataframes.

## Campaign
We created a copy of the crowdfunding information to organize the data based on the information we needed to get a better sense of the outcomes of the campaigns. Data was then formatted and organized into columns with the correct datatypes and then merged with the categories and subcategories dataframes we created previously.

## Contacts
We read the contacts excel data to import into a dataframe and used regular expressions to extract the four digit contact ID number, name, and email and created a new copy of the dataframe to organize by first and last name.

## Crowdfunding Database
All the data was then exported into csv files and a database schema was created to organize the data into tables for SQL. Primary and foreign keys were assigned, and an ERD was sketched to draw the relationships between the columns of the tables.
