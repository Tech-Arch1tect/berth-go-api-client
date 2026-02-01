# RoleWithPermissions

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | **string** |  | 
**Id** | **int32** |  | 
**IsAdmin** | **bool** |  | 
**Name** | **string** |  | 
**Permissions** | [**[]PermissionInfo**](PermissionInfo.md) |  | 

## Methods

### NewRoleWithPermissions

`func NewRoleWithPermissions(description string, id int32, isAdmin bool, name string, permissions []PermissionInfo, ) *RoleWithPermissions`

NewRoleWithPermissions instantiates a new RoleWithPermissions object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRoleWithPermissionsWithDefaults

`func NewRoleWithPermissionsWithDefaults() *RoleWithPermissions`

NewRoleWithPermissionsWithDefaults instantiates a new RoleWithPermissions object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *RoleWithPermissions) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *RoleWithPermissions) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *RoleWithPermissions) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetId

`func (o *RoleWithPermissions) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RoleWithPermissions) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RoleWithPermissions) SetId(v int32)`

SetId sets Id field to given value.


### GetIsAdmin

`func (o *RoleWithPermissions) GetIsAdmin() bool`

GetIsAdmin returns the IsAdmin field if non-nil, zero value otherwise.

### GetIsAdminOk

`func (o *RoleWithPermissions) GetIsAdminOk() (*bool, bool)`

GetIsAdminOk returns a tuple with the IsAdmin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsAdmin

`func (o *RoleWithPermissions) SetIsAdmin(v bool)`

SetIsAdmin sets IsAdmin field to given value.


### GetName

`func (o *RoleWithPermissions) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *RoleWithPermissions) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *RoleWithPermissions) SetName(v string)`

SetName sets Name field to given value.


### GetPermissions

`func (o *RoleWithPermissions) GetPermissions() []PermissionInfo`

GetPermissions returns the Permissions field if non-nil, zero value otherwise.

### GetPermissionsOk

`func (o *RoleWithPermissions) GetPermissionsOk() (*[]PermissionInfo, bool)`

GetPermissionsOk returns a tuple with the Permissions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissions

`func (o *RoleWithPermissions) SetPermissions(v []PermissionInfo)`

SetPermissions sets Permissions field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


