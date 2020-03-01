# ![LOGO](logo.png) DCM/DFA Reporting And Trafficking **flow**ground Connector

## Description

A generated **flow**ground connector for the DCM/DFA Reporting And Trafficking API (version v3.3).

Generated from: https://www.googleapis.com/dfareporting/v3.3<br/>
Generated at: 2020-03-01T05:35:43+00:00

## API Description

Manages your DoubleClick Campaign Manager ad campaigns and reports.<br/>

## Authorization

Supported authorization schemes:
- OAuth2 - Oauth 2.0 implicit authentication
- OAuth2 - Oauth 2.0 accessCode authentication

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### dfareporting.files.get
> Retrieves a report file by its report ID and file ID. This method supports media download.<br/>

*Tags:* `files`

#### Input Parameters
* `reportId` - _required_ - The ID of the report.<br/>
* `fileId` - _required_ - The ID of the report file.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.userProfiles.list
> Retrieves list of user profiles for a user.<br/>

*Tags:* `userProfiles`

#### Input Parameters
* `alt` - _optional_ - Data format for the response.<br/>
    Possible values: json.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.userProfiles.get
> Gets one user profile by ID.<br/>

*Tags:* `userProfiles`

#### Input Parameters
* `profileId` - _required_ - The user profile ID.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.accountActiveAdSummaries.get
> Gets the account's active ad summary by account ID.<br/>

*Tags:* `accountActiveAdSummaries`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `summaryAccountId` - _required_ - Account ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.accountPermissionGroups.list
> Retrieves the list of account permission groups.<br/>

*Tags:* `accountPermissionGroups`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.accountPermissionGroups.get
> Gets one account permission group by ID.<br/>

*Tags:* `accountPermissionGroups`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Account permission group ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.accountPermissions.list
> Retrieves the list of account permissions.<br/>

*Tags:* `accountPermissions`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.accountPermissions.get
> Gets one account permission by ID.<br/>

*Tags:* `accountPermissions`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Account permission ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.accountUserProfiles.list
> Retrieves a list of account user profiles, possibly filtered. This method supports paging.<br/>

*Tags:* `accountUserProfiles`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `active` - _optional_ - Select only active user profiles.<br/>
* `ids` - _optional_ - Select only user profiles with these IDs.<br/>
* `maxResults` - _optional_ - Maximum number of results to return.<br/>
* `pageToken` - _optional_ - Value of the nextPageToken from the previous result page.<br/>
* `searchString` - _optional_ - Allows searching for objects by name, ID or email. Wildcards (*) are allowed. For example, "user profile*2015" will return objects with names like "user profile June 2015", "user profile April 2015", or simply "user profile 2015". Most of the searches also add wildcards implicitly at the start and the end of the search string. For example, a search string of "user profile" will match objects with name "my user profile", "user profile 2015", or simply "user profile".<br/>
* `sortField` - _optional_ - Field by which to sort the list.<br/>
    Possible values: ID, NAME.
* `sortOrder` - _optional_ - Order of sorted results.<br/>
    Possible values: ASCENDING, DESCENDING.
* `subaccountId` - _optional_ - Select only user profiles with the specified subaccount ID.<br/>
* `userRoleId` - _optional_ - Select only user profiles with the specified user role ID.<br/>

### dfareporting.accountUserProfiles.patch
> Updates an existing account user profile. This method supports patch semantics.<br/>

*Tags:* `accountUserProfiles`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - User profile ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.accountUserProfiles.insert
> Inserts a new account user profile.<br/>

*Tags:* `accountUserProfiles`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.accountUserProfiles.update
> Updates an existing account user profile.<br/>

*Tags:* `accountUserProfiles`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.accountUserProfiles.get
> Gets one account user profile by ID.<br/>

*Tags:* `accountUserProfiles`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - User profile ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.accounts.list
> Retrieves the list of accounts, possibly filtered. This method supports paging.<br/>

*Tags:* `accounts`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `active` - _optional_ - Select only active accounts. Don't set this field to select both active and non-active accounts.<br/>
* `ids` - _optional_ - Select only accounts with these IDs.<br/>
* `maxResults` - _optional_ - Maximum number of results to return.<br/>
* `pageToken` - _optional_ - Value of the nextPageToken from the previous result page.<br/>
* `searchString` - _optional_ - Allows searching for objects by name or ID. Wildcards (*) are allowed. For example, "account*2015" will return objects with names like "account June 2015", "account April 2015", or simply "account 2015". Most of the searches also add wildcards implicitly at the start and the end of the search string. For example, a search string of "account" will match objects with name "my account", "account 2015", or simply "account".<br/>
* `sortField` - _optional_ - Field by which to sort the list.<br/>
    Possible values: ID, NAME.
* `sortOrder` - _optional_ - Order of sorted results.<br/>
    Possible values: ASCENDING, DESCENDING.

### dfareporting.accounts.patch
> Updates an existing account. This method supports patch semantics.<br/>

*Tags:* `accounts`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Account ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.accounts.update
> Updates an existing account.<br/>

*Tags:* `accounts`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.accounts.get
> Gets one account by ID.<br/>

*Tags:* `accounts`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Account ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.ads.list
> Retrieves a list of ads, possibly filtered. This method supports paging.<br/>

*Tags:* `ads`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `active` - _optional_ - Select only active ads.<br/>
* `advertiserId` - _optional_ - Select only ads with this advertiser ID.<br/>
* `archived` - _optional_ - Select only archived ads.<br/>
* `audienceSegmentIds` - _optional_ - Select only ads with these audience segment IDs.<br/>
* `campaignIds` - _optional_ - Select only ads with these campaign IDs.<br/>
* `compatibility` - _optional_ - Select default ads with the specified compatibility. Applicable when type is AD_SERVING_DEFAULT_AD. DISPLAY and DISPLAY_INTERSTITIAL refer to rendering either on desktop or on mobile devices for regular or interstitial ads, respectively. APP and APP_INTERSTITIAL are for rendering in mobile apps. IN_STREAM_VIDEO refers to rendering an in-stream video ads developed with the VAST standard.<br/>
    Possible values: APP, APP_INTERSTITIAL, DISPLAY, DISPLAY_INTERSTITIAL, IN_STREAM_AUDIO, IN_STREAM_VIDEO.
* `creativeIds` - _optional_ - Select only ads with these creative IDs assigned.<br/>
* `creativeOptimizationConfigurationIds` - _optional_ - Select only ads with these creative optimization configuration IDs.<br/>
* `dynamicClickTracker` - _optional_ - Select only dynamic click trackers. Applicable when type is AD_SERVING_CLICK_TRACKER. If true, select dynamic click trackers. If false, select static click trackers. Leave unset to select both.<br/>
* `ids` - _optional_ - Select only ads with these IDs.<br/>
* `landingPageIds` - _optional_ - Select only ads with these landing page IDs.<br/>
* `maxResults` - _optional_ - Maximum number of results to return.<br/>
* `overriddenEventTagId` - _optional_ - Select only ads with this event tag override ID.<br/>
* `pageToken` - _optional_ - Value of the nextPageToken from the previous result page.<br/>
* `placementIds` - _optional_ - Select only ads with these placement IDs assigned.<br/>
* `remarketingListIds` - _optional_ - Select only ads whose list targeting expression use these remarketing list IDs.<br/>
* `searchString` - _optional_ - Allows searching for objects by name or ID. Wildcards (*) are allowed. For example, "ad*2015" will return objects with names like "ad June 2015", "ad April 2015", or simply "ad 2015". Most of the searches also add wildcards implicitly at the start and the end of the search string. For example, a search string of "ad" will match objects with name "my ad", "ad 2015", or simply "ad".<br/>
* `sizeIds` - _optional_ - Select only ads with these size IDs.<br/>
* `sortField` - _optional_ - Field by which to sort the list.<br/>
    Possible values: ID, NAME.
* `sortOrder` - _optional_ - Order of sorted results.<br/>
    Possible values: ASCENDING, DESCENDING.
* `sslCompliant` - _optional_ - Select only ads that are SSL-compliant.<br/>
* `sslRequired` - _optional_ - Select only ads that require SSL.<br/>
* `type` - _optional_ - Select only ads with these types.<br/>

### dfareporting.ads.patch
> Updates an existing ad. This method supports patch semantics.<br/>

*Tags:* `ads`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Ad ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.ads.insert
> Inserts a new ad.<br/>

*Tags:* `ads`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.ads.update
> Updates an existing ad.<br/>

*Tags:* `ads`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.ads.get
> Gets one ad by ID.<br/>

*Tags:* `ads`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Ad ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.advertiserGroups.list
> Retrieves a list of advertiser groups, possibly filtered. This method supports paging.<br/>

*Tags:* `advertiserGroups`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `ids` - _optional_ - Select only advertiser groups with these IDs.<br/>
* `maxResults` - _optional_ - Maximum number of results to return.<br/>
* `pageToken` - _optional_ - Value of the nextPageToken from the previous result page.<br/>
* `searchString` - _optional_ - Allows searching for objects by name or ID. Wildcards (*) are allowed. For example, "advertiser*2015" will return objects with names like "advertiser group June 2015", "advertiser group April 2015", or simply "advertiser group 2015". Most of the searches also add wildcards implicitly at the start and the end of the search string. For example, a search string of "advertisergroup" will match objects with name "my advertisergroup", "advertisergroup 2015", or simply "advertisergroup".<br/>
* `sortField` - _optional_ - Field by which to sort the list.<br/>
    Possible values: ID, NAME.
* `sortOrder` - _optional_ - Order of sorted results.<br/>
    Possible values: ASCENDING, DESCENDING.

### dfareporting.advertiserGroups.patch
> Updates an existing advertiser group. This method supports patch semantics.<br/>

