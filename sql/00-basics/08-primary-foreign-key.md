# Primary and Foreign Key in SQL

## What is a Primary Key?

- A Primary Key is a column or a set of columns in a table that uniquely identifies each row in that table.
- It must contain unique values and cannot contain NULL values.
- A table can have only one Primary Key, which can consist of single or multiple columns (composite key).
- Primary Keys help maintain the integrity of the data by ensuring that each record can be uniquely identified.

## What is a Foreign Key?

- A Foreign Key is a column or a set of columns in one table that refers to the Primary Key in another table.
- It establishes a relationship between the two tables, enforcing referential integrity.
- Foreign Keys can contain duplicate values and can also contain NULL values.
- They help maintain the consistency of data across related tables by ensuring that the value in the Foreign Key column matches a value in the referenced Primary Key column.
- A table can have multiple Foreign Keys, each linking to different tables.
- Foreign Keys are used to represent relationships such as one-to-many and many-to-many between tables.
