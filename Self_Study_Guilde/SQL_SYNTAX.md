
-- Comments in SQL start with two consecutive dashes

-- SELECT statement: Retrieves data from a table
**SELECT** column1, column2  
**FROM** table_name  
**WHERE condition**;

-- INSERT INTO statement: Adds new rows of data into a table  
**INSERT** INTO table_name (column1, column2)  
**VALUES** (value1, value2);

-- UPDATE statement: Modifies existing data in a table  
**UPDATE** table_name  
**SET** column1 = value1  
**WHERE condition**;

-- DELETE FROM statement: Removes rows of data from a table  
**DELETE FROM** table_name  
**WHERE condition**;

-- CREATE TABLE statement: Creates a new table in the database  
**CREATE TABLE** table_name (  
    column1 datatype,  
    column2 datatype,  
    ...
);

-- ALTER TABLE statement: Modifies an existing table structure  
**ALTER TABLE** table_name  
**ADD** column_name datatype;

-- DROP TABLE statement: Deletes a table from the database  
**DROP** TABLE table_name;

-- CREATE INDEX statement: Creates an index on a table column for faster data retrieval  
**CREATE** INDEX index_name  
**ON** table_name (column_name);

-- DROP INDEX statement: Deletes an index from a table  
**DROP** INDEX index_name;