*Tags:* `advertiserGroups`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Advertiser group ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.advertiserGroups.insert
> Inserts a new advertiser group.<br/>

*Tags:* `advertiserGroups`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.advertiserGroups.update
> Updates an existing advertiser group.<br/>

*Tags:* `advertiserGroups`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.advertiserGroups.delete
> Deletes an existing advertiser group.<br/>

*Tags:* `advertiserGroups`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Advertiser group ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.advertiserGroups.get
> Gets one advertiser group by ID.<br/>

*Tags:* `advertiserGroups`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Advertiser group ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.advertiserLandingPages.list
> Retrieves a list of landing pages.<br/>

*Tags:* `advertiserLandingPages`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `advertiserIds` - _optional_ - Select only landing pages that belong to these advertisers.<br/>
* `archived` - _optional_ - Select only archived landing pages. Don't set this field to select both archived and non-archived landing pages.<br/>
* `campaignIds` - _optional_ - Select only landing pages that are associated with these campaigns.<br/>
* `ids` - _optional_ - Select only landing pages with these IDs.<br/>
* `maxResults` - _optional_ - Maximum number of results to return.<br/>
* `pageToken` - _optional_ - Value of the nextPageToken from the previous result page.<br/>
* `searchString` - _optional_ - Allows searching for landing pages by name or ID. Wildcards (*) are allowed. For example, "landingpage*2017" will return landing pages with names like "landingpage July 2017", "landingpage March 2017", or simply "landingpage 2017". Most of the searches also add wildcards implicitly at the start and the end of the search string. For example, a search string of "landingpage" will match campaigns with name "my landingpage", "landingpage 2015", or simply "landingpage".<br/>
* `sortField` - _optional_ - Field by which to sort the list.<br/>
    Possible values: ID, NAME.
* `sortOrder` - _optional_ - Order of sorted results.<br/>
    Possible values: ASCENDING, DESCENDING.
* `subaccountId` - _optional_ - Select only landing pages that belong to this subaccount.<br/>

### dfareporting.advertiserLandingPages.patch
> Updates an existing landing page. This method supports patch semantics.<br/>

*Tags:* `advertiserLandingPages`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Landing page ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.advertiserLandingPages.insert
> Inserts a new landing page.<br/>

*Tags:* `advertiserLandingPages`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.advertiserLandingPages.update
> Updates an existing landing page.<br/>

*Tags:* `advertiserLandingPages`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.advertiserLandingPages.get
> Gets one landing page by ID.<br/>

*Tags:* `advertiserLandingPages`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Landing page ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.advertisers.list
> Retrieves a list of advertisers, possibly filtered. This method supports paging.<br/>

*Tags:* `advertisers`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `advertiserGroupIds` - _optional_ - Select only advertisers with these advertiser group IDs.<br/>
* `floodlightConfigurationIds` - _optional_ - Select only advertisers with these floodlight configuration IDs.<br/>
* `ids` - _optional_ - Select only advertisers with these IDs.<br/>
* `includeAdvertisersWithoutGroupsOnly` - _optional_ - Select only advertisers which do not belong to any advertiser group.<br/>
* `maxResults` - _optional_ - Maximum number of results to return.<br/>
* `onlyParent` - _optional_ - Select only advertisers which use another advertiser's floodlight configuration.<br/>
* `pageToken` - _optional_ - Value of the nextPageToken from the previous result page.<br/>
* `searchString` - _optional_ - Allows searching for objects by name or ID. Wildcards (*) are allowed. For example, "advertiser*2015" will return objects with names like "advertiser June 2015", "advertiser April 2015", or simply "advertiser 2015". Most of the searches also add wildcards implicitly at the start and the end of the search string. For example, a search string of "advertiser" will match objects with name "my advertiser", "advertiser 2015", or simply "advertiser".<br/>
* `sortField` - _optional_ - Field by which to sort the list.<br/>
    Possible values: ID, NAME.
* `sortOrder` - _optional_ - Order of sorted results.<br/>
    Possible values: ASCENDING, DESCENDING.
* `status` - _optional_ - Select only advertisers with the specified status.<br/>
    Possible values: APPROVED, ON_HOLD.
* `subaccountId` - _optional_ - Select only advertisers with these subaccount IDs.<br/>

### dfareporting.advertisers.patch
> Updates an existing advertiser. This method supports patch semantics.<br/>

*Tags:* `advertisers`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Advertiser ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.advertisers.insert
> Inserts a new advertiser.<br/>

*Tags:* `advertisers`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.advertisers.update
> Updates an existing advertiser.<br/>

*Tags:* `advertisers`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.advertisers.get
> Gets one advertiser by ID.<br/>

*Tags:* `advertisers`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Advertiser ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.browsers.list
> Retrieves a list of browsers.<br/>

*Tags:* `browsers`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.campaigns.list
> Retrieves a list of campaigns, possibly filtered. This method supports paging.<br/>

*Tags:* `campaigns`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `advertiserGroupIds` - _optional_ - Select only campaigns whose advertisers belong to these advertiser groups.<br/>
* `advertiserIds` - _optional_ - Select only campaigns that belong to these advertisers.<br/>
* `archived` - _optional_ - Select only archived campaigns. Don't set this field to select both archived and non-archived campaigns.<br/>
* `atLeastOneOptimizationActivity` - _optional_ - Select only campaigns that have at least one optimization activity.<br/>
* `excludedIds` - _optional_ - Exclude campaigns with these IDs.<br/>
* `ids` - _optional_ - Select only campaigns with these IDs.<br/>
* `maxResults` - _optional_ - Maximum number of results to return.<br/>
* `overriddenEventTagId` - _optional_ - Select only campaigns that have overridden this event tag ID.<br/>
* `pageToken` - _optional_ - Value of the nextPageToken from the previous result page.<br/>
* `searchString` - _optional_ - Allows searching for campaigns by name or ID. Wildcards (*) are allowed. For example, "campaign*2015" will return campaigns with names like "campaign June 2015", "campaign April 2015", or simply "campaign 2015". Most of the searches also add wildcards implicitly at the start and the end of the search string. For example, a search string of "campaign" will match campaigns with name "my campaign", "campaign 2015", or simply "campaign".<br/>
* `sortField` - _optional_ - Field by which to sort the list.<br/>
    Possible values: ID, NAME.
* `sortOrder` - _optional_ - Order of sorted results.<br/>
    Possible values: ASCENDING, DESCENDING.
* `subaccountId` - _optional_ - Select only campaigns that belong to this subaccount.<br/>

### dfareporting.campaigns.patch
> Updates an existing campaign. This method supports patch semantics.<br/>

*Tags:* `campaigns`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Campaign ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.campaigns.insert
> Inserts a new campaign.<br/>

*Tags:* `campaigns`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.campaigns.update
> Updates an existing campaign.<br/>

*Tags:* `campaigns`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.campaignCreativeAssociations.list
> Retrieves the list of creative IDs associated with the specified campaign. This method supports paging.<br/>

*Tags:* `campaignCreativeAssociations`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `campaignId` - _required_ - Campaign ID in this association.<br/>
* `maxResults` - _optional_ - Maximum number of results to return.<br/>
* `pageToken` - _optional_ - Value of the nextPageToken from the previous result page.<br/>
* `sortOrder` - _optional_ - Order of sorted results.<br/>
    Possible values: ASCENDING, DESCENDING.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.campaignCreativeAssociations.insert
> Associates a creative with the specified campaign. This method creates a default ad with dimensions matching the creative in the campaign if such a default ad does not exist already.<br/>

*Tags:* `campaignCreativeAssociations`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `campaignId` - _required_ - Campaign ID in this association.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.campaigns.get
> Gets one campaign by ID.<br/>

*Tags:* `campaigns`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Campaign ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.changeLogs.list
> Retrieves a list of change logs. This method supports paging.<br/>

*Tags:* `changeLogs`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `action` - _optional_ - Select only change logs with the specified action.<br/>
    Possible values: ACTION_ADD, ACTION_ASSIGN, ACTION_ASSOCIATE, ACTION_CREATE, ACTION_DELETE, ACTION_DISABLE, ACTION_EMAIL_TAGS, ACTION_ENABLE, ACTION_LINK, ACTION_MARK_AS_DEFAULT, ACTION_PUSH, ACTION_REMOVE, ACTION_SEND, ACTION_SHARE, ACTION_UNASSIGN, ACTION_UNLINK, ACTION_UPDATE.
