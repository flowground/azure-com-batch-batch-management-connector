# ![LOGO](logo.png) BatchManagement **flow**ground Connector

## Description

A generated **flow**ground connector for the BatchManagement API (version 2018-12-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/batch-BatchManagement/2018-12-01/swagger.json<br/>
Generated at: 2019-05-07T17:37:38+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists available operations for the Microsoft.Batch provider

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - The API version to be used with the HTTP request.

### Gets information about the Batch accounts associated with the subscription.

*Tags:* `BatchAccount`

#### Input Parameters
* `api-version` - _required_ - The API version to be used with the HTTP request.
* `subscriptionId` - _required_ - The Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000)

### Checks whether the Batch account name is available in the specified region.

#### Input Parameters
* `locationName` - _required_ - The desired region for the name check.
* `api-version` - _required_ - The API version to be used with the HTTP request.
* `subscriptionId` - _required_ - The Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000)

### Gets the Batch service quotas for the specified subscription at the given location.

*Tags:* `Location`

#### Input Parameters
* `locationName` - _required_ - The region for which to retrieve Batch service quotas.
* `api-version` - _required_ - The API version to be used with the HTTP request.
* `subscriptionId` - _required_ - The Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000)

### Gets information about the Batch accounts associated with the specified resource group.

*Tags:* `BatchAccount`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the Batch account.
* `api-version` - _required_ - The API version to be used with the HTTP request.
* `subscriptionId` - _required_ - The Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000)

### Deletes the specified Batch account.

*Tags:* `BatchAccount`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the Batch account.
* `accountName` - _required_ - The name of the Batch account.
* `api-version` - _required_ - The API version to be used with the HTTP request.
* `subscriptionId` - _required_ - The Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000)

### Gets information about the specified Batch account.

*Tags:* `BatchAccount`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the Batch account.
* `accountName` - _required_ - The name of the Batch account.
* `api-version` - _required_ - The API version to be used with the HTTP request.
* `subscriptionId` - _required_ - The Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000)

### Updates the properties of an existing Batch account.

*Tags:* `BatchAccount`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the Batch account.
* `accountName` - _required_ - The name of the Batch account.
* `api-version` - _required_ - The API version to be used with the HTTP request.
* `subscriptionId` - _required_ - The Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000)

### Creates a new Batch account with the specified parameters. Existing accounts cannot be updated with this API and should instead be updated with the Update Batch Account API.

*Tags:* `BatchAccount`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the Batch account.
* `accountName` - _required_ - A name for the Batch account which must be unique within the region. Batch account names must be between 3 and 24 characters in length and must use only numbers and lowercase letters. This name is used as part of the DNS name that is used to access the Batch service in the region in which the account is created. For example: http://accountname.region.batch.azure.com/.
* `api-version` - _required_ - The API version to be used with the HTTP request.
* `subscriptionId` - _required_ - The Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000)

### Lists all of the applications in the specified account.

*Tags:* `Application`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the Batch account.
* `accountName` - _required_ - The name of the Batch account.
* `maxresults` - _optional_ - The maximum number of items to return in the response.
* `api-version` - _required_ - The API version to be used with the HTTP request.
* `subscriptionId` - _required_ - The Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000)

### Deletes an application.

*Tags:* `Application`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the Batch account.
* `accountName` - _required_ - The name of the Batch account.
* `applicationName` - _required_ - The name of the application. This must be unique within the account.
* `api-version` - _required_ - The API version to be used with the HTTP request.
* `subscriptionId` - _required_ - The Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000)

### Gets information about the specified application.

*Tags:* `Application`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the Batch account.
* `accountName` - _required_ - The name of the Batch account.
* `applicationName` - _required_ - The name of the application. This must be unique within the account.
* `api-version` - _required_ - The API version to be used with the HTTP request.
* `subscriptionId` - _required_ - The Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000)

### Updates settings for the specified application.

*Tags:* `Application`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the Batch account.
* `accountName` - _required_ - The name of the Batch account.
* `applicationName` - _required_ - The name of the application. This must be unique within the account.
* `api-version` - _required_ - The API version to be used with the HTTP request.
* `subscriptionId` - _required_ - The Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000)

### Adds an application to the specified Batch account.

*Tags:* `Application`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the Batch account.
* `accountName` - _required_ - The name of the Batch account.
* `applicationName` - _required_ - The name of the application. This must be unique within the account.
* `api-version` - _required_ - The API version to be used with the HTTP request.
* `subscriptionId` - _required_ - The Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000)

### Lists all of the application packages in the specified application.

*Tags:* `ApplicationPackage`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the Batch account.
* `accountName` - _required_ - The name of the Batch account.
* `applicationName` - _required_ - The name of the application. This must be unique within the account.
* `maxresults` - _optional_ - The maximum number of items to return in the response.
* `api-version` - _required_ - The API version to be used with the HTTP request.
* `subscriptionId` - _required_ - The Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000)

