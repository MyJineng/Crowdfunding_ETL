# Crowdfunding_ETL

Crowdfunding data was sourced from excel files than cleaned using Pandas before loading data into PostGresSQL.

Due to relationship constraints contained in the SQL Schema, please load the csvs in this order:
category, subcategory, contacts, and finally campagin funding.

# Campaign Category Data Frames - split data into two unique columns, dropped uncessary data, and added unique identifers
![image](https://github.com/MyJineng/Crowdfunding_ETL/assets/98989716/bbf7c1c3-74d1-44c1-a914-a4e932994ba6)

![image](https://github.com/MyJineng/Crowdfunding_ETL/assets/98989716/dccb6d09-d2ff-4475-91bd-7e8e82a6d743)

# Campaign Funding Data Frame - merged campaign categories, dropped unecessary data, reassigned datatypes from string to datetime/float
![image](https://github.com/MyJineng/Crowdfunding_ETL/assets/98989716/5e4fb175-43ab-42bd-8702-be185e7048aa)

# Contacts Data Frame - split from single string into indivdual clean columns
![image](https://github.com/MyJineng/Crowdfunding_ETL/assets/98989716/3bb4127a-d070-49d6-b11a-8b5ce0b95ad6)

# ERD of database to conceptualize linking
![ERD](https://github.com/MyJineng/Crowdfunding_ETL/assets/98989716/95c44fdd-6d39-4783-a40e-656033f927e4)

# Confirmation of data loaded into PostGres
![image](https://github.com/MyJineng/Crowdfunding_ETL/assets/98989716/0630e5fb-6574-4653-a404-a21c93fc6d9a)

