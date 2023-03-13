# Crowdfunding_ETL
Project 2
The Crowdfunding_ETL assignment was undertaken independently and primarily uses “Pandas” and the PostgreSQL database to create tables and analyse the data of given data. The initial data focuses on the basis details of crowdfunded projects. Some of the data provided includes the date of launch, category and subcategory and the name of the company which launched the project.  

The data is then split up, focusing on the unique characteristics of each category and subcategory of each crowdfunded project. From this new DataFramescan be developed through the “pd.DataFrame” function, using the prepend function to place a string before each category and subcategory ID.

Each new DataFrame is saved to the git clone, and data is cleaned through the dropping of columns and renaming to clean data for ease of accessibility and readability. Each saved DataFrame is then imported to a new PostgreSQL database, where the primary keys for the following columns were created. 
-	Contact_id
-	Category_id
-	Subcategory_id

Each new table can then be linked using a foreign key, allowing unique tables to be constructed. 
