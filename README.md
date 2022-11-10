# rcg-db-mssql-oracle-as400db2-snowflake
Accessing data from disparate systems using Database connector to connect to RDBMS, Legacy and SaaS databases. Establishing the relationship between tables using DataWeave 2.0

# MuleSoft Flow
![image](https://user-images.githubusercontent.com/104389334/201210993-9da51103-61a5-4998-bf81-4b06b103573f.png)

# Tables Entity Relationship Diagram 
![image](https://user-images.githubusercontent.com/104389334/201212021-5ec4acd9-d0c0-4c75-9e58-1d0e595bac4a.png)

# Database Connector - One connector to connect them all

# RDBMS : Microsoft SQL Databse - 

![image](https://user-images.githubusercontent.com/104389334/201204651-15dc50e8-b76c-4e03-aaf7-fcd40ab600d7.png)

# RDBMS : Oracle Database - 

![image](https://user-images.githubusercontent.com/104389334/201209836-998d50da-5f71-4afe-a057-84ddf78de104.png)

# Legacy : AS400/DB2 Server - 

a) Add Maven dependency - https://mvnrepository.com/artifact/net.sf.jt400/jt400
b) "Library" value should be equated to database in JDBC URL
c) Driver class name - com.ibm.as400.access.AS400JDBCDriver

![image](https://user-images.githubusercontent.com/104389334/201210078-db441945-c79d-49be-b908-7b07626e0703.png)

# SaaS Cloud : Snowflake Datawarehouse -

a) Add Maven dependency - https://mvnrepository.com/artifact/net.snowflake/snowflake-jdbc
b) Driver class name - net.snowflake.client.jdbc.SnowflakeDriver

![image](https://user-images.githubusercontent.com/104389334/201210591-149a47a5-d726-4a31-835c-c021c14f803b.png)

Establishing the Enitity Relationship using "Scatter Gather" and DataWeave 2.0.
