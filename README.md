# Database Normalization

Organizing information in a relational database requires eliminating redundancy to maintain the integrity and consistency of data. If left unchecked in the initial stages of project development, this could result in serious ramifications in terms of performance and waste of resources. For instance, if there is only a single table to store the entire data set then the program has to do a full database scan even for queries that require only a few records. Moreover, if data is repeated over several rows, a single error can cause erroneous data or potential loss of information.

This [notebook](https://nbviewer.org/github/cpmalenab/database_normalization/blob/main/Creating%20Normalized%20Tables.ipynb) aims to discuss the following:

1. Demonstrate the normalization process through a sample music library database.
2. Present and discuss each *normal form* supplemented by Python code and psycopg2 library to manipulate the PostgreSQL database.
3. Define concepts behind database normalization to better understand the theoretical foundation of the topic.
4. Complement the normalized database using an Entity-Relationship Diagram.
5. Identify possible trade-offs and implications of normalizing a database.
 
