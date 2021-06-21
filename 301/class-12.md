# Mongo and Mongoose

## Five differences between SQL and NoSQL databases:

1. SQL databases are primarily called as Relational Databases (RDBMS); whereas NoSQL database are primarily called as non-relational or distributed database.
1. SQL databases are table based databases whereas NoSQL databases are document based, key-value pairs, graph databases or wide-column stores. This means that SQL databases represent data in form of tables which consists of n number of rows of data whereas NoSQL databases are the collection of key-value pair, documents, graph databases or wide-column stores which do not have standard schema definitions which it needs to adhered to.
1. SQL databases have predefined schema whereas NoSQL databases have dynamic schema for unstructured data.
1. SQL databases are vertically scalable whereas the NoSQL databases are horizontally scalable. SQL databases are scaled by increasing the horse-power of the hardware. NoSQL databases are scaled by increasing the databases servers in the pool of resources to reduce the load.
1. SQL databases uses SQL ( structured query language ) for defining and manipulating the data, which is very powerful. In NoSQL database, queries are focused on collection of documents. Sometimes it is also called as UnQL (Unstructured Query Language). The syntax of using UnQL varies from database to database.

## What kind of data is a good fit for an SQL database?

- The complex query intensive environment

## Give a real world example.

Replication: By replicating MySQL database across multiple nodes the work load can be reduced heavily increasing the scalability and availability of business application

## What kind of data is a good fit a NoSQL database?

- The hierarchical data storage as it follows the key-value pair way of storing data similar to JSON data.

## Give a real world example

- big data

## Which type of database is best for hierarchical data storage?

- NoSQL

## Which type of database is best for scalability?

- SQL

## What does SQL stand for?

SQL stands for Structured Query Language. SQL is used to communicate with a database. According to ANSI (American National Standards Institute), it is the standard language for relational database management systems.

## What is a relational database?

A relational database is a type of database that stores and provides access to data points that are related to one another. Relational databases are based on the relational model, an intuitive, straightforward way of representing data in tables. In a relational database, each row in the table is a record with a unique ID called the key. The columns of the table hold attributes of the data, and each record usually has a value for each attribute, making it easy to establish the relationships among data points.

## What type of structure does a relational database work with?

The relational model means that the logical data structures—the data tables, views, and indexes—are separate from the physical storage structures. This separation means that database administrators can manage physical data storage without affecting access to that data as a logical structure.

## What is a ‘schema’?

A database schema represents the logical configuration of all or part of a relational database. It can exist both as a visual representation and as a set of formulas known as integrity constraints that govern a database. These formulas are expressed in a data definition language, such as SQL.

## What is a NoSQL database?

NoSQL, which stands for “not only SQL,” is an approach to database design that provides flexible schemas for the storage and retrieval of data beyond the traditional table structures found in relational databases.

## How does it work?

NoSQL is an approach to databases that represents a shift away from traditional relational database management systems (RDBMS). ... Relational databases rely on tables, columns, rows, or schemas to organize and retrieve data. In contrast, NoSQL databases do not rely on these structures and use more flexible data models.

## What is inside of a Mongo database?

A document is a representation of a single entity of data in the MongoDB database. A collection consists of one or more related objects. A major difference exists between MongoDB and SQL, in that documents are different from rows. Row data is flat, with one column for each value in the row.

## Which is more flexible - SQL or MongoDB? and why.

MongoDB is more fast and scalable in comparison to the SQL server. MongoDB doesn't support JOIN and Global transactions but the SQL server supports it. MongoDB supports a big amount of data but the MS SQL server doesn't. MongoDB support Agile practices but MS SQL server doesn't support it.

## What is the disadvantage of a NoSQL database?

Disadvantages. NoSQL databases don't have the reliability functions which Relational Databases have (basically don't support ACID). This also means that NoSQL databases offer consistency in performance and scalability.

## Things I want to know more about
