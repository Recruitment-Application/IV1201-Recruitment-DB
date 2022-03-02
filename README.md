# IV1201-Recruitment-DB
Description:
The SQL scripts to create the database for the Recruitment application. The database was created with PostgreSQL.

SQL files:
recruitmentsdb.sql: Script to create the database with all the data included.
recruitmentsdb_schema.sql: Script to create the database with only the schema.

Useful commands using PostgresSQL CLI tools:

Export the schema of a database
pg_dump -W -F p --schema-only -U username  -d dbname -h host > Path/filename.sql

Export the whole database including data
pg_dump -W -F p -U username -d dbname -h host > Path/filename.sql

Import a database
psql -U username -d dbname -h host < Path/filename.sql