* `ids` - _optional_ - Select only change logs with these IDs.<br/>
* `maxChangeTime` - _optional_ - Select only change logs whose change time is before the specified maxChangeTime.The time should be formatted as an RFC3339 date/time string. For example, for 10:54 PM on July 18th, 2015, in the America/New York time zone, the format is "2015-07-18T22:54:00-04:00". In other words, the year, month, day, the letter T, the hour (24-hour clock system), minute, second, and then the time zone offset.<br/>
* `maxResults` - _optional_ - Maximum number of results to return.<br/>
* `minChangeTime` - _optional_ - Select only change logs whose change time is after the specified minChangeTime.The time should be formatted as an RFC3339 date/time string. For example, for 10:54 PM on July 18th, 2015, in the America/New York time zone, the format is "2015-07-18T22:54:00-04:00". In other words, the year, month, day, the letter T, the hour (24-hour clock system), minute, second, and then the time zone offset.<br/>
* `objectIds` - _optional_ - Select only change logs with these object IDs.<br/>
* `objectType` - _optional_ - Select only change logs with the specified object type.<br/>
    Possible values: OBJECT_ACCOUNT, OBJECT_ACCOUNT_BILLING_FEATURE, OBJECT_AD, OBJECT_ADVERTISER, OBJECT_ADVERTISER_GROUP, OBJECT_BILLING_ACCOUNT_GROUP, OBJECT_BILLING_FEATURE, OBJECT_BILLING_MINIMUM_FEE, OBJECT_BILLING_PROFILE, OBJECT_CAMPAIGN, OBJECT_CONTENT_CATEGORY, OBJECT_CREATIVE, OBJECT_CREATIVE_ASSET, OBJECT_CREATIVE_BUNDLE, OBJECT_CREATIVE_FIELD, OBJECT_CREATIVE_GROUP, OBJECT_DFA_SITE, OBJECT_EVENT_TAG, OBJECT_FLOODLIGHT_ACTIVITY_GROUP, OBJECT_FLOODLIGHT_ACTVITY, OBJECT_FLOODLIGHT_CONFIGURATION, OBJECT_FLOODLIGHT_DV360_LINK, OBJECT_INSTREAM_CREATIVE, OBJECT_LANDING_PAGE, OBJECT_MEDIA_ORDER, OBJECT_PLACEMENT, OBJECT_PLACEMENT_STRATEGY, OBJECT_PLAYSTORE_LINK, OBJECT_PROVIDED_LIST_CLIENT, OBJECT_RATE_CARD, OBJECT_REMARKETING_LIST, OBJECT_RICHMEDIA_CREATIVE, OBJECT_SD_SITE, OBJECT_SEARCH_LIFT_STUDY, OBJECT_SIZE, OBJECT_SUBACCOUNT, OBJECT_TARGETING_TEMPLATE, OBJECT_USER_PROFILE, OBJECT_USER_PROFILE_FILTER, OBJECT_USER_ROLE.
* `pageToken` - _optional_ - Value of the nextPageToken from the previous result page.<br/>
* `searchString` - _optional_ - Select only change logs whose object ID, user name, old or new values match the search string.<br/>
* `userProfileIds` - _optional_ - Select only change logs with these user profile IDs.<br/>

### dfareporting.changeLogs.get
> Gets one change log by ID.<br/>

*Tags:* `changeLogs`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Change log ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.cities.list
> Retrieves a list of cities, possibly filtered.<br/>

*Tags:* `cities`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `countryDartIds` - _optional_ - Select only cities from these countries.<br/>
* `dartIds` - _optional_ - Select only cities with these DART IDs.<br/>
* `namePrefix` - _optional_ - Select only cities with names starting with this prefix.<br/>
* `regionDartIds` - _optional_ - Select only cities from these regions.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.connectionTypes.list
> Retrieves a list of connection types.<br/>

*Tags:* `connectionTypes`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.connectionTypes.get
> Gets one connection type by ID.<br/>

*Tags:* `connectionTypes`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Connection type ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.contentCategories.list
> Retrieves a list of content categories, possibly filtered. This method supports paging.<br/>

*Tags:* `contentCategories`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `ids` - _optional_ - Select only content categories with these IDs.<br/>
* `maxResults` - _optional_ - Maximum number of results to return.<br/>
* `pageToken` - _optional_ - Value of the nextPageToken from the previous result page.<br/>
* `searchString` - _optional_ - Allows searching for objects by name or ID. Wildcards (*) are allowed. For example, "contentcategory*2015" will return objects with names like "contentcategory June 2015", "contentcategory April 2015", or simply "contentcategory 2015". Most of the searches also add wildcards implicitly at the start and the end of the search string. For example, a search string of "contentcategory" will match objects with name "my contentcategory", "contentcategory 2015", or simply "contentcategory".<br/>
* `sortField` - _optional_ - Field by which to sort the list.<br/>
    Possible values: ID, NAME.
* `sortOrder` - _optional_ - Order of sorted results.<br/>
    Possible values: ASCENDING, DESCENDING.

### dfareporting.contentCategories.patch
> Updates an existing content category. This method supports patch semantics.<br/>

*Tags:* `contentCategories`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Content category ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.contentCategories.insert
> Inserts a new content category.<br/>

*Tags:* `contentCategories`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.contentCategories.update
> Updates an existing content category.<br/>

*Tags:* `contentCategories`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.contentCategories.delete
> Deletes an existing content category.<br/>

*Tags:* `contentCategories`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Content category ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.contentCategories.get
> Gets one content category by ID.<br/>

*Tags:* `contentCategories`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Content category ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.conversions.batchinsert
> Inserts conversions.<br/>

*Tags:* `conversions`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.conversions.batchupdate
> Updates existing conversions.<br/>

*Tags:* `conversions`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.countries.list
> Retrieves a list of countries.<br/>

*Tags:* `countries`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.countries.get
> Gets one country by ID.<br/>

*Tags:* `countries`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `dartId` - _required_ - Country DART ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.creativeAssets.insert
> Inserts a new creative asset.<br/>

*Tags:* `creativeAssets`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `advertiserId` - _required_ - Advertiser ID of this creative. This is a required field.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.creativeFields.list
> Retrieves a list of creative fields, possibly filtered. This method supports paging.<br/>

*Tags:* `creativeFields`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `advertiserIds` - _optional_ - Select only creative fields that belong to these advertisers.<br/>
* `ids` - _optional_ - Select only creative fields with these IDs.<br/>
* `maxResults` - _optional_ - Maximum number of results to return.<br/>
* `pageToken` - _optional_ - Value of the nextPageToken from the previous result page.<br/>
* `searchString` - _optional_ - Allows searching for creative fields by name or ID. Wildcards (*) are allowed. For example, "creativefield*2015" will return creative fields with names like "creativefield June 2015", "creativefield April 2015", or simply "creativefield 2015". Most of the searches also add wild-cards implicitly at the start and the end of the search string. For example, a search string of "creativefield" will match creative fields with the name "my creativefield", "creativefield 2015", or simply "creativefield".<br/>
* `sortField` - _optional_ - Field by which to sort the list.<br/>
    Possible values: ID, NAME.
* `sortOrder` - _optional_ - Order of sorted results.<br/>
    Possible values: ASCENDING, DESCENDING.

### dfareporting.creativeFields.patch
> Updates an existing creative field. This method supports patch semantics.<br/>

*Tags:* `creativeFields`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Creative Field ID<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.creativeFields.insert
> Inserts a new creative field.<br/>

*Tags:* `creativeFields`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.creativeFields.update
> Updates an existing creative field.<br/>

*Tags:* `creativeFields`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.creativeFieldValues.list
> Retrieves a list of creative field values, possibly filtered. This method supports paging.<br/>

*Tags:* `creativeFieldValues`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `creativeFieldId` - _required_ - Creative field ID for this creative field value.<br/>
* `ids` - _optional_ - Select only creative field values with these IDs.<br/>
* `maxResults` - _optional_ - Maximum number of results to return.<br/>
* `pageToken` - _optional_ - Value of the nextPageToken from the previous result page.<br/>
* `searchString` - _optional_ - Allows searching for creative field values by their values. Wildcards (e.g. *) are not allowed.<br/>
* `sortField` - _optional_ - Field by which to sort the list.<br/>
    Possible values: ID, VALUE.
* `sortOrder` - _optional_ - Order of sorted results.<br/>
    Possible values: ASCENDING, DESCENDING.

### dfareporting.creativeFieldValues.patch
> Updates an existing creative field value. This method supports patch semantics.<br/>

*Tags:* `creativeFieldValues`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `creativeFieldId` - _required_ - Creative field ID for this creative field value.<br/>
* `id` - _required_ - Creative Field Value ID<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.creativeFieldValues.insert
> Inserts a new creative field value.<br/>

*Tags:* `creativeFieldValues`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `creativeFieldId` - _required_ - Creative field ID for this creative field value.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.creativeFieldValues.update
> Updates an existing creative field value.<br/>

*Tags:* `creativeFieldValues`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `creativeFieldId` - _required_ - Creative field ID for this creative field value.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.creativeFieldValues.delete
> Deletes an existing creative field value.<br/>

*Tags:* `creativeFieldValues`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `creativeFieldId` - _required_ - Creative field ID for this creative field value.<br/>
* `id` - _required_ - Creative Field Value ID<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.creativeFieldValues.get
> Gets one creative field value by ID.<br/>

*Tags:* `creativeFieldValues`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `creativeFieldId` - _required_ - Creative field ID for this creative field value.<br/>
* `id` - _required_ - Creative Field Value ID<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.creativeFields.delete
> Deletes an existing creative field.<br/>

*Tags:* `creativeFields`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Creative Field ID<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.creativeFields.get
> Gets one creative field by ID.<br/>

*Tags:* `creativeFields`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Creative Field ID<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.creativeGroups.list
> Retrieves a list of creative groups, possibly filtered. This method supports paging.<br/>

*Tags:* `creativeGroups`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `advertiserIds` - _optional_ - Select only creative groups that belong to these advertisers.<br/>
* `groupNumber` - _optional_ - Select only creative groups that belong to this subgroup.<br/>
* `ids` - _optional_ - Select only creative groups with these IDs.<br/>
* `maxResults` - _optional_ - Maximum number of results to return.<br/>
* `pageToken` - _optional_ - Value of the nextPageToken from the previous result page.<br/>
* `searchString` - _optional_ - Allows searching for creative groups by name or ID. Wildcards (*) are allowed. For example, "creativegroup*2015" will return creative groups with names like "creativegroup June 2015", "creativegroup April 2015", or simply "creativegroup 2015". Most of the searches also add wild-cards implicitly at the start and the end of the search string. For example, a search string of "creativegroup" will match creative groups with the name "my creativegroup", "creativegroup 2015", or simply "creativegroup".<br/>
* `sortField` - _optional_ - Field by which to sort the list.<br/>
    Possible values: ID, NAME.
