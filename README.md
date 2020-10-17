# Load data from Spark to a Database using JDBC Spark Dataframe source
This is a template to create a Spark Dataframe based on a jdbc connection and load data from Spark to a Database postgres.

The example code take into account a table in a Postgres Databae with the next table structure:

database: testdb

CREATE TABLE table_test(
  id INTEGER,
  name VARCHAR(10)
); 

