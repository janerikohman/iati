# iati
Test to read, analyze and write IATI-standard data.

Primarily to have use cases to implement. The goal is to experiment with:
* Azure Table Storage
* Azure Container Instances
* Azure Functions and bindings
* PowerBi for analysis
* Message oriented architecture

## Todo
* Read IATI-xml files
* Use IATI-standard schema to deserilize XML to classes
* Package the data in flat format and store in Azure Table Storage
##
* Use Azure Functions with table bindings to store data from XML-files
* Use Azure Container Instances for the program that deserializes the XML-files and calls the Azure Functions
