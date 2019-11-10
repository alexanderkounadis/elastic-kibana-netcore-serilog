# elastic-kibana-netcore-serilog

spin up elasticsearch and kibana containers using docker (docker-compose up -d)

Navigate to http://localhost:9200 to ensure ElasticSearch is up and running

Navigate to http://localhost:5601 to ensure Kibana is up and running

Nuget Packages: 
  Serilog
  Serilog.Sinks.ElasticSearch
  Serilog.Extensions.Logging
  Serilog.Exceptions

appsettings.json configuration :
    "ElasticConfiguration": {
    "Uri": "http://localhost:9200/"
  }

run the MVC application by hitting f5 in Visual Studio code, or by typing dotnet run

open up Kibana at http://localhost:5601 so that we can view the logs.

Create an Index Pattern in Kibana to Show Data
