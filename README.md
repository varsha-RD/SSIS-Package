Prerequisites:
=============
Install below
*SSIS Package
*SSISDB

This package reads the CSV file and loads the data into the order, product, and customer tables without duplicates.
Used flat file source to load the csv file
Execute sql task to create the table
ole Db destination for load the data to database tables
sort to remove the duplicates from csv file
look up to check whether the csv data is exists in tables tables or not 
