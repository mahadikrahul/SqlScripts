# SQL Scripts

## Introduction

This repository contains some scripts that will help us in our development phase. They use the target DB and its tables to populate the result we can use in our code.

## Disclaimer

The scripts are created primarily in the SQL server environment, so the compatibility of working in other RDBMS databases might vary. Also, you might need to update the query to your tailored needs.

## Content

Each script file contains a SQL script targeting a specific task listed below. Some initial code might seem redundant, but it is to keep the scripts isolated and standalone-ready.

## Scripts

### C# Object Creator ([C#ObjectCreator.sql](https://github.com/mahadikrahul/sql-scripts/Scripts/C#ObjectCreator.sql))

This script will print the C# object in the messages area that we can use in the below areas of our code.

#### Usage

1. Add the target table name as the value of the @TableName variable at line 3.

2. Add any desired condition to the table that you want to filter the result. However, we can keep it blank for all records to populate.

## Author

[Rahul Mahadik](https://github.com/mahadikrahul)
