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

HBASE 	RDBMS
Schema-less in database	Having fixed schema in database
Column-oriented databases	Row oriented data store
Designed to store De-normalized data	Designed to store Normalized data
Wide and sparsely populated tables present in HBase	Contains thin tables in database
Supports automatic partitioning	Has no built in support for partitioning
Well suited for OLAP systems	Well suited for OLTP systems
Read only relevant data from database	Retrieve one row at a time and hence could read unnecessary data if only 
                                        some of the data in a row is required
Structured and semi-structure data can be stored and processed using HBase	Structured data can be stored and 
                                                                            processed using RDBMS
Enables aggregation over many rows and columns	Aggregation is an expensive operation
