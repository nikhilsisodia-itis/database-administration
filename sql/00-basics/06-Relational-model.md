# Relational Model

## What is Relational Model?

- The Relational Model is a data model that organizes data into tables (relations) consisting of rows and columns.
- Each table represents a specific entity, and each row in the table represents a unique instance of that entity.
- The columns in the table represent the attributes of the entity, and each attribute has a specific data type.
- The Relational Model is based on the principles of set theory and first-order predicate logic.
- It provides a clear and intuitive way to represent and manipulate data, making it the foundation for most modern database systems.

## Key Concepts of Relational Model

1. **Table (Relation)**: A table is a collection of related data entries organized in rows and columns. Each table has a unique name.
2. **Row (Tuple)**: A row represents a single record in a table and contains values for each attribute. Each row is uniquely identified by a primary key.
3. **Column (Attribute)**: A column represents a specific attribute of the entity and has a defined data type (e.g., integer, varchar).
4. **Primary Key**: A primary key is a unique identifier for each row in a table. It ensures that no two rows have the same key value.
5. **Foreign Key**: A foreign key is an attribute that creates a link between two tables. It refers to the primary key of another table, establishing a relationship between them.

## Relational Algebra

- Relational algebra is a formal system for manipulating relations (tables) in the relational model.
- It provides a set of operations (e.g., selection, projection, join) that can be used to query and transform data.
- Relational algebra forms the theoretical foundation for SQL and other query languages.

## Advantages of Relational Model

- **Data Integrity**: The relational model enforces data integrity through the use of primary and foreign keys, ensuring that relationships between tables remain consistent.
- **Flexibility**: The tabular structure allows for easy modification of the database schema, such as adding or removing columns and tables.
- **Powerful Query Language**: SQL, the standard query language for relational databases, provides powerful and expressive capabilities for data manipulation and retrieval.
- **Normalization**: The relational model supports normalization, a process that reduces data redundancy and improves data integrity by organizing data into related tables.
- **ACID Compliance**: Relational databases typically adhere to ACID (Atomicity, Consistency, Isolation, Durability) properties, ensuring reliable transactions and data integrity.
