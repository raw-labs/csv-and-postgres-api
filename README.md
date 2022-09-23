# CSV and RDMBS to API

This example illustrates how to create a REST API to read and serve data from both a CSV file and a database. 

The tables, in the CSV file and in the PostgreSQL database file contain information about airports.  

Information is served via one REST API endpoint:  

**/airports?id=\<airport_id>&country=\<country_name>&city=\<city_name>&iata=\<iata_code>**  

This endpoint returns matching rows in the CSV file and attributes from the database table.  

In this example, it returns the list of airports for the given ID and/or country and/or city and/or iata code.    

The ID is taken from the CSV file and the airport attributes are fetched from a PostgreSQL table.

This illusrates how easy it is to combine different data sources with RAW Labs.
Source code is defined in the code.rql file.

