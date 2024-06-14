# dotnetAPI
# ASP.NET Challenge

Practice using ASP.NET to create and manage routes in a web application.

## Setup

Make sure you have Git and .NET SDK (v6.0) installed.

1. clone your copy, and cd into it
2. Run `dotnet restore` to install all the dependencies
3. Run `dotnet run` to start the server (should error due to routes not having a return)

This app already has the basic structure and templates created. Your job is to fill out the necessary functions in the controllers so the routes can perform the required operations.

Note: You won't be able to access some routes without errors until you've completed the challenges below. For testing you may want to comment out routes you have not fixed yet.

## Checking your work

Run the project and then navigate to localhost url/swagger there you will be able to test the functioning of each test



## Challenge 1: List all games and results

Add a new GET route in the `GamesController` to retrieve all games from the `games` 

This route should be accessible via `/games`. Once you've finished it you should be able to see a list of all games and their results through swagger.

## Challenge 2: Delete a game record

Add a new DELETE route in the `GamesController` to delete a game record based on its ID. After deletion, it should return the remaining games.

This route should be accessible via `/games/{id}`. Once you've finished it you should be able to delete a specific game and see the updated list of remaining games.

## Challenge 3: Add a game result

Add a new POST route in the `GamesController` to allow users to add a new game result. This route should return all the game results after the new one is added.

This route should be accessible via `/games/add`. Once you've finished it you should be able to add a new game result and see the updated list of all game results.

