# nosql-challenge
---
**This challenge is divided into 2 parts**

## Part 1: Database and Jupyter Notebook Set Up
---
**For this section, we have used NoSQL_setup_starter.ipynb to accomplish the following tasks:**

-Import the data provided in the establishments.json file from your Terminal.
-Name the database uk_food and the collection establishments. 
-Copy the text used to import our data from our Terminal to a markdown cell in our notebook.
-Import the necessary libraries .
-Create an instance of the Mongo Client.
-Confirm that we created the database and loaded the data properly:
-List the databases you have in MongoDB. Confirm that uk_food is listed.
-List the collection(s) in the database to ensure that establishments is there.
-Find and display one document in the establishments collection using find_one and display with pprint.
-Assign the establishments collection to a variable to prepare the collection for use.

### Part 2: Update the Database
---
**For this section, we'have used  NoSQL_setup_starter.ipynb to accomplish the following tasks:**

- Add additional information to the database.
- Find the BusinessTypeID for "Restaurant/Cafe/Canteen" and return only the BusinessTypeID and BusinessType fields.
- Update the new restaurant with the BusinessTypeID you found.
- Remove any establishments within the Dover Local Authority from the database, and check the number of documents to ensure they were deleted.
- Use update_many to convert latitude and longitude to decimal numbers.
- Use update_many to convert RatingValue to integer numbers.

### Part 3: Exploratory Analysis
---
**For this section, we'have used  NoSQL_setup_starter.ipynb to accomplish the following tasks:**

- Use NoSQL_analysis_starter.ipynb for this section of the challenge.
- Use the following questions to explore the database, and find the answers, so we can provide them to the magazine editors.
- Use count_documents to display the number of documents contained in the result.unless otherwise stated.
- Display the first document in the results using pprint.
- Convert the result to a Pandas DataFrame, print the number of rows in the DataFrame, and display the first 10 rows.
- Answer the following questions:
  * Which establishments have a hygiene score equal to 20?
  * Which establishments in London have a RatingValue greater than or equal to 4?  
  * What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene
score, nearest to the new restaurant added, "Penang Flavours"?
  * How many establishments in each Local Authority area have a hygiene score of 0? Sort the
results from highest to lowest, and print out the top ten local authority areas.
---