### Deletes an application package record and its associated binary file.

*Tags:* `ApplicationPackage`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the Batch account.
* `accountName` - _required_ - The name of the Batch account.
* `applicationName` - _required_ - The name of the application. This must be unique within the account.
* `versionName` - _required_ - The version of the application.
* `api-version` - _required_ - The API version to be used with the HTTP request.
* `subscriptionId` - _required_ - The Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000)

### Gets information about the specified application package.

*Tags:* `ApplicationPackage`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the Batch account.
* `accountName` - _required_ - The name of the Batch account.
* `applicationName` - _required_ - The name of the application. This must be unique within the account.
* `versionName` - _required_ - The version of the application.
* `api-version` - _required_ - The API version to be used with the HTTP request.
* `subscriptionId` - _required_ - The Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000)

### Creates an application package record.

*Tags:* `ApplicationPackage`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the Batch account.
* `accountName` - _required_ - The name of the Batch account.
* `applicationName` - _required_ - The name of the application. This must be unique within the account.
* `versionName` - _required_ - The version of the application.
* `api-version` - _required_ - The API version to be used with the HTTP request.
* `subscriptionId` - _required_ - The Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000)

### Activates the specified application package.

*Tags:* `ApplicationPackage`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the Batch account.
* `accountName` - _required_ - The name of the Batch account.
* `applicationName` - _required_ - The name of the application. This must be unique within the account.
* `versionName` - _required_ - The version of the application.
* `api-version` - _required_ - The API version to be used with the HTTP request.
* `subscriptionId` - _required_ - The Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000)

### Lists all of the certificates in the specified account.

*Tags:* `Certificate`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the Batch account.
* `accountName` - _required_ - The name of the Batch account.
* `maxresults` - _optional_ - The maximum number of items to return in the response.
* `$select` - _optional_ - Comma separated list of properties that should be returned. e.g. "properties/provisioningState". Only top level properties under properties/ are valid for selection.
* `$filter` - _optional_ - OData filter expression. Valid properties for filtering are "properties/provisioningState", "properties/provisioningStateTransitionTime", "name".
* `api-version` - _required_ - The API version to be used with the HTTP request.
* `subscriptionId` - _required_ - The Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000)

### Deletes the specified certificate.

*Tags:* `Certificate`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the Batch account.
* `accountName` - _required_ - The name of the Batch account.
* `certificateName` - _required_ - The identifier for the certificate. This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request. For example SHA1-a3d1c5.
* `api-version` - _required_ - The API version to be used with the HTTP request.
* `subscriptionId` - _required_ - The Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000)

### Gets information about the specified certificate.

*Tags:* `Certificate`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the Batch account.
* `accountName` - _required_ - The name of the Batch account.
* `certificateName` - _required_ - The identifier for the certificate. This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request. For example SHA1-a3d1c5.
* `api-version` - _required_ - The API version to be used with the HTTP request.
* `subscriptionId` - _required_ - The Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000)

### Updates the properties of an existing certificate.

*Tags:* `Certificate`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the Batch account.
* `accountName` - _required_ - The name of the Batch account.
* `certificateName` - _required_ - The identifier for the certificate. This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request. For example SHA1-a3d1c5.
* `If-Match` - _optional_ - The entity state (ETag) version of the certificate to update. This value can be omitted or set to "*" to apply the operation unconditionally.
* `api-version` - _required_ - The API version to be used with the HTTP request.
* `subscriptionId` - _required_ - The Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000)

### Creates a new certificate inside the specified account.

*Tags:* `Certificate`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the Batch account.
* `accountName` - _required_ - The name of the Batch account.
* `certificateName` - _required_ - The identifier for the certificate. This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request. For example SHA1-a3d1c5.
* `If-Match` - _optional_ - The entity state (ETag) version of the certificate to update. A value of "*" can be used to apply the operation only if the certificate already exists. If omitted, this operation will always be applied.
* `If-None-Match` - _optional_ - Set to '*' to allow a new certificate to be created, but to prevent updating an existing certificate. Other values will be ignored.
* `api-version` - _required_ - The API version to be used with the HTTP request.
* `subscriptionId` - _required_ - The Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000)

### Cancels a failed deletion of a certificate from the specified account.

> If you try to delete a certificate that is being used by a pool or compute node, the status of the certificate changes to deleteFailed. If you decide that you want to continue using the certificate, you can use this operation to set the status of the certificate back to active. If you intend to delete the certificate, you do not need to run this operation after the deletion failed. You must make sure that the certificate is not being used by any resources, and then you can try again to delete the certificate.

*Tags:* `Certificate`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the Batch account.
* `accountName` - _required_ - The name of the Batch account.
* `certificateName` - _required_ - The identifier for the certificate. This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request. For example SHA1-a3d1c5.
* `api-version` - _required_ - The API version to be used with the HTTP request.
* `subscriptionId` - _required_ - The Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000)

