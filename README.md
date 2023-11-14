# nosql-challenge
Module 12 Challenge
I have been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

The NoSQL_setup.ipynb sets up and updates the database. The NoSQL_analysis.ipynb queries relevant information for analyses and converts results into Pandas DataFrame. The data provided in the establishments.json file was imported using Terminal with mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json.

The following questions are answered from the analysis:

Question 1: Which establishments have a hygiene score equal to 20?

Question 2: Which establishments in London have a RatingValue greater than or equal to 4? 

Question 3: What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"? 

Question 4: How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas. 