
# OracleDB-SQL-Project

This project demonstrates core SQL operations using Oracle SQL while integrating fundamental Oracle Database theory. Although the implementation focuses on SQL commands, it also covers key Oracle DB concepts to provide a broader understanding of how Oracle manages data. This approach is ideal for those who want to learn both practical SQL and some theoretical aspects of Oracle Database systems.

## Oracle Database Theory Overview

Oracle Database (Oracle DB) is a robust, multi-model database management system known for its high performance and advanced features. Here are some foundational concepts:

- **Instance and Database**:  
  An Oracle instance comprises memory structures (such as the System Global Area) and background processes that manage database operations. The database itself is a collection of physical datafiles that store the actual data.

- **Tablespaces and Datafiles**:  
  Oracle organizes storage into tablespaces, which are logical storage units consisting of one or more datafiles. This architecture aids in efficient data management and backup operations.

- **Schema and Users**:  
  In Oracle, a schema is a collection of database objects (tables, views, indexes, etc.) that belong to a specific user. This separation of schema and user enhances security and simplifies object management.

- **SQL and PL/SQL**:  
  Oracle SQL is used for data manipulation and querying, while PL/SQL (Procedural Language/SQL) extends SQL with procedural capabilities, allowing the creation of complex scripts and functions.

## Table-Related SQL Queries

Below are common SQL operations tailored for Oracle SQL. These examples include basic commands that are used frequently in Oracle DB environments.

### Create Table

Define a new table in Oracle SQL with the necessary columns, data types, and constraints. Oracle may require specific data types and constraint definitions according to its standards.

```sql
CREATE TABLE table_name (
  column_name1 datatype constraint,
  column_name2 datatype constraint
);
```
![Screenshot 2025-01-10 215412](https://github.com/user-attachments/assets/a225fc49-08ae-4b2-7cd13e162b9e)

### Insert Data

Insert records into your table. Oracle SQL statements are terminated with a semicolon.

```sql
INSERT INTO table_name (colname1, colname2)
VALUES (col1_v1, col2_v1),
       (col1_v2, col2_v2);
```
![Screenshot 2025-01-10 220242](https://github.com/user-attachments/assets/9bc3f79f-d08e-4ace-b75e-290451102bf2)

### Select & View All Columns

Retrieve all records from a table. This basic SELECT statement works across all SQL databases, including Oracle.

```sql
SELECT * FROM table_name;
```
![image](https://github.com/user-attachments/assets/4da7494a-e78c-4c92-9229-2722fbaaf624)

### Where Clause

Filter query results based on specific conditions. This clause is fundamental for querying subsets of data in Oracle SQL.

```sql
SELECT col1, col2 FROM table_name
WHERE conditions;
```
![image](https://github.com/user-attachments/assets/c0209d16-d35a-4ad5-a66a-6f3d7dc67bc1)

### Aggregate Functions

Aggregate functions in Oracle SQL perform calculations on sets of values and return a single value. They are essential for summarizing data.

- **COUNT()**: Returns the number of rows.
- **MAX()**: Returns the maximum value.
  
![image](https://github.com/user-attachments/assets/5acb2859-eb15-4c3a-a8e5-3cf6640dcb96)

- **MIN()**: Returns the minimum value.

![image](https://github.com/user-attachments/assets/195fd3d0-f5f3-463c-804a-45d948c3006e)

- **SUM()**: Calculates the total sum of a numeric column.

![image](https://github.com/user-attachments/assets/f601a742-c0b9-46c9-b4ad-68a61006e0e6)

- **AVG()**: Computes the average value.

![image](https://github.com/user-attachments/assets/857106c1-5b5c-46d2-a616-95ff415f80ee)

## Conclusion

This project not only demonstrates practical Oracle SQL operations but also offers an overview of the underlying theory of Oracle Database systems. By combining hands-on SQL examples with Oracle DB concepts such as instances, tablespaces, and schema management, you gain a deeper understanding of how Oracle structures and manages data. This comprehensive approach ensures you are well-prepared for real-world applications in an Oracle environment.
