## Project: Data Modeling with Cassandra

###  Description

A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app.
The analysis team is particularly interested in understanding what songs users are listening to. 
Currently, there is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app.
They'd like a data engineer to create an Apache Cassandra database which can create queries on song play data to answer the questions.
To complete the project, we need to model our data by creating tables in Apache Cassandra to run queries.

### Project Datasets:

For this project, we work with one dataset: event_data, the directory of CSV files partitioned by date.

### Project files:

Apache_cassandra.ipynb is the file used to perform all the project steps listed below.

### Project Steps:

Below are steps followed to complete each component of this project.

1- Modeling your NoSQL database or Apache Cassandra database.

2- Design tables to answer the queries outlined in the project template.

3- Write Apache Cassandra CREATE KEYSPACE and SET KEYSPACE statements.

4- Develop your CREATE statement for each of the tables to address each question.

5- Load the data with INSERT statement for each of the tables.

6- Include IF NOT EXISTS clauses in our CREATE statements to create tables only if the tables do not already exist.

7- Include DROP TABLE statement for each table, this way you can run drop and create tables whenever you want to reset our database and test our ETL pipeline.

8- Test by running the proper select statements with the correct WHERE clause.

9- Build ETL Pipeline.

10- Implement the logic in section Part I of the notebook template to iterate through each event file in event_data to process and create a new CSV file in Python.

11- Make necessary edits to Part II of the notebook template to include Apache Cassandra CREATE and INSERT statements to load processed records into relevant tables in our data model.

12- Test by running SELECT statements after running the queries on your database.