* `sortOrder` - _optional_ - Order of sorted results.<br/>
    Possible values: ASCENDING, DESCENDING.

### dfareporting.creativeGroups.patch
> Updates an existing creative group. This method supports patch semantics.<br/>

*Tags:* `creativeGroups`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Creative group ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.creativeGroups.insert
> Inserts a new creative group.<br/>

*Tags:* `creativeGroups`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.creativeGroups.update
> Updates an existing creative group.<br/>

*Tags:* `creativeGroups`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.creativeGroups.get
> Gets one creative group by ID.<br/>

*Tags:* `creativeGroups`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Creative group ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.creatives.list
> Retrieves a list of creatives, possibly filtered. This method supports paging.<br/>

*Tags:* `creatives`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `active` - _optional_ - Select only active creatives. Leave blank to select active and inactive creatives.<br/>
* `advertiserId` - _optional_ - Select only creatives with this advertiser ID.<br/>
* `archived` - _optional_ - Select only archived creatives. Leave blank to select archived and unarchived creatives.<br/>
* `campaignId` - _optional_ - Select only creatives with this campaign ID.<br/>
* `companionCreativeIds` - _optional_ - Select only in-stream video creatives with these companion IDs.<br/>
* `creativeFieldIds` - _optional_ - Select only creatives with these creative field IDs.<br/>
* `ids` - _optional_ - Select only creatives with these IDs.<br/>
* `maxResults` - _optional_ - Maximum number of results to return.<br/>
* `pageToken` - _optional_ - Value of the nextPageToken from the previous result page.<br/>
* `renderingIds` - _optional_ - Select only creatives with these rendering IDs.<br/>
* `searchString` - _optional_ - Allows searching for objects by name or ID. Wildcards (*) are allowed. For example, "creative*2015" will return objects with names like "creative June 2015", "creative April 2015", or simply "creative 2015". Most of the searches also add wildcards implicitly at the start and the end of the search string. For example, a search string of "creative" will match objects with name "my creative", "creative 2015", or simply "creative".<br/>
* `sizeIds` - _optional_ - Select only creatives with these size IDs.<br/>
* `sortField` - _optional_ - Field by which to sort the list.<br/>
    Possible values: ID, NAME.
* `sortOrder` - _optional_ - Order of sorted results.<br/>
    Possible values: ASCENDING, DESCENDING.
* `studioCreativeId` - _optional_ - Select only creatives corresponding to this Studio creative ID.<br/>
* `types` - _optional_ - Select only creatives with these creative types.<br/>

### dfareporting.creatives.patch
> Updates an existing creative. This method supports patch semantics.<br/>

*Tags:* `creatives`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Creative ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.creatives.insert
> Inserts a new creative.<br/>

*Tags:* `creatives`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.creatives.update
> Updates an existing creative.<br/>

*Tags:* `creatives`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.creatives.get
> Gets one creative by ID.<br/>

*Tags:* `creatives`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Creative ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.dimensionValues.query
> Retrieves list of report dimension values for a list of filters.<br/>

*Tags:* `dimensionValues`

#### Input Parameters
* `profileId` - _required_ - The DFA user profile ID.<br/>
* `maxResults` - _optional_ - Maximum number of results to return.<br/>
* `pageToken` - _optional_ - The value of the nextToken from the previous result page.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.directorySites.list
> Retrieves a list of directory sites, possibly filtered. This method supports paging.<br/>

*Tags:* `directorySites`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `acceptsInStreamVideoPlacements` - _optional_ - This search filter is no longer supported and will have no effect on the results returned.<br/>
* `acceptsInterstitialPlacements` - _optional_ - This search filter is no longer supported and will have no effect on the results returned.<br/>
* `acceptsPublisherPaidPlacements` - _optional_ - Select only directory sites that accept publisher paid placements. This field can be left blank.<br/>
* `active` - _optional_ - Select only active directory sites. Leave blank to retrieve both active and inactive directory sites.<br/>
* `dfpNetworkCode` - _optional_ - Select only directory sites with this Ad Manager network code.<br/>
* `ids` - _optional_ - Select only directory sites with these IDs.<br/>
* `maxResults` - _optional_ - Maximum number of results to return.<br/>
* `pageToken` - _optional_ - Value of the nextPageToken from the previous result page.<br/>
* `searchString` - _optional_ - Allows searching for objects by name, ID or URL. Wildcards (*) are allowed. For example, "directory site*2015" will return objects with names like "directory site June 2015", "directory site April 2015", or simply "directory site 2015". Most of the searches also add wildcards implicitly at the start and the end of the search string. For example, a search string of "directory site" will match objects with name "my directory site", "directory site 2015" or simply, "directory site".<br/>
* `sortField` - _optional_ - Field by which to sort the list.<br/>
    Possible values: ID, NAME.
* `sortOrder` - _optional_ - Order of sorted results.<br/>
    Possible values: ASCENDING, DESCENDING.

### dfareporting.directorySites.insert
> Inserts a new directory site.<br/>

*Tags:* `directorySites`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.directorySites.get
> Gets one directory site by ID.<br/>

*Tags:* `directorySites`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Directory site ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.dynamicTargetingKeys.list
> Retrieves a list of dynamic targeting keys.<br/>

*Tags:* `dynamicTargetingKeys`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `advertiserId` - _optional_ - Select only dynamic targeting keys whose object has this advertiser ID.<br/>
* `names` - _optional_ - Select only dynamic targeting keys exactly matching these names.<br/>
* `objectId` - _optional_ - Select only dynamic targeting keys with this object ID.<br/>
* `objectType` - _optional_ - Select only dynamic targeting keys with this object type.<br/>
    Possible values: OBJECT_AD, OBJECT_ADVERTISER, OBJECT_CREATIVE, OBJECT_PLACEMENT.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.dynamicTargetingKeys.insert
> Inserts a new dynamic targeting key. Keys must be created at the advertiser level before being assigned to the advertiser's ads, creatives, or placements. There is a maximum of 1000 keys per advertiser, out of which a maximum of 20 keys can be assigned per ad, creative, or placement.<br/>

*Tags:* `dynamicTargetingKeys`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.dynamicTargetingKeys.delete
> Deletes an existing dynamic targeting key.<br/>

*Tags:* `dynamicTargetingKeys`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `objectId` - _required_ - ID of the object of this dynamic targeting key. This is a required field.<br/>
* `name` - _required_ - Name of this dynamic targeting key. This is a required field. Must be less than 256 characters long and cannot contain commas. All characters are converted to lowercase.<br/>
* `objectType` - _required_ - Type of the object of this dynamic targeting key. This is a required field.<br/>
    Possible values: OBJECT_AD, OBJECT_ADVERTISER, OBJECT_CREATIVE, OBJECT_PLACEMENT.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.eventTags.list
> Retrieves a list of event tags, possibly filtered.<br/>

*Tags:* `eventTags`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `adId` - _optional_ - Select only event tags that belong to this ad.<br/>
* `advertiserId` - _optional_ - Select only event tags that belong to this advertiser.<br/>
* `campaignId` - _optional_ - Select only event tags that belong to this campaign.<br/>
* `definitionsOnly` - _optional_ - Examine only the specified campaign or advertiser's event tags for matching selector criteria. When set to false, the parent advertiser and parent campaign of the specified ad or campaign is examined as well. In addition, when set to false, the status field is examined as well, along with the enabledByDefault field. This parameter can not be set to true when adId is specified as ads do not define their own even tags.<br/>
* `enabled` - _optional_ - Select only enabled event tags. What is considered enabled or disabled depends on the definitionsOnly parameter. When definitionsOnly is set to true, only the specified advertiser or campaign's event tags' enabledByDefault field is examined. When definitionsOnly is set to false, the specified ad or specified campaign's parent advertiser's or parent campaign's event tags' enabledByDefault and status fields are examined as well.<br/>
* `eventTagTypes` - _optional_ - Select only event tags with the specified event tag types. Event tag types can be used to specify whether to use a third-party pixel, a third-party JavaScript URL, or a third-party click-through URL for either impression or click tracking.<br/>
* `ids` - _optional_ - Select only event tags with these IDs.<br/>
* `searchString` - _optional_ - Allows searching for objects by name or ID. Wildcards (*) are allowed. For example, "eventtag*2015" will return objects with names like "eventtag June 2015", "eventtag April 2015", or simply "eventtag 2015". Most of the searches also add wildcards implicitly at the start and the end of the search string. For example, a search string of "eventtag" will match objects with name "my eventtag", "eventtag 2015", or simply "eventtag".<br/>
* `sortField` - _optional_ - Field by which to sort the list.<br/>
    Possible values: ID, NAME.
* `sortOrder` - _optional_ - Order of sorted results.<br/>
    Possible values: ASCENDING, DESCENDING.

### dfareporting.eventTags.patch
> Updates an existing event tag. This method supports patch semantics.<br/>

*Tags:* `eventTags`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Event tag ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.eventTags.insert
> Inserts a new event tag.<br/>

*Tags:* `eventTags`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.eventTags.update
> Updates an existing event tag.<br/>

*Tags:* `eventTags`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.eventTags.delete
> Deletes an existing event tag.<br/>

*Tags:* `eventTags`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Event tag ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.eventTags.get
> Gets one event tag by ID.<br/>

*Tags:* `eventTags`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Event tag ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.files.list
> Lists files for a user profile.<br/>

*Tags:* `files`

#### Input Parameters
* `profileId` - _required_ - The DFA profile ID.<br/>
* `maxResults` - _optional_ - Maximum number of results to return.<br/>
* `pageToken` - _optional_ - The value of the nextToken from the previous result page.<br/>
* `scope` - _optional_ - The scope that defines which results are returned.<br/>
    Possible values: ALL, MINE, SHARED_WITH_ME.
