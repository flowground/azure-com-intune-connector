# ![LOGO](logo.png) IntuneResourceManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the IntuneResourceManagementClient API (version 2015-01-14-privatepreview).

Generated from: https://api.apis.guru/v2/specs/azure.com/intune/2015-01-14-privatepreview/swagger.json<br/>
Generated at: 2019-05-07T17:38:14+03:00

## API Description

Microsoft.Intune Resource provider Api features in the swagger-2.0 specification

## Authorization

This API does not require authorization.

## Actions

### Returns location for user tenant.

#### Input Parameters
* `api-version` - _required_ - Service Api Version.

### Returns location for given tenant.

#### Input Parameters
* `api-version` - _required_ - Service Api Version.

### Get apps for an AndroidMAMPolicy.

#### Input Parameters
* `hostName` - _required_ - Location hostName for the tenant
* `policyName` - _required_ - Unique name for the policy
* `api-version` - _required_ - Service Api Version.
* `$filter` - _optional_ - The filter to apply on the operation.
* `$top` - _optional_
* `$select` - _optional_ - select specific fields in entity.

### Returns Intune Android policies.

#### Input Parameters
* `hostName` - _required_ - Location hostName for the tenant
* `api-version` - _required_ - Service Api Version.
* `$filter` - _optional_ - The filter to apply on the operation.
* `$top` - _optional_
* `$select` - _optional_ - select specific fields in entity.

### Delete Android Policy

#### Input Parameters
* `hostName` - _required_ - Location hostName for the tenant
* `policyName` - _required_ - Unique name for the policy
* `api-version` - _required_ - Service Api Version.

### Returns AndroidMAMPolicy with given name.

#### Input Parameters
* `hostName` - _required_ - Location hostName for the tenant
* `policyName` - _required_ - Unique name for the policy
* `api-version` - _required_ - Service Api Version.
* `$select` - _optional_ - select specific fields in entity.

### Patch AndroidMAMPolicy.

#### Input Parameters
* `hostName` - _required_ - Location hostName for the tenant
* `policyName` - _required_ - Unique name for the policy
* `api-version` - _required_ - Service Api Version.

### Creates or updates AndroidMAMPolicy.

#### Input Parameters
* `hostName` - _required_ - Location hostName for the tenant
* `policyName` - _required_ - Unique name for the policy
* `api-version` - _required_ - Service Api Version.

### Delete App for Android Policy

#### Input Parameters
* `hostName` - _required_ - Location hostName for the tenant
* `policyName` - _required_ - Unique name for the policy
* `appName` - _required_ - application unique Name
* `api-version` - _required_ - Service Api Version.

### Add app to an AndroidMAMPolicy.

#### Input Parameters
* `hostName` - _required_ - Location hostName for the tenant
* `policyName` - _required_ - Unique name for the policy
* `appName` - _required_ - application unique Name
* `api-version` - _required_ - Service Api Version.

### Returns groups for a given AndroidMAMPolicy.

#### Input Parameters
* `hostName` - _required_ - Location hostName for the tenant
* `policyName` - _required_ - policy name for the tenant
* `api-version` - _required_ - Service Api Version.

### Delete Group for Android Policy

#### Input Parameters
* `hostName` - _required_ - Location hostName for the tenant
* `policyName` - _required_ - Unique name for the policy
* `groupId` - _required_ - application unique Name
* `api-version` - _required_ - Service Api Version.

### Add group to an AndroidMAMPolicy.

#### Input Parameters
* `hostName` - _required_ - Location hostName for the tenant
* `policyName` - _required_ - Unique name for the policy
* `groupId` - _required_ - group Id
* `api-version` - _required_ - Service Api Version.

### Returns Intune Manageable apps.

#### Input Parameters
* `hostName` - _required_ - Location hostName for the tenant
* `api-version` - _required_ - Service Api Version.
* `$filter` - _optional_ - The filter to apply on the operation.
* `$top` - _optional_
* `$select` - _optional_ - select specific fields in entity.

### Returns Intune flagged user collection

#### Input Parameters
* `hostName` - _required_ - Location hostName for the tenant
* `api-version` - _required_ - Service Api Version.
* `$filter` - _optional_ - The filter to apply on the operation.
* `$top` - _optional_
* `$select` - _optional_ - select specific fields in entity.

### Returns Intune flagged user details

#### Input Parameters
* `hostName` - _required_ - Location hostName for the tenant
* `userName` - _required_ - Flagged userName
* `api-version` - _required_ - Service Api Version.
* `$select` - _optional_ - select specific fields in entity.

### Returns Intune flagged enrolled app collection for the User

