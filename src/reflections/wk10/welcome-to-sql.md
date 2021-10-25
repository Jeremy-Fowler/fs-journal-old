# Welcome To SQL

## In a SQL table, what is the difference between information in a row and information in a column?

Columns are properties, and rows are objects

## Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.

CREATE TABLE houses(
  id int NOT NULL,
  name VARVHAR(255) NOT NULL,
  age int NOT NULL,
  description VARCHAR(255 NOT NULL)
);

## What is the difference between the following statements

## DELETE FROM table_name;
## DROP TABLE table_name;

DELETE FROM will delete all rows in a table, while DROP TABLE will delete all rows and columns.

https://github.com/Jeremy-Fowler/knights