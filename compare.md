### Source1 VS Source2:

| a | a | a |
| ----------- | --------------------------------------------- | --------------------------------------------- |
| a | a | a |
| a | a | a |
| a | a | a |
| a | a | a |
| a | a | a |
| a | a | a |
| a | a | a |
| a | a | a |
| a | a | a |
| a | a | a |
| a | a | a |
| a | a | a |



### Relational Database VS NoSQL Database:

| Type    | Relational Database    | NoSQL Database |
| ----------- | --------------------------------------------- | --------------------------------------------- |
| Velocity | Handles data coming in low velocity           | Handles data coming in high velocity    |
| Volume | Handles data in the moderate volume           | Handles data in very high volume    |  
| Type | Manages structured data                       | Manages structured unstructured and semi-structured data    |   
| Transaction | Supports complex transactions (with joins)    | Supports simple transactions    |  
| Failure | single point of failure with failover         | No single point of failure    |  
| Scalability | Gives read scalability                        | Gives both read and write scalability    |  
| Deployment | Centralized deployments                       | Decentralized deployments    |  
| Depl. mode | Deployed in vertical fashion                  | Deployed in Horizontal fashion    |  
| Destination | Transactions written in one location          | Transaction written in many locations    |  
| Source | Data arrive from one or few locations         | Data arrive from many locations     |

### HBase VS RDBMS

While comparing HBase with Traditional Relational databases, we have to take three key areas into consideration. 
Those are data model, data storage, and data diversity.

| a | RDBMS | HBASE |
| ----------- | --------------------------------------------- | --------------------------------------------- |
| a | Having fixed schema in database | Schema-less in database |
| a | Row oriented data store | Column-oriented databases |
| a | Designed to store Normalized data | Designed to store De-normalized data |
| a | Contains thin tables in database | Wide and sparsely populated tables present in HBase |
| a | Has no built in support for partitioning | Supports automatic partitioning |
| a | Well suited for OLTP systems | Well suited for OLAP systems |
| a | Retrieve one row at a time and hence could read unnecessary data if only some of the data in a row is required | Read only relevant data from database |
| a | Structured data can be stored and processed using RDBMS | Structured and semi-structure data can be stored and processed using HBase |
| a | Aggregation is an expensive operation | Enables aggregation over many rows and columns |


### Hive VS HBase:

| Features | Hive | HBase |
| ----------- | --------------------------------------------- | --------------------------------------------- |
| Data base model | Relational DBMS | Wide Column store |
| Data Schema | With Schema | Schema- free |
| SQL Support | Yes it uses HQL(Hive query language) | No |
| Partition methods | Sharding | Sharding |
| Consistency Level | Eventual Consistency | Immediate Consistency |
| Secondary indexes | Yes | No |
| Replication Methods | Selectable replication factor | Selectable replication factor |

