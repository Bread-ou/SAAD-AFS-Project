# 8. Choosing To Split The Database

Date: 21-12-2023

## Status

Accepted

## Context

In a system implementing SOA, there are options for database management, including using a single comprehensive database, 
dividing the database into separate parts, or assigning a dedicated database to each component.

## Decision

The database will be split into two databases, one will be a general database housing data such as account information, queries, query responses, and other general data.
The database structure will be split into two distinct systems. 
The first one, a relational database, will store structured general data such as account information, queries, and branch-related data; capitalizing on its ability to handle complex queries and maintain data integrity. 
The second, a NoSQL database, specifically using MongoDB, will be dedicated to visa application data. 
This choice is due to MongoDB's efficiency in handling read/write operations and because there is only one entity in that database; that being the visa applications.


## Consequences
* **Benefits of Both:** The system capitalizes on the unique advantages of each database type.
NoSQL offers scalability and performance for dynamic visa application data, while the SQL database excels in handling complex queries and structured data like account and query information.
* **Management Complexity:** The approach necessitates a sophisticated data management system to seamlessly operate and manage the application.
