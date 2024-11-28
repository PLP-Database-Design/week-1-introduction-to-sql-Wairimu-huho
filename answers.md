# Database Management Systems (DBMS) Concepts

## 1. Components of a DBMS

A Database Management System consists of several key components:

1. **Hardware**: Physical devices like computers, storage devices, and network infrastructure that store and access the data.

2. **Software**: The actual DBMS software and related applications that manage and interact with the database.

3. **Data**: The actual information stored in the database, organized in tables, documents, or other structures.

4. **Procedures**: Rules and guidelines that govern database operations and maintenance.

5. **Query Language**: Tools for interacting with the database (like SQL).

6. **Users**: Different types of users who interact with the database:
   - Database Administrators (DBAs)
   - Application Programmers
   - End Users



## 2. Relational Database

A relational database is a type of database that stores and organizes data in tables with rows and columns, where relationships can be established between these tables using keys.

Examples:
1. **MySQL**: Open-source RDBMS, popular for web applications
2. **PostgreSQL**: Advanced open-source database with extensive features
3. **Oracle**: Enterprise-level commercial database system
4. **Microsoft SQL Server**: Microsoft's enterprise database solution



## 3. Classifications of SQL

SQL commands are classified into three main categories:

1. **DDL (Data Definition Language)**
   - Used to define and modify database structure
   - Commands include CREATE, ALTER, DROP, TRUNCATE

2. **DML (Data Manipulation Language)**
   - Used to manipulate data within the database
   - Commands include SELECT, INSERT, UPDATE, DELETE

3. **DCL (Data Control Language)**
   - Used to control access to data in the database
   - Commands include GRANT and REVOKE



## 4. Primary Key vs Foreign Key

**Primary Key**:
- Uniquely identifies each record in a table
- Cannot contain NULL values
- Must be unique for each record
- Only one per table

**Foreign Key**:
- References a primary key in another table
- Creates relationships between tables
- Can contain NULL values
- Multiple foreign keys allowed per table
- Ensures referential integrity



## 5. Entity-Relationship Diagram (ERD)

An Entity-Relationship Diagram is a visual representation of the relationships between entities (tables) in a database. It shows:
- Entities and their attributes
- Relationships between entities
- Cardinality of relationships (one-to-one, one-to-many, many-to-many)
- Primary and foreign keys

## 6. Advantages of Relational Databases

1. **Data Independence**: Physical storage can be modified without affecting logical data structure
2. **Data Integrity**: Ensures accuracy and consistency through constraints and rules
3. **Data Security**: Provides robust access control and user management
4. **Reduced Redundancy**: Normalized structure minimizes data duplication


## 7. Common Data Types

1. **Numeric Types**:
   - INTEGER
   - DECIMAL
   - FLOAT
   - DOUBLE

2. **String Types**:
   - VARCHAR
   - CHAR
   - TEXT

3. **Date/Time Types**:
   - DATE
   - TIME
   - TIMESTAMP

4. **Boolean Type**:
   - BOOLEAN (TRUE/FALSE)


## 8. Purpose of DBMS

The primary purposes of a Database Management System are:

1. **Data Management**: Efficiently organize, store, and retrieve data
2. **Data Security**: Protect data from unauthorized access
3. **Data Integrity**: Maintain accuracy and consistency of data
4. **Concurrent Access**: Allow multiple users to access data simultaneously
5. **Data Independence**: Separate data from applications that use it
