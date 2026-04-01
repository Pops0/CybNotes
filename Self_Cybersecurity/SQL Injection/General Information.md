# Information:

## Commands
#info

**CREATE**: Creates a new database object (database, table, index, view, etc.)  
<u>Example:</u>  
CREATE TABLE users (  
id INT,  
name VARCHAR(50)  
);

**ALTER**: Modifies the structure of an existing database object.  
<u>Example:</u>  
ALTER TABLE users  
ADD email VARCHAR(100);

**DROP**: Deletes a database object permanently.  
<u>Example:</u>  
DROP TABLE users;

**TRUNCATE**: Removes all rows from a table but keeps the table structure.  
<u>Example:</u>  
TRUNCATE TABLE users;

**RENAME**: Changes the name of a table or database object.  
<u>Example:</u>  
RENAME TABLE users TO customers;

**INSERT**: Adds new records into a table.  
<u>Example:</u>  
INSERT INTO users (id, name)  
VALUES (1, 'John');

**UPDATE**: Changes existing records in a table.  
<u>Example:</u>  
UPDATE users  
SET name = 'Jane'  
WHERE id = 1;

**DELETE**: Removes specific records from a table.  
<u>Example:</u>  
DELETE FROM users  
WHERE id = 1;

**SELECT**: Retrieves data from a table.  
<u>Example:</u>  
SELECT * FROM users;

**DISTINCT**: Removes duplicate rows in query results.  
<u>Example:</u>  
SELECT DISTINCT name  
FROM users;

**WHERE**: Filters records based on a condition.  
<u>Example:</u>  
SELECT * FROM users  
WHERE id > 5;

**ORDER** BY: Sorts query results.  
<u>Example:</u>  
SELECT * FROM users  
ORDER BY name ASC;

**GROUP BY**: Groups rows that have the same values.  
<u>Example:</u>  
SELECT name, COUNT(*)  
FROM users  
GROUP BY name;

**HAVING**: Filters grouped results.  
<u>Example:</u>  
SELECT name, COUNT(*)  
FROM users  
GROUP BY name  
HAVING COUNT(*) > 1;

**LIMIT**: Limits the number of rows returned.  
<u>Example:</u>  
SELECT * FROM users  
LIMIT 10;

**OFFSET**: Skips a number of rows before returning results.  
<u>Example:</u>  
SELECT * FROM users  
LIMIT 10 OFFSET 5;

**JOIN**: Combines rows from multiple tables.  
<u>Example:</u>  
SELECT users.name, orders.id  
FROM users  
JOIN orders ON users.id = orders.user_id;

**INNER JOIN**: Returns rows that match in both tables.  
<u>Example:</u>  
SELECT *  
FROM users  
INNER JOIN orders  
ON users.id = orders.user_id;

**LEFT JOIN**: Returns all rows from the left table and matching rows from the right.  
<u>Example:</u>  
SELECT *  
FROM users  
LEFT JOIN orders  
ON users.id = orders.user_id;

**RIGHT JOIN**: Returns all rows from the right table and matching rows from the left.  
<u>Example:</u>  
SELECT *  
FROM users  
RIGHT JOIN orders  
ON users.id = orders.user_id;

**FULL JOIN**: Returns rows when there is a match in either table.  
<u>Example:</u>  
SELECT *  
FROM users  
FULL JOIN orders  
ON users.id = orders.user_id;

**UNION**: Combines results of two queries and removes duplicates.  
<u>Example:</u>  
SELECT name FROM users  
UNION  
SELECT name FROM admins;

**UNION ALL**: Combines results but keeps duplicates.  
<u>Example:</u>  
SELECT name FROM users  
UNION ALL  
SELECT name FROM admins;

**CREATE INDEX**: Creates an index to improve search performance.  
<u>Example:</u>  
CREATE INDEX idx_name  
ON users(name);

