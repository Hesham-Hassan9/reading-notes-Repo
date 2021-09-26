# No SQL vs SQL

1. Fill in the chart below with five differences between SQL and NoSQL databases:

| SQL                                                      | NoSQL                                                                                                                            |
|----------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------|
| Relational Databases                                     | non-relational or distributed database                                                                                           |
| predefined schema                                        | dynamic schema for unstructured data                                                                                             |
| vertically scalable                                      | horizontally scalable.                                                                                                           |
| databases are not best fit for hierarchical data storage | database fits better for the hierarchical data storage as it follows the key-value pair way of storing data similar to JSON data |

2. What kind of data is a good fit for an SQL database?

   If your data is highly structured and the associations between program entities are clearly defined (for example, if you are developing a POS system where you need to store customer orders and product records), then traditional SQL-based databases are best suited.

* Give a real world example

      MySql, Oracle, Sqlite, Postgres and MS-SQL

3. What kind of data is a good fit a NoSQL database?

    Therefore, if your application requires high availability and scalability, a NoSQL database built on BASE properties may be suitable. Choose NoSQL if you have or need: Semi-Structured or Unstructured Data/Flexible Schema. Predefined access paths and query patterns.

* Give a real world example

      MongoDB, BigTable, Redis, RavenDb, Cassandra, Hbase, Neo4j and CouchDb

4. Which type of database is best for hierarchical data storage?

    Document-based databases like MongoDB and Redis are great for small hierarchical data with a relatively small number of children per entry

5. Which type of database is best for scalability?

    The clear winner with more than 1/3 of the multiple database types being used is the combination of MySQL and MongoDB. While MongoDB is often considered an alternative to MySQL, the two databases work well together when properly designed. The second most popular combination was MySQL and PostgreSQL together.
