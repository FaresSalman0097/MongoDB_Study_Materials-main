**MongoDB Interview Questions**

    1. What are NoSQL databases? What are the different types of NoSQL databases?
            NoSQL means Not Only SQL which is a non-relational database used to store data in non tabular form.
            # Types
            Document-based databases
            Key-value stores
            Column-oriented databases
            Graph-based databases
    2. What is MongoDB?
            MongoDB is a document-oriented NoSQL database used for high volume data storage. Instead of using tables and rows as in the traditional relational databases, MongoDB makes use of collections and documents. Documents consist of key-value pairs which are the basic unit of data in MongoDB. Collections contain sets of documents and function which is the equivalent of relational database tables.
    3. What are Indexes in MongoDB?
            MongoDB uses indexing in order to make the query processing more efficient. If there is no indexing, then the MongoDB must scan every document in the collection and retrieve only those documents that match the query. Indexes are special data structures that stores some information related to the documents such that it becomes easy for MongoDB to find the right data file. The indexes are order by the value of the field specified in the index. 
            Example:
            db.mycol.createIndex({“age”:1})
            {
            “createdCollectionAutomatically” : false,
            “numIndexesBefore” : 1,
            “numIndexesAfter” : 2,
            “ok” : 1
            }
    
    4. What are the types of Indexes available in MongoDB?
    5. Explain Index Properties in MongoDB?
    6. How many indexes does MongoDB create by default for a new collection?
    7. Can you create an index in an array field in MongoDB?
    8. Why does Profiler use in MongoDB?
    9. How to remove attribute from MongoDB Object?
    10. What is "Namespace" in MongoDB?
    11. What is Replication in Mongodb?
    12. What is Replica Set in MongoDB?
    13. How does MongoDB ensure high availability?
    14. What is an Embedded MongoDB Document?
    15. How can you achieve primary key - foreign key relationships in MongoDB?
    16. When should we embed one document within another in MongoDB?
    17. How is data stored in MongoDB?
    18. What are the differences between MongoDB and SQL-SERVER?
    19. How can you achieve transaction and locking in MongoDB?
    20. When to Use MongoDB Rather than MySQL?
    21. How MongoDB supports ACID transactions and locking functionalities?
    22. What are the best practices for MongoDB Transactions?
    23. Explain limitations of MongoDB Transactions?
    24. Should I normalize my data before storing it in MongoDB?
    25. What is upsert operation in MongoDB?
    26. Is there an "upsert" option in the mongodb insert command?
    27. How to perform a delete operation in MongoDB?
    28. If you remove a document from database, does MongoDB remove it from disk?
    29. Explain the structure of ObjectID in MongoDB?
    30. Can one MongoDB operation lock more than one database?
    31. What is Sharding in MongoDB?
    32. What is Aggregation in MongoDB?
    33. Why are MongoDB data files large in size?
    34. How can you isolate your cursors from intervening with the write operations?
    35. Does MongoDB provide a facility to do text search?
    36. What is a Storage Engine in MongoDB?
    37. How to condense large volumes of data in Mongodb?
    38. Explain relationships in MongoDB?
    39. What is splitting in MongoDB?
    40. Explain what is horizontal scalability in mongodb?