#### Input Parameters
* `hostName` - _required_ - Location hostName for the tenant
* `userName` - _required_ - User name for the tenant
* `api-version` - _required_ - Service Api Version.
* `$filter` - _optional_ - The filter to apply on the operation.
* `$top` - _optional_
* `$select` - _optional_ - select specific fields in entity.

### Returns Intune iOSPolicies.

#### Input Parameters
* `hostName` - _required_ - Location hostName for the tenant
* `api-version` - _required_ - Service Api Version.
* `$filter` - _optional_ - The filter to apply on the operation.
* `$top` - _optional_
* `$select` - _optional_ - select specific fields in entity.

### Delete Ios Policy

#### Input Parameters
* `hostName` - _required_ - Location hostName for the tenant
* `policyName` - _required_ - Unique name for the policy
* `api-version` - _required_ - Service Api Version.

### Returns Intune iOS policies.

#### Input Parameters
* `hostName` - _required_ - Location hostName for the tenant
* `policyName` - _required_ - Unique name for the policy
* `api-version` - _required_ - Service Api Version.
* `$select` - _optional_ - select specific fields in entity.

### patch an iOSMAMPolicy.

#### Input Parameters
* `hostName` - _required_ - Location hostName for the tenant
* `policyName` - _required_ - Unique name for the policy
* `api-version` - _required_ - Service Api Version.

### Creates or updates iOSMAMPolicy.

#### Input Parameters
* `hostName` - _required_ - Location hostName for the tenant
* `policyName` - _required_ - Unique name for the policy
* `api-version` - _required_ - Service Api Version.

### Get apps for an iOSMAMPolicy.

#### Input Parameters
* `hostName` - _required_ - Location hostName for the tenant
* `policyName` - _required_ - Unique name for the policy
* `api-version` - _required_ - Service Api Version.
* `$filter` - _optional_ - The filter to apply on the operation.
* `$top` - _optional_
* `$select` - _optional_ - select specific fields in entity.

### Delete App for Ios Policy

#### Input Parameters
* `hostName` - _required_ - Location hostName for the tenant
* `policyName` - _required_ - Unique name for the policy
* `appName` - _required_ - application unique Name
* `api-version` - _required_ - Service Api Version.

### Add app to an iOSMAMPolicy.

#### Input Parameters
* `hostName` - _required_ - Location hostName for the tenant
* `policyName` - _required_ - Unique name for the policy
* `appName` - _required_ - application unique Name
* `api-version` - _required_ - Service Api Version.

### Returns groups for a given iOSMAMPolicy.

#### Input Parameters
* `hostName` - _required_ - Location hostName for the tenant
* `policyName` - _required_ - policy name for the tenant
* `api-version` - _required_ - Service Api Version.

### Delete Group for iOS Policy

#### Input Parameters
* `hostName` - _required_ - Location hostName for the tenant
* `policyName` - _required_ - Unique name for the policy
* `groupId` - _required_ - application unique Name
* `api-version` - _required_ - Service Api Version.

### Add group to an iOSMAMPolicy.

#### Input Parameters
* `hostName` - _required_ - Location hostName for the tenant
* `policyName` - _required_ - Unique name for the policy
* `groupId` - _required_ - group Id
* `api-version` - _required_ - Service Api Version.

### Returns operationResults.

#### Input Parameters
* `hostName` - _required_ - Location hostName for the tenant
* `api-version` - _required_ - Service Api Version.
* `$filter` - _optional_ - The filter to apply on the operation.
* `$top` - _optional_
* `$select` - _optional_ - select specific fields in entity.

### Returns Intune Tenant level statuses.

#### Input Parameters
* `hostName` - _required_ - Location hostName for the tenant
* `api-version` - _required_ - Service Api Version.

### Get devices for a user.

#### Input Parameters
* `hostName` - _required_ - Location hostName for the tenant
* `userName` - _required_ - user unique Name
* `api-version` - _required_ - Service Api Version.
* `$filter` - _optional_ - The filter to apply on the operation.
* `$top` - _optional_
* `$select` - _optional_ - select specific fields in entity.

### Get a unique device for a user.

#### Input Parameters
* `hostName` - _required_ - Location hostName for the tenant
* `userName` - _required_ - unique user name
* `deviceName` - _required_ - device name
* `api-version` - _required_ - Service Api Version.
* `$select` - _optional_ - select specific fields in entity.

### Wipe a device for a user.

#### Input Parameters
* `hostName` - _required_ - Location hostName for the tenant
* `userName` - _required_ - unique user name
* `deviceName` - _required_ - device name
* `api-version` - _required_ - Service Api Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-intune-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
