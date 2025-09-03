# Introduction to SQL

## What is SQL?

- SQL- Structured Query Language
- A programming language used to communicate with the relational database.
- It is used for querying (requesting), updating, and managing data in a relational database.
- SQL is essential for database administrators, developers, and data analysts.

## What is a Query?

- A query is a request for data or information from a database.
- Queries are written in SQL and can be used to retrieve, update, or delete data.
- There are different types of queries, including SELECT, INSERT, UPDATE, and DELETE.
- Also known as SQL statements (instructions).
- Statements are instructions written to perform specific tasks in the database.

## Parts of a SQL Query

- Clause: A clause is a component of a SQL statement that performs a specific function. Examples include SELECT, FROM, WHERE, and ORDER BY.
- Identifiers: Identifiers are names used to identify database objects such as tables, columns, and indexes. They must be unique within their context. Examples include `employees`, `first_name`, and `salary`.
- Keyword: Keywords are reserved words in SQL that have a special meaning and are used to perform specific actions. Examples include SELECT, INSERT, UPDATE, DELETE, and WHERE.
- Expression: An expression is a combination of values, operators, and functions that evaluates to a single value. Expressions are used in SQL to perform calculations, manipulate data, and filter results.
- Predicate: A predicate is a condition that evaluates to true or false and is used to filter records. Predicates are often found in the WHERE clause. It is a single true/false test.
- Operator: An operator is a symbol that performs a specific operation on one or more operands. Examples include arithmetic operators (+, -, *, /), comparison operators (=, <, >), and logical operators (AND, OR, NOT).
- Conditions: Conditions are expressions that evaluate to true or false and are used to filter records. Conditions are often found in the WHERE clause. It can be combination of predicates, using logical operators.
- Value: A value is a specific piece of data that can be used in a SQL statement. Values can be numbers, strings, dates, or other data types.
- Statement: A statement is a complete SQL command that performs a specific action on the database. Statements can be simple, such as a single SELECT query, or complex, involving multiple clauses and subqueries.

## Declarative Nature of SQL

- SQL is a declarative language, which means that you specify what you want to achieve without having to define how to achieve it.
- In SQL, you describe the desired result, and the database management system (DBMS) determines the most efficient way to execute the query.
- This is in contrast to imperative programming languages, where you must provide a step-by-step procedure to achieve a specific outcome.