* `sortField` - _optional_ - The field by which to sort the list.<br/>
    Possible values: ID, LAST_MODIFIED_TIME.
* `sortOrder` - _optional_ - Order of sorted results.<br/>
    Possible values: ASCENDING, DESCENDING.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.floodlightActivities.list
> Retrieves a list of floodlight activities, possibly filtered. This method supports paging.<br/>

*Tags:* `floodlightActivities`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `advertiserId` - _optional_ - Select only floodlight activities for the specified advertiser ID. Must specify either ids, advertiserId, or floodlightConfigurationId for a non-empty result.<br/>
* `floodlightActivityGroupIds` - _optional_ - Select only floodlight activities with the specified floodlight activity group IDs.<br/>
* `floodlightActivityGroupName` - _optional_ - Select only floodlight activities with the specified floodlight activity group name.<br/>
* `floodlightActivityGroupTagString` - _optional_ - Select only floodlight activities with the specified floodlight activity group tag string.<br/>
* `floodlightActivityGroupType` - _optional_ - Select only floodlight activities with the specified floodlight activity group type.<br/>
    Possible values: COUNTER, SALE.
* `floodlightConfigurationId` - _optional_ - Select only floodlight activities for the specified floodlight configuration ID. Must specify either ids, advertiserId, or floodlightConfigurationId for a non-empty result.<br/>
* `ids` - _optional_ - Select only floodlight activities with the specified IDs. Must specify either ids, advertiserId, or floodlightConfigurationId for a non-empty result.<br/>
* `maxResults` - _optional_ - Maximum number of results to return.<br/>
* `pageToken` - _optional_ - Value of the nextPageToken from the previous result page.<br/>
* `searchString` - _optional_ - Allows searching for objects by name or ID. Wildcards (*) are allowed. For example, "floodlightactivity*2015" will return objects with names like "floodlightactivity June 2015", "floodlightactivity April 2015", or simply "floodlightactivity 2015". Most of the searches also add wildcards implicitly at the start and the end of the search string. For example, a search string of "floodlightactivity" will match objects with name "my floodlightactivity activity", "floodlightactivity 2015", or simply "floodlightactivity".<br/>
* `sortField` - _optional_ - Field by which to sort the list.<br/>
    Possible values: ID, NAME.
* `sortOrder` - _optional_ - Order of sorted results.<br/>
    Possible values: ASCENDING, DESCENDING.
* `tagString` - _optional_ - Select only floodlight activities with the specified tag string.<br/>

### dfareporting.floodlightActivities.patch
> Updates an existing floodlight activity. This method supports patch semantics.<br/>

*Tags:* `floodlightActivities`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Floodlight activity ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.floodlightActivities.insert
> Inserts a new floodlight activity.<br/>

*Tags:* `floodlightActivities`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.floodlightActivities.update
> Updates an existing floodlight activity.<br/>

*Tags:* `floodlightActivities`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.floodlightActivities.generatetag
> Generates a tag for a floodlight activity.<br/>

*Tags:* `floodlightActivities`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `floodlightActivityId` - _optional_ - Floodlight activity ID for which we want to generate a tag.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.floodlightActivities.delete
> Deletes an existing floodlight activity.<br/>

*Tags:* `floodlightActivities`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Floodlight activity ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.floodlightActivities.get
> Gets one floodlight activity by ID.<br/>

*Tags:* `floodlightActivities`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Floodlight activity ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.floodlightActivityGroups.list
> Retrieves a list of floodlight activity groups, possibly filtered. This method supports paging.<br/>

*Tags:* `floodlightActivityGroups`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `advertiserId` - _optional_ - Select only floodlight activity groups with the specified advertiser ID. Must specify either advertiserId or floodlightConfigurationId for a non-empty result.<br/>
* `floodlightConfigurationId` - _optional_ - Select only floodlight activity groups with the specified floodlight configuration ID. Must specify either advertiserId, or floodlightConfigurationId for a non-empty result.<br/>
* `ids` - _optional_ - Select only floodlight activity groups with the specified IDs. Must specify either advertiserId or floodlightConfigurationId for a non-empty result.<br/>
* `maxResults` - _optional_ - Maximum number of results to return.<br/>
* `pageToken` - _optional_ - Value of the nextPageToken from the previous result page.<br/>
* `searchString` - _optional_ - Allows searching for objects by name or ID. Wildcards (*) are allowed. For example, "floodlightactivitygroup*2015" will return objects with names like "floodlightactivitygroup June 2015", "floodlightactivitygroup April 2015", or simply "floodlightactivitygroup 2015". Most of the searches also add wildcards implicitly at the start and the end of the search string. For example, a search string of "floodlightactivitygroup" will match objects with name "my floodlightactivitygroup activity", "floodlightactivitygroup 2015", or simply "floodlightactivitygroup".<br/>
* `sortField` - _optional_ - Field by which to sort the list.<br/>
    Possible values: ID, NAME.
* `sortOrder` - _optional_ - Order of sorted results.<br/>
    Possible values: ASCENDING, DESCENDING.
* `type` - _optional_ - Select only floodlight activity groups with the specified floodlight activity group type.<br/>
    Possible values: COUNTER, SALE.

### dfareporting.floodlightActivityGroups.patch
> Updates an existing floodlight activity group. This method supports patch semantics.<br/>

*Tags:* `floodlightActivityGroups`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Floodlight activity Group ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.floodlightActivityGroups.insert
> Inserts a new floodlight activity group.<br/>

*Tags:* `floodlightActivityGroups`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.floodlightActivityGroups.update
> Updates an existing floodlight activity group.<br/>

*Tags:* `floodlightActivityGroups`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.floodlightActivityGroups.get
> Gets one floodlight activity group by ID.<br/>

*Tags:* `floodlightActivityGroups`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Floodlight activity Group ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.floodlightConfigurations.list
> Retrieves a list of floodlight configurations, possibly filtered.<br/>

*Tags:* `floodlightConfigurations`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `ids` - _optional_ - Set of IDs of floodlight configurations to retrieve. Required field; otherwise an empty list will be returned.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.floodlightConfigurations.patch
> Updates an existing floodlight configuration. This method supports patch semantics.<br/>

*Tags:* `floodlightConfigurations`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Floodlight configuration ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.floodlightConfigurations.update
> Updates an existing floodlight configuration.<br/>

*Tags:* `floodlightConfigurations`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.floodlightConfigurations.get
> Gets one floodlight configuration by ID.<br/>

*Tags:* `floodlightConfigurations`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Floodlight configuration ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.languages.list
> Retrieves a list of languages.<br/>

*Tags:* `languages`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.metros.list
> Retrieves a list of metros.<br/>

*Tags:* `metros`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.mobileApps.list
> Retrieves list of available mobile apps.<br/>

*Tags:* `mobileApps`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `directories` - _optional_ - Select only apps from these directories.<br/>
* `ids` - _optional_ - Select only apps with these IDs.<br/>
* `maxResults` - _optional_ - Maximum number of results to return.<br/>
* `pageToken` - _optional_ - Value of the nextPageToken from the previous result page.<br/>
* `searchString` - _optional_ - Allows searching for objects by name or ID. Wildcards (*) are allowed. For example, "app*2015" will return objects with names like "app Jan 2018", "app Jan 2018", or simply "app 2018". Most of the searches also add wildcards implicitly at the start and the end of the search string. For example, a search string of "app" will match objects with name "my app", "app 2018", or simply "app".<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.mobileApps.get
> Gets one mobile app by ID.<br/>

*Tags:* `mobileApps`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Mobile app ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.mobileCarriers.list
> Retrieves a list of mobile carriers.<br/>

*Tags:* `mobileCarriers`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.mobileCarriers.get
> Gets one mobile carrier by ID.<br/>

*Tags:* `mobileCarriers`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Mobile carrier ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.operatingSystemVersions.list
> Retrieves a list of operating system versions.<br/>

*Tags:* `operatingSystemVersions`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.operatingSystemVersions.get
> Gets one operating system version by ID.<br/>

*Tags:* `operatingSystemVersions`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Operating system version ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.operatingSystems.list
> Retrieves a list of operating systems.<br/>

*Tags:* `operatingSystems`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.operatingSystems.get
> Gets one operating system by DART ID.<br/>

*Tags:* `operatingSystems`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `dartId` - _required_ - Operating system DART ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.placementGroups.list
> Retrieves a list of placement groups, possibly filtered. This method supports paging.<br/>

*Tags:* `placementGroups`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `advertiserIds` - _optional_ - Select only placement groups that belong to these advertisers.<br/>
* `archived` - _optional_ - Select only archived placements. Don't set this field to select both archived and non-archived placements.<br/>
* `campaignIds` - _optional_ - Select only placement groups that belong to these campaigns.<br/>
* `contentCategoryIds` - _optional_ - Select only placement groups that are associated with these content categories.<br/>
* `directorySiteIds` - _optional_ - Select only placement groups that are associated with these directory sites.<br/>
* `ids` - _optional_ - Select only placement groups with these IDs.<br/>
* `maxEndDate` - _optional_ - Select only placements or placement groups whose end date is on or before the specified maxEndDate. The date should be formatted as "yyyy-MM-dd".<br/>
* `maxResults` - _optional_ - Maximum number of results to return.<br/>
* `maxStartDate` - _optional_ - Select only placements or placement groups whose start date is on or before the specified maxStartDate. The date should be formatted as "yyyy-MM-dd".<br/>
* `minEndDate` - _optional_ - Select only placements or placement groups whose end date is on or after the specified minEndDate. The date should be formatted as "yyyy-MM-dd".<br/>
* `minStartDate` - _optional_ - Select only placements or placement groups whose start date is on or after the specified minStartDate. The date should be formatted as "yyyy-MM-dd".<br/>
* `pageToken` - _optional_ - Value of the nextPageToken from the previous result page.<br/>
* `placementGroupType` - _optional_ - Select only placement groups belonging with this group type. A package is a simple group of placements that acts as a single pricing point for a group of tags. A roadblock is a group of placements that not only acts as a single pricing point but also assumes that all the tags in it will be served at the same time. A roadblock requires one of its assigned placements to be marked as primary for reporting.<br/>
    Possible values: PLACEMENT_PACKAGE, PLACEMENT_ROADBLOCK.
