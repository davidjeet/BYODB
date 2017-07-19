# BYODB

"The Layer Concept" by FoundationDB: https://foundationdb.com/key-value-store/white-papers/the-layer-concept

"When you choose a database today, you're not choosing one piece of technology, you're choosing three: 

1. Storage technology, 
2. Data model, and 
3. API/query language.
 
For example, if you choose Postgres, you are choosing the Postgres storage engine, a relational data model, and the SQL query language. If you choose MongoDB you are choosing the MongoDB distributed storage engine, a document data model, and the MongoDB API. In systems like these, features are interwoven between all of the layers. For example, both of those systems provide indexes, and the notion of an index exists in all three layers."

---

# Technology

This would be on .NET Core

Would leverage storage engine that windows uses - ESE 
Or lightening.net??? (the latter is promising https://github.com/CoreyKaylor/Lightning.NET because it is based on .NET Core)

Some other interesting articles:
https://www.codeproject.com/Articles/1029838/Build-Your-Own-Database


- Had an idea to "double-index" (hash and range) for everything.
- Also, do we index on disk or in memory???  


