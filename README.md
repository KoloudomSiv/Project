# Project
##Introduction
In this project, we will be creating a small game of the famous Rock Paper Scissors game using python.The player will be able to play with the computer.
There will also be a database where you can see the score from all games.The game keeps track of the player's wins and losses using a PostgreSQL database. Player's names and ages are used to uniquely identify them in database.
## Prerequisites
1. Python 3.x
2. PostgreSQL database server installed and running
3. psycopg2 library installed (pip install psycopg2)
## setupp
1. Install the required libraries using the following command:
2. Set Up your PostgreSQL database with the following connection details:
- Database name: posgres
- User: posgres
- Password: heng
- Host: localhost
- port: 5432
## Code description
The Python script rps_game.py connects to the PostgreSQL database, gets player information, plays the RPS game, updates scores, and handles the game loop.
## Acknowledgement
This simple project was created for a group project during our python class about python and database connectivity.
