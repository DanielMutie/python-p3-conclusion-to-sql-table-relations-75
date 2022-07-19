# Conclusion to Table Relations in SQL

## Learning Goals

- Use primary and foreign keys to create the relations in a relational database.
- Use `INNER JOIN` and `LEFT JOIN` to retrieve relevant data for members of
  one table in other tables.
- Use joins to create one-to-many and many-to-many relationships between tables.

***

## Key Vocab

- **Primary Key**: a number that uniquely identifies one record in a table.
- **Foreign Key**: a column or group of columns that connects one table to
  another.
- **Join**: a query that returns related records from multiple tables in a
  single record.
- **One-to-Many**: a type of relationship between tables where one record in
  table A is connected to multiple records in table B. **e.g.** One person
  ordering multiple drinks at a bar.
- **Many-to-Many**: a type of relationship between tables where multiple
  records in table A are connected to multiple records in table B. **e.g.**
  Students have many classes and classes have many students.

***

## Conclusion

We've established that SQL is a useful programming language to know, and that
the majority of databases you'll work with will have more than one table. As
demonstrated in this section, we've been able to learn and apply concepts that
connect together these tables in various ways. These table relationships are
important to illustrate real-world data.

In this section we covered:

- The structure of a relational database as tables
- How to associate data tables using a foreign key column
- Different types of joins
- Relationship types, such as "one-to-many" and "many-to-many"

We can now distinguish the different types of relationships between data in a
database, and use SQL to query data across multiple tables.

With the ability to define relationships between different tables we can model
data that is more accurate to the real world!

***

## Resources

- [What is a Relational Database? - Google Cloud](https://cloud.google.com/learn/what-is-a-relational-database)
- [Difference between Primary Key and Foreign Key - GeeksforGeeks](https://www.geeksforgeeks.org/difference-between-primary-key-and-foreign-key/)
- [SQL Joins - W3Schools](https://www.w3schools.com/sql/sql_join.asp)
- [Airtable's guide to many-to-many relationships](https://support.airtable.com/hc/en-us/articles/218734758-Airtable-s-guide-to-many-to-many-relationships)
- [Practice SQL Queries on SQLBolt](http://sqlbolt.com/lesson/select_queries_review)
- [dbdiagram.io: ERD Drawing Tool](https://dbdiagram.io)