* `placementStrategyIds` - _optional_ - Select only placement groups that are associated with these placement strategies.<br/>
* `pricingTypes` - _optional_ - Select only placement groups with these pricing types.<br/>
* `searchString` - _optional_ - Allows searching for placement groups by name or ID. Wildcards (*) are allowed. For example, "placement*2015" will return placement groups with names like "placement group June 2015", "placement group May 2015", or simply "placements 2015". Most of the searches also add wildcards implicitly at the start and the end of the search string. For example, a search string of "placementgroup" will match placement groups with name "my placementgroup", "placementgroup 2015", or simply "placementgroup".<br/>
* `siteIds` - _optional_ - Select only placement groups that are associated with these sites.<br/>
* `sortField` - _optional_ - Field by which to sort the list.<br/>
    Possible values: ID, NAME.
* `sortOrder` - _optional_ - Order of sorted results.<br/>
    Possible values: ASCENDING, DESCENDING.

### dfareporting.placementGroups.patch
> Updates an existing placement group. This method supports patch semantics.<br/>

*Tags:* `placementGroups`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Placement group ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.placementGroups.insert
> Inserts a new placement group.<br/>

*Tags:* `placementGroups`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.placementGroups.update
> Updates an existing placement group.<br/>

*Tags:* `placementGroups`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.placementGroups.get
> Gets one placement group by ID.<br/>

*Tags:* `placementGroups`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Placement group ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.placementStrategies.list
> Retrieves a list of placement strategies, possibly filtered. This method supports paging.<br/>

*Tags:* `placementStrategies`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `ids` - _optional_ - Select only placement strategies with these IDs.<br/>
* `maxResults` - _optional_ - Maximum number of results to return.<br/>
* `pageToken` - _optional_ - Value of the nextPageToken from the previous result page.<br/>
* `searchString` - _optional_ - Allows searching for objects by name or ID. Wildcards (*) are allowed. For example, "placementstrategy*2015" will return objects with names like "placementstrategy June 2015", "placementstrategy April 2015", or simply "placementstrategy 2015". Most of the searches also add wildcards implicitly at the start and the end of the search string. For example, a search string of "placementstrategy" will match objects with name "my placementstrategy", "placementstrategy 2015", or simply "placementstrategy".<br/>
* `sortField` - _optional_ - Field by which to sort the list.<br/>
    Possible values: ID, NAME.
* `sortOrder` - _optional_ - Order of sorted results.<br/>
    Possible values: ASCENDING, DESCENDING.

### dfareporting.placementStrategies.patch
> Updates an existing placement strategy. This method supports patch semantics.<br/>

*Tags:* `placementStrategies`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Placement strategy ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.placementStrategies.insert
> Inserts a new placement strategy.<br/>

*Tags:* `placementStrategies`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.placementStrategies.update
> Updates an existing placement strategy.<br/>

*Tags:* `placementStrategies`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.placementStrategies.delete
> Deletes an existing placement strategy.<br/>

*Tags:* `placementStrategies`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Placement strategy ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.placementStrategies.get
> Gets one placement strategy by ID.<br/>

*Tags:* `placementStrategies`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Placement strategy ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.placements.list
> Retrieves a list of placements, possibly filtered. This method supports paging.<br/>

*Tags:* `placements`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `advertiserIds` - _optional_ - Select only placements that belong to these advertisers.<br/>
* `archived` - _optional_ - Select only archived placements. Don't set this field to select both archived and non-archived placements.<br/>
* `campaignIds` - _optional_ - Select only placements that belong to these campaigns.<br/>
* `compatibilities` - _optional_ - Select only placements that are associated with these compatibilities. DISPLAY and DISPLAY_INTERSTITIAL refer to rendering either on desktop or on mobile devices for regular or interstitial ads respectively. APP and APP_INTERSTITIAL are for rendering in mobile apps. IN_STREAM_VIDEO refers to rendering in in-stream video ads developed with the VAST standard.<br/>
* `contentCategoryIds` - _optional_ - Select only placements that are associated with these content categories.<br/>
* `directorySiteIds` - _optional_ - Select only placements that are associated with these directory sites.<br/>
* `groupIds` - _optional_ - Select only placements that belong to these placement groups.<br/>
* `ids` - _optional_ - Select only placements with these IDs.<br/>
* `maxEndDate` - _optional_ - Select only placements or placement groups whose end date is on or before the specified maxEndDate. The date should be formatted as "yyyy-MM-dd".<br/>
* `maxResults` - _optional_ - Maximum number of results to return.<br/>
* `maxStartDate` - _optional_ - Select only placements or placement groups whose start date is on or before the specified maxStartDate. The date should be formatted as "yyyy-MM-dd".<br/>
* `minEndDate` - _optional_ - Select only placements or placement groups whose end date is on or after the specified minEndDate. The date should be formatted as "yyyy-MM-dd".<br/>
* `minStartDate` - _optional_ - Select only placements or placement groups whose start date is on or after the specified minStartDate. The date should be formatted as "yyyy-MM-dd".<br/>
* `pageToken` - _optional_ - Value of the nextPageToken from the previous result page.<br/>
* `paymentSource` - _optional_ - Select only placements with this payment source.<br/>
    Possible values: PLACEMENT_AGENCY_PAID, PLACEMENT_PUBLISHER_PAID.
* `placementStrategyIds` - _optional_ - Select only placements that are associated with these placement strategies.<br/>
* `pricingTypes` - _optional_ - Select only placements with these pricing types.<br/>
* `searchString` - _optional_ - Allows searching for placements by name or ID. Wildcards (*) are allowed. For example, "placement*2015" will return placements with names like "placement June 2015", "placement May 2015", or simply "placements 2015". Most of the searches also add wildcards implicitly at the start and the end of the search string. For example, a search string of "placement" will match placements with name "my placement", "placement 2015", or simply "placement".<br/>
* `siteIds` - _optional_ - Select only placements that are associated with these sites.<br/>
* `sizeIds` - _optional_ - Select only placements that are associated with these sizes.<br/>
* `sortField` - _optional_ - Field by which to sort the list.<br/>
    Possible values: ID, NAME.
* `sortOrder` - _optional_ - Order of sorted results.<br/>
    Possible values: ASCENDING, DESCENDING.

### dfareporting.placements.patch
> Updates an existing placement. This method supports patch semantics.<br/>

*Tags:* `placements`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Placement ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.placements.insert
> Inserts a new placement.<br/>

*Tags:* `placements`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.placements.update
> Updates an existing placement.<br/>

*Tags:* `placements`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.placements.generatetags
> Generates tags for a placement.<br/>

*Tags:* `placements`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `campaignId` - _optional_ - Generate placements belonging to this campaign. This is a required field.<br/>
* `placementIds` - _optional_ - Generate tags for these placements.<br/>
* `tagFormats` - _optional_ - Tag formats to generate for these placements.<br/>
<br/>
Note: PLACEMENT_TAG_STANDARD can only be generated for 1x1 placements.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.placements.get
> Gets one placement by ID.<br/>

*Tags:* `placements`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Placement ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.platformTypes.list
> Retrieves a list of platform types.<br/>

*Tags:* `platformTypes`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.platformTypes.get
> Gets one platform type by ID.<br/>

*Tags:* `platformTypes`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Platform type ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.postalCodes.list
> Retrieves a list of postal codes.<br/>

*Tags:* `postalCodes`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.postalCodes.get
> Gets one postal code by ID.<br/>

*Tags:* `postalCodes`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `code` - _required_ - Postal code ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.projects.list
> Retrieves a list of projects, possibly filtered. This method supports paging.<br/>

*Tags:* `projects`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `advertiserIds` - _optional_ - Select only projects with these advertiser IDs.<br/>
* `ids` - _optional_ - Select only projects with these IDs.<br/>
* `maxResults` - _optional_ - Maximum number of results to return.<br/>
* `pageToken` - _optional_ - Value of the nextPageToken from the previous result page.<br/>
* `searchString` - _optional_ - Allows searching for projects by name or ID. Wildcards (*) are allowed. For example, "project*2015" will return projects with names like "project June 2015", "project April 2015", or simply "project 2015". Most of the searches also add wildcards implicitly at the start and the end of the search string. For example, a search string of "project" will match projects with name "my project", "project 2015", or simply "project".<br/>
* `sortField` - _optional_ - Field by which to sort the list.<br/>
    Possible values: ID, NAME.
* `sortOrder` - _optional_ - Order of sorted results.<br/>
    Possible values: ASCENDING, DESCENDING.

### dfareporting.projects.get
> Gets one project by ID.<br/>

*Tags:* `projects`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Project ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.inventoryItems.list
> Retrieves a list of inventory items, possibly filtered. This method supports paging.<br/>

*Tags:* `inventoryItems`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `projectId` - _required_ - Project ID for order documents.<br/>
* `ids` - _optional_ - Select only inventory items with these IDs.<br/>
* `inPlan` - _optional_ - Select only inventory items that are in plan.<br/>
* `maxResults` - _optional_ - Maximum number of results to return.<br/>
* `orderId` - _optional_ - Select only inventory items that belong to specified orders.<br/>
* `pageToken` - _optional_ - Value of the nextPageToken from the previous result page.<br/>
* `siteId` - _optional_ - Select only inventory items that are associated with these sites.<br/>
* `sortField` - _optional_ - Field by which to sort the list.<br/>
    Possible values: ID, NAME.