### Gets the account keys for the specified Batch account.

> This operation applies only to Batch accounts created with a poolAllocationMode of 'BatchService'. If the Batch account was created with a poolAllocationMode of 'UserSubscription', clients cannot use access to keys to authenticate, and must use Azure Active Directory instead. In this case, getting the keys will fail.

*Tags:* `BatchAccount`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the Batch account.
* `accountName` - _required_ - The name of the Batch account.
* `api-version` - _required_ - The API version to be used with the HTTP request.
* `subscriptionId` - _required_ - The Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000)

### Lists all of the pools in the specified account.

*Tags:* `Pool`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the Batch account.
* `accountName` - _required_ - The name of the Batch account.
* `maxresults` - _optional_ - The maximum number of items to return in the response.
* `$select` - _optional_ - Comma separated list of properties that should be returned. e.g. "properties/provisioningState". Only top level properties under properties/ are valid for selection.
* `$filter` - _optional_ - OData filter expression. Valid properties for filtering are:

 name
 properties/allocationState
 properties/allocationStateTransitionTime
 properties/creationTime
 properties/provisioningState
 properties/provisioningStateTransitionTime
 properties/lastModified
 properties/vmSize
 properties/interNodeCommunication
 properties/scaleSettings/autoScale
 properties/scaleSettings/fixedScale
* `api-version` - _required_ - The API version to be used with the HTTP request.
* `subscriptionId` - _required_ - The Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000)

### Deletes the specified pool.

*Tags:* `Pool`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the Batch account.
* `accountName` - _required_ - The name of the Batch account.
* `poolName` - _required_ - The pool name. This must be unique within the account.
* `api-version` - _required_ - The API version to be used with the HTTP request.
* `subscriptionId` - _required_ - The Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000)

### Gets information about the specified pool.

*Tags:* `Pool`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the Batch account.
* `accountName` - _required_ - The name of the Batch account.
* `poolName` - _required_ - The pool name. This must be unique within the account.
* `api-version` - _required_ - The API version to be used with the HTTP request.
* `subscriptionId` - _required_ - The Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000)

### Updates the properties of an existing pool.

*Tags:* `Pool`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the Batch account.
* `accountName` - _required_ - The name of the Batch account.
* `poolName` - _required_ - The pool name. This must be unique within the account.
* `If-Match` - _optional_ - The entity state (ETag) version of the pool to update. This value can be omitted or set to "*" to apply the operation unconditionally.
* `api-version` - _required_ - The API version to be used with the HTTP request.
* `subscriptionId` - _required_ - The Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000)

### Creates a new pool inside the specified account.

*Tags:* `Pool`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the Batch account.
* `accountName` - _required_ - The name of the Batch account.
* `poolName` - _required_ - The pool name. This must be unique within the account.
* `If-Match` - _optional_ - The entity state (ETag) version of the pool to update. A value of "*" can be used to apply the operation only if the pool already exists. If omitted, this operation will always be applied.
* `If-None-Match` - _optional_ - Set to '*' to allow a new pool to be created, but to prevent updating an existing pool. Other values will be ignored.
* `api-version` - _required_ - The API version to be used with the HTTP request.
* `subscriptionId` - _required_ - The Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000)

### Disables automatic scaling for a pool.

*Tags:* `Pool`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the Batch account.
* `accountName` - _required_ - The name of the Batch account.
* `poolName` - _required_ - The pool name. This must be unique within the account.
* `api-version` - _required_ - The API version to be used with the HTTP request.
* `subscriptionId` - _required_ - The Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000)

### Stops an ongoing resize operation on the pool.

> This does not restore the pool to its previous state before the resize operation: it only stops any further changes being made, and the pool maintains its current state. After stopping, the pool stabilizes at the number of nodes it was at when the stop operation was done. During the stop operation, the pool allocation state changes first to stopping and then to steady. A resize operation need not be an explicit resize pool request; this API can also be used to halt the initial sizing of the pool when it is created.

*Tags:* `Pool`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the Batch account.
* `accountName` - _required_ - The name of the Batch account.
* `poolName` - _required_ - The pool name. This must be unique within the account.
* `api-version` - _required_ - The API version to be used with the HTTP request.
* `subscriptionId` - _required_ - The Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000)

### Regenerates the specified account key for the Batch account.

*Tags:* `BatchAccount`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the Batch account.
* `accountName` - _required_ - The name of the Batch account.
* `api-version` - _required_ - The API version to be used with the HTTP request.
* `subscriptionId` - _required_ - The Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000)

### Synchronizes access keys for the auto-storage account configured for the specified Batch account.

*Tags:* `BatchAccount`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the Batch account.
* `accountName` - _required_ - The name of the Batch account.
* `api-version` - _required_ - The API version to be used with the HTTP request.
* `subscriptionId` - _required_ - The Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000)

## License

**flow**ground :- Telekom iPaaS / azure-com-batch-batch-management-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
