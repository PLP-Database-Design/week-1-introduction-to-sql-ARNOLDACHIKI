1.State and Explain the components of a DBMS(Database Management System)
(i) Database engine- the database engine is the main component of the database management system as it helps handle data storage ,retrival and helps in doing operations such as adding,updating and deleting records
(ii)Database schema-Database schema helps to define the logic structure of the database as it outlines how data is organised and how relationships are structured between different data elements
(iii)Query processor- the query processor is responsible for interprating and executing database queries by translating high level wueries written in SQL into a series of operations that the database management system can perform in order to be able to retrieve data
(iv)Database Management Interface-This is the interface through which users interact with the database management system  by allowing users to input commands or use intuitive interface to interact with the database and is responsible for prooviding access to database functionalities such as the creation of tables
(v)Transaction Management -Transaction management ensures that database transactions are processed reliably, consistently and successully or rolled back in case of failure which helps to guaranteedata intergrity and consistency
(vi)Storage Manager- the storage manager is responsible for efficient management of the physical storage of data by interacting with the file system to ensure that data is stored in a way that allows fast access and retrieval
(vii)Data dictionary-The data dictionary is a repository that stores metadata about the database and helps the database management system to understand the strucure of the database which is crucial for maintaining consistency and intergrity
(viii)Sercurity and access control-the sercurity and access control helps prevent unauthorized access and ensures the confidentiality and the intergrity of data 
(ix)Backup and recovery management- The bakup and recovery management ensures that the database can be restored to a consistent state incase of a failure by using regular backups and recovery strategies which asre crucial for maintaining data availability and reliability
(x)Concurrency control-concurrency control is a mechanism that ensures that multiple users or applications can access and modify the database system simultenously without causing conflicts or data corruption

2. What is a relational database? Give 4 examples.
A relational database is a type of database that stores and organises data in a structured format sing rows and columns that are arranged into tables
(i)Tables
(ii)Rows
(iii)Columns
(iv)Primary keys

3. State and Explain three classifications of SQL?
(i)Data defination language -The data defination language consists of sql commands that are used to define and manage database structures by allowing one to create , alter and delete database objects
(ii)Data Manipulation Language-The datamanipilation language is used to manipulate data within the database and includes sql commands for querying ,inserting ,updating and deleting dat in the tables as it focuses on managing the data stored within the tables
(iii)Data contol Language- the data control language consists of sql commands that are used to control access to data within the database by defining who can access the data and what actions they can perform ,focusing on database sercurity and permissions

4. What is the difference between a Primary Key and a Foreign Key?
A primary key is one that uniquely identifies each record in the table that is unique for each record hence cannot contain a null value and a table can have only one primary key while a foreign key is a key that establishes a relationship between two tables  which can have null values and it is not unique as multiple rows can have the same foreign key value hence a table can have multiple foreign keys

5. What is an Entity-Relationship Diagram?
An entity-relationship diagram is a visual representation of the structure of the database aas it shows the entities within a system ,the relationships between those entities and the attributes for each entity

6. What are the advantages of relational databases?
(i)Data accuracy and intergrity- Relational databases use constraints like primary keys ,foreign keys and unique constraints to ensure that the data stored is accurate and help maintain data intergrity by preventing the entry of duplicate or invalid data
(ii)Flexibility-Relational databases support a wide variety of data types and are flexible enough to accommodate changes in the database schema with minimal disruption
(iii)Data sercurity-Relational databases allow administrators to define specific access rights and permissions for users and this only ensures that only authorized users can access, modify or delete sensitive data
(iv)Data consistency and redudancy elimination-By applying normalization techniques ,relational databases reduce data redudancy and this ensures that updates or deletions are applied consistently accross all instances of a data element
(v)Relationship Management-Relational databases allow users to define and manage complex relationships between tables ,using foreign keys and joins and this enables the creation of sophisticated data models and systems with multiple interconnected tables

7. State four types of data type used to store data in tables?
(i)Numeric data types-These are used to store numerical values including integers,floating-point numbers and fixed-point numbers
(ii)Character data types-These are used to store text or string dat in tables like naess,addresses or descriptions
(iii)Date and time data types-These are used to store date and time-related information in a table
(iv)Boolean data type-This is used to store binary data that represents truth values(true or false)

8. What is the purpose of a database management system (DBMS)?  
The purpose of the database management system is to provide a systematic and efficient way to store ,manage and manipulate data in  databases by serving as intermediary between users and the database hence ensuring that data is stored in an organised manner and can be accessed and controlled in a secure way