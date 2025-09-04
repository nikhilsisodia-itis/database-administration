# Tables in SQL

## What are Tables in SQL?

- Tables are the fundamental building blocks of a relational database.
- They store data in rows and columns, similar to a spreadsheet.
- Each table represents a specific entity, such as customers or orders.
- Tables can be related to one another through foreign keys.
- A table consists of columns (attributes) and rows (records).
- A table consists of all the data related to an Object.
- Degree of a Table = number of attributes (columns) it has.
- Cardinality of a Table = number of unique records (rows) it has.

## What is an Object?

- An Object is a real-world entity that can be distinctly identified.
- Objects can be physical items, like a car or a book, or they can be abstract concepts, like a customer or an order.
- Each Object has attributes (properties) that describe its characteristics and behaviors.
- Objects can also have relationships with other Objects, which can be represented in a database using foreign keys.

## Columns in SQL

- Columns are the vertical entities in a table that represent attributes of the Object.
- Each column has a specific data type, such as integer, varchar, date, etc.
- Columns can have constraints, to enforce data integrity.
- The combination of all columns in a table defines the structure of the data stored in that table.

## Domain OR Constraints in SQL

- Domain or constraints in SQL are rules that control what kind of data can go into a column in a table.
- They help make sure the data is correct and consistent.
- Domain means the allowed set of values for a column (for example, only numbers, only dates, or only specific words).
- Constraints are rules you set on columns, like:
  - NOT NULL: The column must have a value.
  - UNIQUE: All values in the column must be different.
  - CHECK: The value must meet a specific condition (for example, age > 0).
  - DEFAULT: Sets a default value if none is provided.
  - FOREIGN KEY: Ensures referential integrity by linking to a primary key in another table.
  - PRIMARY KEY: Uniquely identifies each row in a table.

## Rows in SQL

- Rows are the horizontal entities in a table that represent individual records of the Object.
- Each row contains a unique instance of data for the attributes defined by the columns.
- Rows can be added, updated, or deleted, allowing for dynamic data management.
- The combination of all rows in a table defines the dataset for that specific Object.
- A single record of data is called a Tuple.
- Every Tuple follows the column's constraints and data types.
- Cardinality refers to the number of unique tuples in a column.