**DROP INDEX**: Deletes an index.  
<u>Example:</u>  
DROP INDEX idx_name;

**CREATE VIEW**: Creates a virtual table based on a query.  
<u>Example:</u>  
CREATE VIEW active_users AS  
SELECT * FROM users  
WHERE active = 1;

**DROP VIEW**: Deletes a view.  
<u>Example:</u>  
DROP VIEW active_users;

**GRANT**: Gives privileges to a user.  
<u>Example:</u>  
GRANT SELECT ON users TO analyst;

**REVOKE**: Removes privileges from a user.  
<u>Example:</u>  
REVOKE SELECT ON users FROM analyst;

**COMMIT**: Saves all changes made in the current transaction.  
<u>Example:</u>  
COMMIT;

**ROLLBACK**: Undoes changes made in the current transaction.  
<u>Example:</u>  
ROLLBACK;

**SAVEPOINT**: Creates a checkpoint inside a transaction.  
<u>Example:</u>  
SAVEPOINT before_update;

**SET TRANSACTION**: Defines properties of a transaction.  
<u>Example:</u>  
SET TRANSACTION READ ONLY;

**CREATE USER**: Creates a new database user.  
<u>Example:</u>  
CREATE USER bob IDENTIFIED BY 'password';

**DROP USER**: Removes a database user.  
<u>Example:</u>  
DROP USER bob;

**ALTER USER**: Modifies user credentials or permissions.  
<u>Example:</u>  
ALTER USER bob IDENTIFIED BY 'newpassword';

**SHOW DATABASES**: Lists all databases (commonly used in MySQL).  
<u>Example:</u>  
SHOW DATABASES;

**SHOW TABLES**: Lists all tables in the current database.  
<u>Example:</u>  
SHOW TABLES;

**DESCRIBE**: Shows the structure of a table.  
<u>Example:</u>  
DESCRIBE users;

---

## SQL Injection Categories:
#info 

###### *In-band*:
Directly on site | Direct Channel
###### *Out-band*: 
Via messenger | Secondary/Alternative channel e.g [[out-of-band example.png]]
###### *Blind (or inferential):*
No idea what info there is, but tries nonetheless, retrieves "yes" or "no" queries, doesn't really get data, just close-ended question, works on behaviours (keyword is also to "reconstructing key information")

## 5 Main Techniques:
#info
###### - **Union operator:** 
This is typically used when an SQL injection vulnerability allows a **SELECT** statement to combine two queries into a single result or a set of results.
###### - **Boolean:**
This is used to verify whether certain conditions are true or false.
###### - **Error-based technique:**
This is used to force the database to generate an error in order to enhance and refine an attack (injection).
###### - **Out-of-band technique:**
This is typically used to obtain records from the database by using a different channel. For example, it is possible to make an HTTP connection to send the results to a different web server or a local machine running a web service. e.g [[out-of-band example.png]]
###### - **Time delay**:
** It is possible to use database commands to delay answers. An attacker may use this technique when he or she doesn’t get output or error messages from the application. 
```
e.g: https://store.h4cker.org/buyme.php?id=8 AND IF(version() like '8%', sleep(10), 'false'))--
```
*In this example, the query checks whether the MySQL version is 8.x and then forces the server to delay the answer by 10 seconds. The attacker can increase the delay time and monitor the responses. The attacker could even set the sleep parameter to a high value since it is not necessary to wait that long and then just cancel the request after a few seconds.*

## Error Message Types:
#info 
###### <u>SQL Server Errors:</u>
https://www.w3schools.com/tags/ref_httpmessages.asp
###### <u>Microsoft SQL Server Database:</u>
https://learn.microsoft.com/en-us/sql/relational-databases/errors-events/database-engine-events-and-errors
###### <u>Oracle:</u>
https://docs.oracle.com/database/121/ERRMG/toc.htm
###### <u>Union:</u>
https://www.w3schools.com/sql/sql_union.asp

