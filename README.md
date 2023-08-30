# nosql-challenge :Eat Safe,Love

In this challenge, I use PyMongo to analyze some rating data from *The UK Food Standards Agency* of various establishments across the United Kingdom, in order to help journalists and food critics from the food magazine, *Eat Safe, Love* to evaluate some of the ratings to decide where to focus future articles.

## Data Sources:

Tha data is provided in JSON format and the file is called establishment and it is found in the Resources directory.
The file was imported usicg terminal with this command:
mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json   

## Project Parts

### Part 1
Data Import, cleaning, and investigation happens in the NoSQL_setup_starter.ipynb file
* Import the data provided in the establishments.json file from your Terminal. Name the database uk_food and the collection establishments. Copy the text you used to import your data from your Terminal to a markdown cell in your notebook.

### Part 2
Creation of the Panang Flavours record happens in the NoSQL_setup_starter.ipynb file
* Insert the new halal restaurant *Panang Flovours* opened in Greenwich to the Database.
* Update the new restauarant with the correct BusineesTypeID.

### Part 3
Analysis and table-building happens in NoSql_analysis_starter.ipynb file, to Answer the following questions:
* Which establishments have a hygiene score equal to 20?
* Which establishments in London have a RatingValue greater than or equal to 4?
* What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
* How many establishments in each Local Authority area have a hygiene score of 0? 

## Dependecies

* pymongo
* pprint
* pandas