* `sortOrder` - _optional_ - Order of sorted results.<br/>
    Possible values: ASCENDING, DESCENDING.
* `type` - _optional_ - Select only inventory items with this type.<br/>
    Possible values: PLANNING_PLACEMENT_TYPE_CREDIT, PLANNING_PLACEMENT_TYPE_REGULAR.

### dfareporting.inventoryItems.get
> Gets one inventory item by ID.<br/>

*Tags:* `inventoryItems`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `projectId` - _required_ - Project ID for order documents.<br/>
* `id` - _required_ - Inventory item ID.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.orderDocuments.list
> Retrieves a list of order documents, possibly filtered. This method supports paging.<br/>

*Tags:* `orderDocuments`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `projectId` - _required_ - Project ID for order documents.<br/>
* `approved` - _optional_ - Select only order documents that have been approved by at least one user.<br/>
* `ids` - _optional_ - Select only order documents with these IDs.<br/>
* `maxResults` - _optional_ - Maximum number of results to return.<br/>
* `orderId` - _optional_ - Select only order documents for specified orders.<br/>
* `pageToken` - _optional_ - Value of the nextPageToken from the previous result page.<br/>
* `searchString` - _optional_ - Allows searching for order documents by name or ID. Wildcards (*) are allowed. For example, "orderdocument*2015" will return order documents with names like "orderdocument June 2015", "orderdocument April 2015", or simply "orderdocument 2015". Most of the searches also add wildcards implicitly at the start and the end of the search string. For example, a search string of "orderdocument" will match order documents with name "my orderdocument", "orderdocument 2015", or simply "orderdocument".<br/>
* `siteId` - _optional_ - Select only order documents that are associated with these sites.<br/>
* `sortField` - _optional_ - Field by which to sort the list.<br/>
    Possible values: ID, NAME.
* `sortOrder` - _optional_ - Order of sorted results.<br/>
    Possible values: ASCENDING, DESCENDING.

### dfareporting.orderDocuments.get
> Gets one order document by ID.<br/>

*Tags:* `orderDocuments`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `projectId` - _required_ - Project ID for order documents.<br/>
* `id` - _required_ - Order document ID.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.orders.list
> Retrieves a list of orders, possibly filtered. This method supports paging.<br/>

*Tags:* `orders`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `projectId` - _required_ - Project ID for orders.<br/>
* `ids` - _optional_ - Select only orders with these IDs.<br/>
* `maxResults` - _optional_ - Maximum number of results to return.<br/>
* `pageToken` - _optional_ - Value of the nextPageToken from the previous result page.<br/>
* `searchString` - _optional_ - Allows searching for orders by name or ID. Wildcards (*) are allowed. For example, "order*2015" will return orders with names like "order June 2015", "order April 2015", or simply "order 2015". Most of the searches also add wildcards implicitly at the start and the end of the search string. For example, a search string of "order" will match orders with name "my order", "order 2015", or simply "order".<br/>
* `siteId` - _optional_ - Select only orders that are associated with these site IDs.<br/>
* `sortField` - _optional_ - Field by which to sort the list.<br/>
    Possible values: ID, NAME.
* `sortOrder` - _optional_ - Order of sorted results.<br/>
    Possible values: ASCENDING, DESCENDING.

### dfareporting.orders.get
> Gets one order by ID.<br/>

*Tags:* `orders`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `projectId` - _required_ - Project ID for orders.<br/>
* `id` - _required_ - Order ID.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.regions.list
> Retrieves a list of regions.<br/>

*Tags:* `regions`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.remarketingListShares.patch
> Updates an existing remarketing list share. This method supports patch semantics.<br/>

*Tags:* `remarketingListShares`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `remarketingListId` - _required_ - Remarketing list ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.remarketingListShares.update
> Updates an existing remarketing list share.<br/>

*Tags:* `remarketingListShares`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.remarketingListShares.get
> Gets one remarketing list share by remarketing list ID.<br/>

*Tags:* `remarketingListShares`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `remarketingListId` - _required_ - Remarketing list ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.remarketingLists.list
> Retrieves a list of remarketing lists, possibly filtered. This method supports paging.<br/>

*Tags:* `remarketingLists`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `advertiserId` - _required_ - Select only remarketing lists owned by this advertiser.<br/>
* `active` - _optional_ - Select only active or only inactive remarketing lists.<br/>
* `floodlightActivityId` - _optional_ - Select only remarketing lists that have this floodlight activity ID.<br/>
* `maxResults` - _optional_ - Maximum number of results to return.<br/>
* `name` - _optional_ - Allows searching for objects by name or ID. Wildcards (*) are allowed. For example, "remarketing list*2015" will return objects with names like "remarketing list June 2015", "remarketing list April 2015", or simply "remarketing list 2015". Most of the searches also add wildcards implicitly at the start and the end of the search string. For example, a search string of "remarketing list" will match objects with name "my remarketing list", "remarketing list 2015", or simply "remarketing list".<br/>
* `pageToken` - _optional_ - Value of the nextPageToken from the previous result page.<br/>
* `sortField` - _optional_ - Field by which to sort the list.<br/>
    Possible values: ID, NAME.
* `sortOrder` - _optional_ - Order of sorted results.<br/>
    Possible values: ASCENDING, DESCENDING.

### dfareporting.remarketingLists.patch
> Updates an existing remarketing list. This method supports patch semantics.<br/>

*Tags:* `remarketingLists`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Remarketing list ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.remarketingLists.insert
> Inserts a new remarketing list.<br/>

*Tags:* `remarketingLists`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.remarketingLists.update
> Updates an existing remarketing list.<br/>

*Tags:* `remarketingLists`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.remarketingLists.get
> Gets one remarketing list by ID.<br/>

*Tags:* `remarketingLists`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Remarketing list ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.reports.list
> Retrieves list of reports.<br/>

*Tags:* `reports`

#### Input Parameters
* `profileId` - _required_ - The DFA user profile ID.<br/>
* `maxResults` - _optional_ - Maximum number of results to return.<br/>
* `pageToken` - _optional_ - The value of the nextToken from the previous result page.<br/>
* `scope` - _optional_ - The scope that defines which results are returned.<br/>
    Possible values: ALL, MINE.
* `sortField` - _optional_ - The field by which to sort the list.<br/>
    Possible values: ID, LAST_MODIFIED_TIME, NAME.
* `sortOrder` - _optional_ - Order of sorted results.<br/>
    Possible values: ASCENDING, DESCENDING.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.reports.insert
> Creates a report.<br/>

*Tags:* `reports`

#### Input Parameters
* `profileId` - _required_ - The DFA user profile ID.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.reports.compatibleFields.query
> Returns the fields that are compatible to be selected in the respective sections of a report criteria, given the fields already selected in the input report and user permissions.<br/>

*Tags:* `reports`

#### Input Parameters
* `profileId` - _required_ - The DFA user profile ID.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.reports.delete
> Deletes a report by its ID.<br/>

*Tags:* `reports`

#### Input Parameters
* `profileId` - _required_ - The DFA user profile ID.<br/>
* `reportId` - _required_ - The ID of the report.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.reports.get
> Retrieves a report by its ID.<br/>

*Tags:* `reports`

#### Input Parameters
* `profileId` - _required_ - The DFA user profile ID.<br/>
* `reportId` - _required_ - The ID of the report.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.reports.patch
> Updates a report. This method supports patch semantics.<br/>

*Tags:* `reports`

#### Input Parameters
* `profileId` - _required_ - The DFA user profile ID.<br/>
* `reportId` - _required_ - The ID of the report.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.reports.update
> Updates a report.<br/>

*Tags:* `reports`

#### Input Parameters
* `profileId` - _required_ - The DFA user profile ID.<br/>
* `reportId` - _required_ - The ID of the report.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.reports.files.list
> Lists files for a report.<br/>

*Tags:* `reports`

#### Input Parameters
* `profileId` - _required_ - The DFA profile ID.<br/>
* `reportId` - _required_ - The ID of the parent report.<br/>
* `maxResults` - _optional_ - Maximum number of results to return.<br/>
* `pageToken` - _optional_ - The value of the nextToken from the previous result page.<br/>
* `sortField` - _optional_ - The field by which to sort the list.<br/>
    Possible values: ID, LAST_MODIFIED_TIME.
* `sortOrder` - _optional_ - Order of sorted results.<br/>
    Possible values: ASCENDING, DESCENDING.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.reports.files.get
> Retrieves a report file. This method supports media download.<br/>

*Tags:* `reports`

#### Input Parameters
* `profileId` - _required_ - The DFA profile ID.<br/>
* `reportId` - _required_ - The ID of the report.<br/>
* `fileId` - _required_ - The ID of the report file.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.reports.run
> Runs a report.<br/>

*Tags:* `reports`

#### Input Parameters
* `profileId` - _required_ - The DFA profile ID.<br/>
* `reportId` - _required_ - The ID of the report.<br/>
* `synchronous` - _optional_ - If set and true, tries to run the report synchronously.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.sites.list
> Retrieves a list of sites, possibly filtered. This method supports paging.<br/>

