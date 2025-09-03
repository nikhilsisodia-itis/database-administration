# ER Model

## What is ER Model?

- The Entity-Relationship (ER) Model is a conceptual framework used to describe the data structures and relationships within a database.
- It provides a visual representation of entities (objects) and their attributes, as well as the relationships between them.
- ER diagrams are commonly used in the database design process to communicate the structure of the data and to identify potential issues before implementation.
- The ER Model is a foundational concept in database design and is widely used in conjunction with the relational model.

## Components of ER Model

1. **Entity**: An entity is a distinct object or thing in the database that is represented by a set of attributes. For example, a "Customer" entity may have attributes like `CustomerID`, `Name`, and `Email`.
2. **Attribute**: An attribute is a property or characteristic of an entity. Attributes can be simple (single-valued) or composite (multi-valued). For example, a "Name" attribute may be composite, consisting of `FirstName` and `LastName`.
3. **Relationship**: A relationship is an association between two or more entities. Relationships can be one-to-one, one-to-many, or many-to-many. For example, a "Customer" may place multiple "Orders", representing a one-to-many relationship.
4. **Primary Key**: A primary key is a unique identifier for an entity. It ensures that each instance of the entity can be uniquely identified. For example, `CustomerID` may serve as the primary key for the "Customer" entity.
5. **Foreign Key**: A foreign key is an attribute that creates a link between two entities. It refers to the primary key of another entity, establishing a relationship between them. For example, `CustomerID` in the "Order" entity may serve as a foreign key referencing the "Customer" entity.

## ER Diagram

- An ER diagram is a visual representation of the ER model, showing entities, attributes, and relationships.
- It uses specific symbols to represent different components:
  - Rectangles represent entities.
  - Ovals represent attributes.
  - Diamonds represent relationships.
- ER diagrams are useful for database design, as they provide a clear overview of the data structure and relationships.
