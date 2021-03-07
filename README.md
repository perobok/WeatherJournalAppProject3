# Weather-Journal App Project

## Overview
This is simple page which containes ability to pull data from external API. Customer should enter zip code for USA and the app wil return current weather data. 

## Detail explanation
I created server using node express and configured on witch port it will be running. After that I defined GET and POST routes for the app. GET route is used to pass data to client side and POST to receive it and store inside projectData object declared at the top of server.js file. 
In app.js first I created variables for api key and api url. Then I created async function where I took data from form and pass it to getData function. This function will fetch api and request metric units. 
After we receive data from API then we will post it usin POST method in function postData. 

## Instructions
I putted comments in front of functions to explain my methods so it is not important to add to many details about the app. 