*Tags:* `sites`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `acceptsInStreamVideoPlacements` - _optional_ - This search filter is no longer supported and will have no effect on the results returned.<br/>
* `acceptsInterstitialPlacements` - _optional_ - This search filter is no longer supported and will have no effect on the results returned.<br/>
* `acceptsPublisherPaidPlacements` - _optional_ - Select only sites that accept publisher paid placements.<br/>
* `adWordsSite` - _optional_ - Select only AdWords sites.<br/>
* `approved` - _optional_ - Select only approved sites.<br/>
* `campaignIds` - _optional_ - Select only sites with these campaign IDs.<br/>
* `directorySiteIds` - _optional_ - Select only sites with these directory site IDs.<br/>
* `ids` - _optional_ - Select only sites with these IDs.<br/>
* `maxResults` - _optional_ - Maximum number of results to return.<br/>
* `pageToken` - _optional_ - Value of the nextPageToken from the previous result page.<br/>
* `searchString` - _optional_ - Allows searching for objects by name, ID or keyName. Wildcards (*) are allowed. For example, "site*2015" will return objects with names like "site June 2015", "site April 2015", or simply "site 2015". Most of the searches also add wildcards implicitly at the start and the end of the search string. For example, a search string of "site" will match objects with name "my site", "site 2015", or simply "site".<br/>
* `sortField` - _optional_ - Field by which to sort the list.<br/>
    Possible values: ID, NAME.
* `sortOrder` - _optional_ - Order of sorted results.<br/>
    Possible values: ASCENDING, DESCENDING.
* `subaccountId` - _optional_ - Select only sites with this subaccount ID.<br/>
* `unmappedSite` - _optional_ - Select only sites that have not been mapped to a directory site.<br/>

### dfareporting.sites.patch
> Updates an existing site. This method supports patch semantics.<br/>

*Tags:* `sites`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Site ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.sites.insert
> Inserts a new site.<br/>

*Tags:* `sites`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.sites.update
> Updates an existing site.<br/>

*Tags:* `sites`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.sites.get
> Gets one site by ID.<br/>

*Tags:* `sites`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Site ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.sizes.list
> Retrieves a list of sizes, possibly filtered. Retrieved sizes are globally unique and may include values not currently in use by your account. Due to this, the list of sizes returned by this method may differ from the list seen in the Trafficking UI.<br/>

*Tags:* `sizes`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `height` - _optional_ - Select only sizes with this height.<br/>
* `iabStandard` - _optional_ - Select only IAB standard sizes.<br/>
* `ids` - _optional_ - Select only sizes with these IDs.<br/>
* `width` - _optional_ - Select only sizes with this width.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.sizes.insert
> Inserts a new size.<br/>

*Tags:* `sizes`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.sizes.get
> Gets one size by ID.<br/>

*Tags:* `sizes`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Size ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.subaccounts.list
> Gets a list of subaccounts, possibly filtered. This method supports paging.<br/>

*Tags:* `subaccounts`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `ids` - _optional_ - Select only subaccounts with these IDs.<br/>
* `maxResults` - _optional_ - Maximum number of results to return.<br/>
* `pageToken` - _optional_ - Value of the nextPageToken from the previous result page.<br/>
* `searchString` - _optional_ - Allows searching for objects by name or ID. Wildcards (*) are allowed. For example, "subaccount*2015" will return objects with names like "subaccount June 2015", "subaccount April 2015", or simply "subaccount 2015". Most of the searches also add wildcards implicitly at the start and the end of the search string. For example, a search string of "subaccount" will match objects with name "my subaccount", "subaccount 2015", or simply "subaccount".<br/>
* `sortField` - _optional_ - Field by which to sort the list.<br/>
    Possible values: ID, NAME.
* `sortOrder` - _optional_ - Order of sorted results.<br/>
    Possible values: ASCENDING, DESCENDING.

### dfareporting.subaccounts.patch
> Updates an existing subaccount. This method supports patch semantics.<br/>

*Tags:* `subaccounts`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Subaccount ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.subaccounts.insert
> Inserts a new subaccount.<br/>

*Tags:* `subaccounts`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.subaccounts.update
> Updates an existing subaccount.<br/>

*Tags:* `subaccounts`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.subaccounts.get
> Gets one subaccount by ID.<br/>

*Tags:* `subaccounts`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Subaccount ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.targetableRemarketingLists.list
> Retrieves a list of targetable remarketing lists, possibly filtered. This method supports paging.<br/>

*Tags:* `targetableRemarketingLists`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `advertiserId` - _required_ - Select only targetable remarketing lists targetable by these advertisers.<br/>
* `active` - _optional_ - Select only active or only inactive targetable remarketing lists.<br/>
* `maxResults` - _optional_ - Maximum number of results to return.<br/>
* `name` - _optional_ - Allows searching for objects by name or ID. Wildcards (*) are allowed. For example, "remarketing list*2015" will return objects with names like "remarketing list June 2015", "remarketing list April 2015", or simply "remarketing list 2015". Most of the searches also add wildcards implicitly at the start and the end of the search string. For example, a search string of "remarketing list" will match objects with name "my remarketing list", "remarketing list 2015", or simply "remarketing list".<br/>
* `pageToken` - _optional_ - Value of the nextPageToken from the previous result page.<br/>
* `sortField` - _optional_ - Field by which to sort the list.<br/>
    Possible values: ID, NAME.
* `sortOrder` - _optional_ - Order of sorted results.<br/>
    Possible values: ASCENDING, DESCENDING.

### dfareporting.targetableRemarketingLists.get
> Gets one remarketing list by ID.<br/>

*Tags:* `targetableRemarketingLists`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Remarketing list ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.targetingTemplates.list
> Retrieves a list of targeting templates, optionally filtered. This method supports paging.<br/>

*Tags:* `targetingTemplates`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `advertiserId` - _optional_ - Select only targeting templates with this advertiser ID.<br/>
* `ids` - _optional_ - Select only targeting templates with these IDs.<br/>
* `maxResults` - _optional_ - Maximum number of results to return.<br/>
* `pageToken` - _optional_ - Value of the nextPageToken from the previous result page.<br/>
* `searchString` - _optional_ - Allows searching for objects by name or ID. Wildcards (*) are allowed. For example, "template*2015" will return objects with names like "template June 2015", "template April 2015", or simply "template 2015". Most of the searches also add wildcards implicitly at the start and the end of the search string. For example, a search string of "template" will match objects with name "my template", "template 2015", or simply "template".<br/>
* `sortField` - _optional_ - Field by which to sort the list.<br/>
    Possible values: ID, NAME.
* `sortOrder` - _optional_ - Order of sorted results.<br/>
    Possible values: ASCENDING, DESCENDING.

### dfareporting.targetingTemplates.patch
> Updates an existing targeting template. This method supports patch semantics.<br/>

*Tags:* `targetingTemplates`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Targeting template ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.targetingTemplates.insert
> Inserts a new targeting template.<br/>

*Tags:* `targetingTemplates`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.targetingTemplates.update
> Updates an existing targeting template.<br/>

*Tags:* `targetingTemplates`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.targetingTemplates.get
> Gets one targeting template by ID.<br/>

*Tags:* `targetingTemplates`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Targeting template ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.userRolePermissionGroups.list
> Gets a list of all supported user role permission groups.<br/>

*Tags:* `userRolePermissionGroups`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.userRolePermissionGroups.get
> Gets one user role permission group by ID.<br/>

*Tags:* `userRolePermissionGroups`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - User role permission group ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.userRolePermissions.list
> Gets a list of user role permissions, possibly filtered.<br/>

*Tags:* `userRolePermissions`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `ids` - _optional_ - Select only user role permissions with these IDs.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.userRolePermissions.get
> Gets one user role permission by ID.<br/>

*Tags:* `userRolePermissions`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - User role permission ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.userRoles.list
> Retrieves a list of user roles, possibly filtered. This method supports paging.<br/>

*Tags:* `userRoles`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `accountUserRoleOnly` - _optional_ - Select only account level user roles not associated with any specific subaccount.<br/>
* `ids` - _optional_ - Select only user roles with the specified IDs.<br/>
* `maxResults` - _optional_ - Maximum number of results to return.<br/>
* `pageToken` - _optional_ - Value of the nextPageToken from the previous result page.<br/>
* `searchString` - _optional_ - Allows searching for objects by name or ID. Wildcards (*) are allowed. For example, "userrole*2015" will return objects with names like "userrole June 2015", "userrole April 2015", or simply "userrole 2015". Most of the searches also add wildcards implicitly at the start and the end of the search string. For example, a search string of "userrole" will match objects with name "my userrole", "userrole 2015", or simply "userrole".<br/>
* `sortField` - _optional_ - Field by which to sort the list.<br/>
    Possible values: ID, NAME.
* `sortOrder` - _optional_ - Order of sorted results.<br/>
    Possible values: ASCENDING, DESCENDING.
* `subaccountId` - _optional_ - Select only user roles that belong to this subaccount.<br/>

### dfareporting.userRoles.patch
> Updates an existing user role. This method supports patch semantics.<br/>

*Tags:* `userRoles`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - User role ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.userRoles.insert
> Inserts a new user role.<br/>

*Tags:* `userRoles`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.userRoles.update
> Updates an existing user role.<br/>

*Tags:* `userRoles`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.userRoles.delete
> Deletes an existing user role.<br/>

*Tags:* `userRoles`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - User role ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.userRoles.get
> Gets one user role by ID.<br/>

*Tags:* `userRoles`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - User role ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.videoFormats.list
> Lists available video formats.<br/>

*Tags:* `videoFormats`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

### dfareporting.videoFormats.get
> Gets one video format by ID.<br/>

*Tags:* `videoFormats`

#### Input Parameters
* `profileId` - _required_ - User profile ID associated with this request.<br/>
* `id` - _required_ - Video format ID.<br/>
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.<br/>
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.<br/>
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.<br/>
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.<br/>
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.<br/>

## License

**flow**ground :- Telekom iPaaS / dcm-dfa-reporting-and-trafficking-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
