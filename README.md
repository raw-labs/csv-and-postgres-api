# WARNING: This repository uses deprecated features. Please refer to [this page](https://app.raw-labs.com/home/) for the latest examples.

# CSV and RDMBS to API

This example illustrates how to create a REST API to read and serve data from both a CSV file and a database. 

It uses a dataset on airports, with two tables, one stored in a CSV file and the other in a PostgreSQL table.

Information is served via a REST API endpoint:

`/airports?id=<airport_id>&country=<country_name>&city=<city_name>&iata=<iata_code>`

The query code is defined in file [1/code.rql](1/code.rql).
The endpoint is defined in file [1/airports.yml](1/airports.yml).

This example illustrates how easy it is to combine different data sources with RAW.

[Click here to learn more about RAW.](https://www.raw-labs.com/)
