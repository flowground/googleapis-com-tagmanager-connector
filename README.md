# ![LOGO](logo.png) Tag Manager **flow**ground Connector

## Description

A generated **flow**ground connector for the Tag Manager API (version v1).

Generated from: https://api.apis.guru/v2/specs/googleapis.com/tagmanager/v1/swagger.json<br/>
Generated at: 2019-05-07T17:42:03+03:00

## API Description

Accesses Tag Manager accounts and containers.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all GTM Accounts that a user has access to.

*Tags:* `accounts`

#### Input Parameters
* `alt` - _optional_ - Data format for the response.
    Possible values: json.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Gets a GTM Account.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates a GTM Account.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `fingerprint` - _optional_ - When provided, this fingerprint must match the fingerprint of the account in storage.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Lists all Containers that belongs to a GTM Account.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a Container.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes a Container.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `containerId` - _required_ - The GTM Container ID.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Gets a Container.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `containerId` - _required_ - The GTM Container ID.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates a Container.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `containerId` - _required_ - The GTM Container ID.
* `fingerprint` - _optional_ - When provided, this fingerprint must match the fingerprint of the container in storage.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Lists all GTM Environments of a GTM Container.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `containerId` - _required_ - The GTM Container ID.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a GTM Environment.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `containerId` - _required_ - The GTM Container ID.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes a GTM Environment.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `containerId` - _required_ - The GTM Container ID.
* `environmentId` - _required_ - The GTM Environment ID.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Gets a GTM Environment.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `containerId` - _required_ - The GTM Container ID.
* `environmentId` - _required_ - The GTM Environment ID.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates a GTM Environment.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `containerId` - _required_ - The GTM Container ID.
* `environmentId` - _required_ - The GTM Environment ID.
* `fingerprint` - _optional_ - When provided, this fingerprint must match the fingerprint of the environment in storage.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Lists all GTM Folders of a Container.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `containerId` - _required_ - The GTM Container ID.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a GTM Folder.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `containerId` - _required_ - The GTM Container ID.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes a GTM Folder.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `containerId` - _required_ - The GTM Container ID.
* `folderId` - _required_ - The GTM Folder ID.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Gets a GTM Folder.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `containerId` - _required_ - The GTM Container ID.
* `folderId` - _required_ - The GTM Folder ID.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates a GTM Folder.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `containerId` - _required_ - The GTM Container ID.
* `fingerprint` - _optional_ - When provided, this fingerprint must match the fingerprint of the folder in storage.
* `folderId` - _required_ - The GTM Folder ID.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List all entities in a GTM Folder.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `containerId` - _required_ - The GTM Container ID.
* `folderId` - _required_ - The GTM Folder ID.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Moves entities to a GTM Folder.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `containerId` - _required_ - The GTM Container ID.
* `folderId` - _required_ - The GTM Folder ID.
* `tagId` - _optional_ - The tags to be moved to the folder.
* `triggerId` - _optional_ - The triggers to be moved to the folder.
* `variableId` - _optional_ - The variables to be moved to the folder.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Re-generates the authorization code for a GTM Environment.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `containerId` - _required_ - The GTM Container ID.
* `environmentId` - _required_ - The GTM Environment ID.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Lists all GTM Tags of a Container.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `containerId` - _required_ - The GTM Container ID.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a GTM Tag.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `containerId` - _required_ - The GTM Container ID.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes a GTM Tag.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `containerId` - _required_ - The GTM Container ID.
* `tagId` - _required_ - The GTM Tag ID.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Gets a GTM Tag.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `containerId` - _required_ - The GTM Container ID.
* `tagId` - _required_ - The GTM Tag ID.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates a GTM Tag.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `containerId` - _required_ - The GTM Container ID.
* `fingerprint` - _optional_ - When provided, this fingerprint must match the fingerprint of the tag in storage.
* `tagId` - _required_ - The GTM Tag ID.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Lists all GTM Triggers of a Container.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `containerId` - _required_ - The GTM Container ID.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a GTM Trigger.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `containerId` - _required_ - The GTM Container ID.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes a GTM Trigger.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `containerId` - _required_ - The GTM Container ID.
* `triggerId` - _required_ - The GTM Trigger ID.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Gets a GTM Trigger.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `containerId` - _required_ - The GTM Container ID.
* `triggerId` - _required_ - The GTM Trigger ID.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates a GTM Trigger.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `containerId` - _required_ - The GTM Container ID.
* `fingerprint` - _optional_ - When provided, this fingerprint must match the fingerprint of the trigger in storage.
* `triggerId` - _required_ - The GTM Trigger ID.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Lists all GTM Variables of a Container.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `containerId` - _required_ - The GTM Container ID.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a GTM Variable.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `containerId` - _required_ - The GTM Container ID.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes a GTM Variable.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `containerId` - _required_ - The GTM Container ID.
* `variableId` - _required_ - The GTM Variable ID.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Gets a GTM Variable.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `containerId` - _required_ - The GTM Container ID.
* `variableId` - _required_ - The GTM Variable ID.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates a GTM Variable.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `containerId` - _required_ - The GTM Container ID.
* `fingerprint` - _optional_ - When provided, this fingerprint must match the fingerprint of the variable in storage.
* `variableId` - _required_ - The GTM Variable ID.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Lists all Container Versions of a GTM Container.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `containerId` - _required_ - The GTM Container ID.
* `headers` - _optional_ - Retrieve headers only when true.
* `includeDeleted` - _optional_ - Also retrieve deleted (archived) versions when true.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a Container Version.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `containerId` - _required_ - The GTM Container ID.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes a Container Version.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `containerId` - _required_ - The GTM Container ID.
* `containerVersionId` - _required_ - The GTM Container Version ID.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Gets a Container Version.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `containerId` - _required_ - The GTM Container ID.
* `containerVersionId` - _required_ - The GTM Container Version ID. Specify published to retrieve the currently published version.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates a Container Version.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `containerId` - _required_ - The GTM Container ID.
* `containerVersionId` - _required_ - The GTM Container Version ID.
* `fingerprint` - _optional_ - When provided, this fingerprint must match the fingerprint of the container version in storage.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Publishes a Container Version.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `containerId` - _required_ - The GTM Container ID.
* `containerVersionId` - _required_ - The GTM Container Version ID.
* `fingerprint` - _optional_ - When provided, this fingerprint must match the fingerprint of the container version in storage.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Restores a Container Version. This will overwrite the container's current configuration (including its variables, triggers and tags). The operation will not have any effect on the version that is being served (i.e. the published version).

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `containerId` - _required_ - The GTM Container ID.
* `containerVersionId` - _required_ - The GTM Container Version ID.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Undeletes a Container Version.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `containerId` - _required_ - The GTM Container ID.
* `containerVersionId` - _required_ - The GTM Container Version ID.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List all users that have access to the account along with Account and Container Permissions granted to each of them.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID. @required tagmanager.accounts.permissions.list
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a user's Account & Container Permissions.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Removes a user from the account, revoking access to it and all of its containers.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `permissionId` - _required_ - The GTM User ID.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Gets a user's Account & Container Permissions.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `permissionId` - _required_ - The GTM User ID.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates a user's Account & Container Permissions.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The GTM Account ID.
* `permissionId` - _required_ - The GTM User ID.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

## License

**flow**ground :- Telekom iPaaS / googleapis-com-tagmanager-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
