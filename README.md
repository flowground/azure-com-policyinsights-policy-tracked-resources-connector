# ![LOGO](logo.png) PolicyTrackedResourcesClient **flow**ground Connector

## Description

A generated **flow**ground connector for the PolicyTrackedResourcesClient API (version 2018-07-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/policyinsights-policyTrackedResources/2018-07-01-preview/swagger.json<br/>
Generated at: 2019-05-07T17:38:36+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Queries policy tracked resources under the management group.

#### Input Parameters
* `managementGroupsNamespace` - _required_ - The namespace for Microsoft Management RP; only "Microsoft.Management" is allowed.
    Possible values: Microsoft.Management.
* `managementGroupName` - _required_ - Management group name.
* `policyTrackedResourcesResource` - _required_ - The name of the virtual resource under PolicyTrackedResources resource type; only "default" is allowed.
    Possible values: default.
* `$top` - _optional_ - Maximum number of records to return.
* `$filter` - _optional_ - OData filter expression.
* `api-version` - _required_ - Client Api Version.

### Queries policy tracked resources under the subscription.

#### Input Parameters
* `policyTrackedResourcesResource` - _required_ - The name of the virtual resource under PolicyTrackedResources resource type; only "default" is allowed.
    Possible values: default.
* `$top` - _optional_ - Maximum number of records to return.
* `$filter` - _optional_ - OData filter expression.
* `subscriptionId` - _required_ - Microsoft Azure subscription ID.
* `api-version` - _required_ - Client Api Version.

### Queries policy tracked resources under the resource group.

#### Input Parameters
* `resourceGroupName` - _required_ - Resource group name.
* `policyTrackedResourcesResource` - _required_ - The name of the virtual resource under PolicyTrackedResources resource type; only "default" is allowed.
    Possible values: default.
* `$top` - _optional_ - Maximum number of records to return.
* `$filter` - _optional_ - OData filter expression.
* `subscriptionId` - _required_ - Microsoft Azure subscription ID.
* `api-version` - _required_ - Client Api Version.

### Queries policy tracked resources under the resource.

#### Input Parameters
* `resourceId` - _required_ - Resource ID.
* `policyTrackedResourcesResource` - _required_ - The name of the virtual resource under PolicyTrackedResources resource type; only "default" is allowed.
    Possible values: default.
* `$top` - _optional_ - Maximum number of records to return.
* `$filter` - _optional_ - OData filter expression.
* `api-version` - _required_ - Client Api Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-policyinsights-policy-tracked-resources-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
