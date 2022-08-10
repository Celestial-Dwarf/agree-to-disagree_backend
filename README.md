# Agree to Disagree - Backend

## Description:
- In creating our app, Agree to Disagree, we utilized a backend server to hold our initial seed foods as well as any foods that are added to the database through consumer-facing app.

## User Stories: 
- As a user I would like to be able to access all available foods in the database
- As a user, I would like to be able to add customized foods to the database
- As a user, I would like to be able to remove and edit items from the database

## Technologies Used:
- The back end for this app was built with:
    - MongoDB
    - Mongoose
    - Express
    - Node.js

## Installation Instructions:
- If you prefer to set this app up using your own database:
    - Fork this repository
    - Navigate to desired folder location in terminal and clone repo
    - npm i dotenv
    - Create .env file and set DATABASE_URL='your database url here'
    - In terminal run "node db/seeds.json"
- Feel free to create a pull request back to this repo if you'd like to submit changes for review!