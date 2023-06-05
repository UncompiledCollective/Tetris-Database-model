# Tetris-Database-model
Database model for mySQL database used in tetris project
It's a single database, two tables. One of them hold scores, user name, and other statistics.
The other stores avatars as longblob(s). Every avatar gets a unique ID on client level.
Client requests these assets through the node.js API.
