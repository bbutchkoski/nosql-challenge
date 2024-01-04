# nosql-challenge

The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

# Part 1: Database & Jupyter Notebook Set Up

Include the mongoimport command text you used to import establishments.json in a markdown cell at the beginning of your Jupyter notebook file

The mongoimport command text correctly drops any existing establishments collection before importing establishments.json into MongoDB 

The database is named uk_food and the collection is named establishments 

Correctly imports PyMongo and Pretty Print 

An instance of the Mongo Client is created 

Lists the databases you have in Mongo, which includes uk_food 

Lists the collection(s) in the uk_food database, which includes establishments in the output (

Uses find_one() and pprint to display one document in the establishments collection 

The establishments collection is assigned to a variable

# Part 2: Update the Database

The supplied data for the "Penang Flavours" restaurant is correctly inserted into the establishments collection 

A query is performed to find the BusinessTypeID for "Restaurant/Cafe/Canteen" and returns only the BusinessTypeID and BusinessType fields 

The "Penang Flavours" document is updated with the correct value for BusinessTypeID 

A query is correctly performed to delete all the documents in the collection where "Dover Local Authority" is the value for LocalAuthorityName 

A count_documents() check is performed before and after the removal of the Dover documents to ensure the documents were removed 

An update_many() query is performed to convert the latitude and longitude fields from strings to decimal numbers and RatingValue to integers 

# Part 3 - Explatory Analysis 

Question 1: Which establishments have a hygiene score equal to 20?
Question 2: Which establishments in London have a RatingValue greater than or equal to 4?
Question 3: What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
Question 4: How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.


