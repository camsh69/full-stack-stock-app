# Group JavaScript Project - Full Stack Stock Tracker App

## Technologies used
- JavaScript, Node, React, Express, MongoDB

## Important
For app to work create a key.js file under client/src (this has been excluded in the .gitignore file to protect private keys).  

Obtain a key from https://www.alphavantage.co/support/#api-key and include it in the code below within the key.js file:

`import React from 'react';`

`const getApiKey = () => {`
`    return "YOUR_API_KEY_HERE";`
 `}`
 
 `export default getApiKey`

## How to run
- CD into server folder and run command ~ `npm install` to install dependencies
- Run command ~ `npm run server:dev` - the server should now be running on port 5000
- In a new terminal window but still in the server folder run command ~ `npm run seeds` to populate DB (may take a few minutes)


- CD into client folder and run command ~ `npm install` to install dependencies
- Run command ~ `npm start`
- App should be visible in browser `http://localhost:3000`

## The Brief - Shares Portfolio Application

A local trader has come to you with a portfolio of shares. She wants to be able to analyse it more effectively. She has a small sample data set to give you and would like you to build a Minimum Viable Product that uses the data to display her portfolio so that she can make better decisions.

## MVP

A user should be able to:

- view total current value.
- view individual and total performance trends.
- retrieve a list of share prices from an external API and allow the user to add shares to her portfolio.
- View a chart of the current values in her portfolio.

## Example Extensions

- Speculation based on trends and further financial modelling using projections.

## API, Libraries, Resources

- https://www.alphavantage.co/ (Requires sign up)
- https://www.highcharts.com/ HighCharts is an open-source library for rendering responsive charts.
