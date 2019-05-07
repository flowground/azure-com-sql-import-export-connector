# ![LOGO](logo.png) Azure SQL Database Import/Export spec **flow**ground Connector

## Description

A generated **flow**ground connector for the Azure SQL Database Import/Export spec API (version 2014-04-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/sql-importExport/2014-04-01/swagger.json<br/>
Generated at: 2019-05-07T17:39:04+03:00

## API Description

Provides create and read functionality for Import/Export operations on Azure SQL databases.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Exports a database to a bacpac.

*Tags:* `ImportExport`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `databaseName` - _required_ - The name of the database to be exported.

### Creates an import operation that imports a bacpac into an existing database. The existing database must be empty.

*Tags:* `ImportExport`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `databaseName` - _required_ - The name of the database to import into
* `extensionName` - _required_ - The name of the operation to perform
    Possible values: import.

### Imports a bacpac into a new database.

*Tags:* `ImportExport`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.

## License

**flow**ground :- Telekom iPaaS / azure-com-sql-import-export-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
