# Project Tournament Results
=============================

This is the code for the study of the "Full Stack Web Developer Nanodegree" on Udacity.

This project requires defining the database schema (SQL table definitions) for a Swiss tournament system and writing a Python module that uses the PostgreSQL database to keep track of players and matches in a game tournament.

The game tournament uses the Swiss system for pairing up players in each round: players are not eliminated, and each player is paired with another player with the same number of wins, or as close as possible.


In this project:

- Database scheme was designed at first to fulfill Swiss tournament system; 
- PostgreSQL database was used to implement this scheme; 
- Python module was wrote to interact with the database and rank the players in the tournament.

How to Run:


From a GitHub shell:
 1. cd FSND-Virtual-Machine/vagrant
 2. vagrant up 
 3. vagrant ssh 
 4. cd /vagrant/tournament
 5. psql -f tournament.sql 
 6. python tournament_test.py

You will see the information of noticing successful running.


