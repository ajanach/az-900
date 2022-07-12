# Database Services

## Data Types:
- **structured**: data thet can be represented using tables with very strict schema
    - each row must follow defined schema
    - some tables have defined relationships between them
    - typically used in relational databases

- **semi-structured**: 
    - data that can be represented using tables but withouth strict defined schema
    - rows must only have unique key identifier

- **unstructured**: 
    - any files in any format
    - like binary files, application files, images, movies, etd.

## Cosmos DB:
- Globally distributed NoSQL (semi-structured data) database service
- schema-less
- multiple APIs (SQL, MongoDB, Cassandra, Gremlin, Table Storage)
- Designed for
    - highly responsive (real time) applications with super low latency responses <10ms
    - multi-regional applications

<img src="..\Images\cosmosDB.png" alt="cosmosDB.png" />
    
## Azure SQL Database:
- relational database service in the cloud PaaS
- structured data service defined using schema and relationships
- rich query capabilites SQL
- high performance, relialable fully managed and secure dataase for building applications

<img src="..\Images\azureSQLDB.png" alt="azureSQLDB.png" />

## Azure SQL product family
- azure sql database: reliable relational database based on SQL server
- azure database for MySQL: azure sql version for mysql database engine
- azure database for postgreSQL: azure sql version for postgresql database negine
- azure SQL managed instance: fully fledged sql server managed by cloud provider PaaS
- azure SQL on VM: fully fledged sql server on IaaS

<img src="..\Images\azureProductFamily.png" alt="azureProductFamily.png" />