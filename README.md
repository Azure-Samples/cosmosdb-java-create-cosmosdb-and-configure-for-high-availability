---
page_type: sample
languages:
- java
products:
- azure
extensions:
- services: Cosmosdb
- platforms: java
---

# Getting Started with Cosmosdb - Manage HA Cosmos DB - in Java #


  Azure CosmosDB sample for high availability.
   - Create a CosmosDB configured with a single read location
   - Get the credentials for the CosmosDB
   - Update the CosmosDB with additional read locations
   - add collection to the CosmosDB with throughput 4000
   - Delete the CosmosDB
 

## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/cosmosdb-java-create-cosmosdb-and-configure-for-high-availability.git

    cd cosmosdb-java-create-cosmosdb-and-configure-for-high-availability

    mvn clean compile exec:java

## More information ##

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.