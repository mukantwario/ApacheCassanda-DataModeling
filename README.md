# ApacheCassanda-DataModeling
### Project Description

In this project, we implemented modeling noSQL database using Apache Cassandra then developed an ETL pipeline to load data from CSV file partitioned by data.

### DataSet

Two datasets are provided:
1. event_data/2018-11-08-events.csv
2. event_data/2018-11-09-events.csv

### Project Template

Two files provided as the start up of this project:
1. event_datafile_new.csv: used to create a denormalized dataset
2. jupyter notebook file to create table, insert data and do select

### Tables
We extract relevant information from these logs and construct a Sparkify database: sparkifydb. It consists of the following tables:

- app_music_library: to implement first query
- app_artist_library: to implement second query
- app_users_library: used this table to implement third query

### ETL Pipeline
Designed table above to answer queries below: ETL pipeline consists os creating KeySpace, develop create and insert statements with appropriate 
partition keys which are helpfull into grouping records retrieved in select query.

### How to run the ETL
1. From command prompt, open the project notebook file, from the notebook menu of the: restart kernel and Run All Cells... or:
2. From same menu after restarting Kernel, use Run menu, you can run specific cells or all cells or restart kernal and run all cells.. 
