
In this project, I used a SQLite database containing weather station data. I used SQL Alchemy to work with this database in Python. First, I looked at the database structure and saved references to the tables so that I could easily access them later. Then, I created a connection to the database to run queries and fetch data.
The database has two tables: one for measurements (like precipitation and temperature) and one for stations. I focused on getting data from the last 12 months, specifically looking at precipitation and temperature information.
Using flask, it provided the data in JSON format, which is easy for other programs to read. The application has routes that users can access to get different types of data in order to look at a particular variable in this situation.





