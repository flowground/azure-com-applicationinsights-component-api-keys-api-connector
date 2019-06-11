# ![LOGO](logo.png) ApplicationInsightsManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the ApplicationInsightsManagementClient API (version 2015-05-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/applicationinsights-componentApiKeys_API/2015-05-01/swagger.json<br/>
Generated at: 2019-06-11T18:13:17+03:00

## API Description

Azure Application Insights client for API keys of a component.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Delete an API Key of an Application Insights component.

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription ID.
* `resourceName` - _required_ - The name of the Application Insights component resource.
* `keyId` - _required_ - The API Key ID. This is unique within a Application Insights component.

### Get the API Key for this key id.

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription ID.
* `resourceName` - _required_ - The name of the Application Insights component resource.
* `keyId` - _required_ - The API Key ID. This is unique within a Application Insights component.

### Gets a list of API keys of an Application Insights component.

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription ID.
* `resourceName` - _required_ - The name of the Application Insights component resource.

### Create an API Key of an Application Insights component.

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription ID.
* `resourceName` - _required_ - The name of the Application Insights component resource.

## License

**flow**ground :- Telekom iPaaS / azure-com-applicationinsights-component-api-keys-api-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
