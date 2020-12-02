---
page_type: sample
languages:
- java
products:
- azure
extensions:
  services: Sql
  platforms: java
---

# Getting Started with Sql - Manage Sql Firewall Rules - in Java #


  Azure SQL sample for managing SQL Database -
   - Create a SQL Server along with 2 firewalls.
   - Add another firewall in the SQL Server
   - List all firewalls.
   - Get a firewall.
   - Update a firewall.
   - Delete a firewall.
   - Add and delete a firewall as part of update of SQL Server
   - Delete Sql Server
 

## Running this Sample ##

To run this sample:

See [DefaultAzureCredential](https://github.com/Azure/azure-sdk-for-java/tree/master/sdk/identity/azure-identity#defaultazurecredential) and prepare the authentication works best for you. For more details on authentication, please refer to [AUTH.md](https://github.com/Azure/azure-sdk-for-java/blob/master/sdk/resourcemanager/docs/AUTH.md).

    git clone https://github.com/Azure-Samples/sql-database-java-manage-firewalls-for-sql-databases.git

    cd sql-database-java-manage-firewalls-for-sql-databases

    mvn clean compile exec:java

## More information ##

For general documentation as well as quickstarts on how to use Azure Management Libraries for Java, please see [here](https://aka.ms/azsdk/java/mgmt).

Start to develop applications with Java on Azure [here](http://azure.com/java).

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.