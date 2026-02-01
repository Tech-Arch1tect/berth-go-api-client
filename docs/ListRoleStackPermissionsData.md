# ListRoleStackPermissionsData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PermissionRules** | [**[]StackPermissionRule**](StackPermissionRule.md) |  | 
**Permissions** | [**[]PermissionInfo**](PermissionInfo.md) |  | 
**Role** | [**RoleInfo**](RoleInfo.md) |  | 
**Servers** | [**[]ServerInfo2**](ServerInfo2.md) |  | 

## Methods

### NewListRoleStackPermissionsData

`func NewListRoleStackPermissionsData(permissionRules []StackPermissionRule, permissions []PermissionInfo, role RoleInfo, servers []ServerInfo2, ) *ListRoleStackPermissionsData`

NewListRoleStackPermissionsData instantiates a new ListRoleStackPermissionsData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListRoleStackPermissionsDataWithDefaults

`func NewListRoleStackPermissionsDataWithDefaults() *ListRoleStackPermissionsData`

NewListRoleStackPermissionsDataWithDefaults instantiates a new ListRoleStackPermissionsData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPermissionRules

`func (o *ListRoleStackPermissionsData) GetPermissionRules() []StackPermissionRule`

GetPermissionRules returns the PermissionRules field if non-nil, zero value otherwise.

### GetPermissionRulesOk

`func (o *ListRoleStackPermissionsData) GetPermissionRulesOk() (*[]StackPermissionRule, bool)`

GetPermissionRulesOk returns a tuple with the PermissionRules field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissionRules

`func (o *ListRoleStackPermissionsData) SetPermissionRules(v []StackPermissionRule)`

SetPermissionRules sets PermissionRules field to given value.


### GetPermissions

`func (o *ListRoleStackPermissionsData) GetPermissions() []PermissionInfo`

GetPermissions returns the Permissions field if non-nil, zero value otherwise.

### GetPermissionsOk

`func (o *ListRoleStackPermissionsData) GetPermissionsOk() (*[]PermissionInfo, bool)`

GetPermissionsOk returns a tuple with the Permissions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissions

`func (o *ListRoleStackPermissionsData) SetPermissions(v []PermissionInfo)`

SetPermissions sets Permissions field to given value.


### GetRole

`func (o *ListRoleStackPermissionsData) GetRole() RoleInfo`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *ListRoleStackPermissionsData) GetRoleOk() (*RoleInfo, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *ListRoleStackPermissionsData) SetRole(v RoleInfo)`

SetRole sets Role field to given value.


### GetServers

`func (o *ListRoleStackPermissionsData) GetServers() []ServerInfo2`

GetServers returns the Servers field if non-nil, zero value otherwise.

### GetServersOk

`func (o *ListRoleStackPermissionsData) GetServersOk() (*[]ServerInfo2, bool)`

GetServersOk returns a tuple with the Servers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServers

`func (o *ListRoleStackPermissionsData) SetServers(v []ServerInfo2)`

SetServers sets Servers field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


