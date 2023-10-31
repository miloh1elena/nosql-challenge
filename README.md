# NoSQL Challenge - UK Food Standards Agency Data Analysis

This repository contains code and data for the NoSQL Challenge, which focuses on analyzing food hygiene ratings data collected by the UK Food Standards Agency. The goal is to provide insights to help the food magazine "Eat Safe, Love" make informed decisions about where to focus future articles.

## Part 1: Database and Jupyter Notebook Set Up

Set up the database and Jupyter Notebook environment. Key tasks include:
- Importing data from the "establishments.json" file into a MongoDB database named "uk_food" and a collection named "establishments."
- Listing databases in MongoDB, confirming the presence of "uk_food."
- Confirming the existence of the "establishments" collection and displaying a sample document.
- Importing necessary libraries like PyMongo and Pretty Print (pprint).

## Part 2: Update the Database

The "Eat Safe, Love" magazine editors have specific requirements for the database. 
- Add a new halal restaurant, "Penang Flavours," to the database.
- Find the BusinessTypeID for "Restaurant/Cafe/Canteen" and update "Penang Flavours" with the correct BusinessTypeID.
- Remove all establishments in the "Dover Local Authority."
- Update number values from strings to numeric types using update_many.

## Part 3: Exploratory Analysis

This section involves answering specific questions to assist the magazine editors in making data-driven decisions. The analysis includes:
- Identifying establishments with a hygiene score of 20.
- Locating establishments in London with a RatingValue greater than or equal to 4.
- Finding the top 5 establishments with a RatingValue of 5, sorted by the lowest hygiene score and proximity to "Penang Flavours."
- Determining the number of establishments in each Local Authority area with a hygiene score of 0, sorting the results and listing the top ten local authority areas.
