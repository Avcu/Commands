# postgreSQL Commands

| Command | Description |
| --- | --- |
| postgres -V | check the postgreSQL's version |
| psql postgres | initialize psql command line |
| \du | show the current users |
| \list | show the current databases |
| CREATE ROLE username WITH LOGIN PASSWORD 'password'; | create a user |
| ALTER ROLE username CREATEDB;  | enable user to create databases |
| psql postgres -U username | initialize psql command line for a given user |
| CREATE DATABASE new_db; | create a new database |
| GRANT ALL PRIVILEGES ON DATABASE new_db TO username; | give permissions to a given user |
| \connect new_db | connect to a database |
| \dt | show the tables in a database |
