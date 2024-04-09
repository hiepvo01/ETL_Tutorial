## ETL implementation with Python and Azure cloud

This project implements a simple Star Schema data warehouse design: Extracting data source from Azure blob storage, Transforming the data into Dimension and Fact tables, and finally uploading the schema to Azure SQL database for data warehouse management.

Please follow the [Tutorial Videos](https://www.youtube.com/watch?v=yIflPdERBvY&list=PL5WVbgdMDtS0rBQzayZnYlnIDHHyEAYxy) for project set up and implementation

### Official Azure Documentations:

[Azure Blob Storage](https://learn.microsoft.com/en-us/azure/storage/blobs/storage-quickstart-blobs-python?tabs=managed-identity%2Croles-azure-portal%2Csign-in-visual-studio-code&pivots=blob-storage-quickstart-scratch&fbclid=IwAR0_SXxKXmnzjU8YgZ7xHys0-F2yG-V4pXQk8us7wv1Z-gEys62RS6ODBRg#prerequisites)

[Azure SQL database](https://learn.microsoft.com/en-us/azure/azure-sql/database/azure-sql-python-quickstart?view=azuresql&tabs=windows%2Csql-inter)

### Core Prerequisites:

Azure account with an active subscription - [create an account for free](https://azure.microsoft.com/en-us/free/?ref=microsoft.com&utm_source=microsoft.com&utm_medium=docs&utm_campaign=visualstudio)

Azure Storage account - [create a storage account](https://learn.microsoft.com/en-us/azure/storage/common/storage-account-create?tabs=azure-portal)

An Azure SQL database configured with Microsoft Entra authentication. You can create one using the [Create database quickstart](https://learn.microsoft.com/en-us/azure/azure-sql/database/single-database-create-quickstart?view=azuresql&tabs=azure-portal).

The latest version of the [Azure CLI](https://learn.microsoft.com/en-us/cli/azure/get-started-with-azure-cli).

Visual Studio Code with the Python extension.

Python 3.8 or later. If you're using a Linux client machine, see [Install the ODBC driver](https://learn.microsoft.com/en-us/sql/connect/python/pyodbc/step-1-configure-development-environment-for-pyodbc-python-development?view=sql-server-ver16&tabs=linux#install-the-odbc-driver).