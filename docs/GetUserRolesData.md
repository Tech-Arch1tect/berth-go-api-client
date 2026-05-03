# GetUserRolesData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AllRoles** | [**[]RoleInfo**](RoleInfo.md) |  | 
**User** | [**UserInfo**](UserInfo.md) |  | 

## Methods

### NewGetUserRolesData

`func NewGetUserRolesData(allRoles []RoleInfo, user UserInfo, ) *GetUserRolesData`

NewGetUserRolesData instantiates a new GetUserRolesData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetUserRolesDataWithDefaults

`func NewGetUserRolesDataWithDefaults() *GetUserRolesData`

NewGetUserRolesDataWithDefaults instantiates a new GetUserRolesData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAllRoles

`func (o *GetUserRolesData) GetAllRoles() []RoleInfo`

GetAllRoles returns the AllRoles field if non-nil, zero value otherwise.

### GetAllRolesOk

`func (o *GetUserRolesData) GetAllRolesOk() (*[]RoleInfo, bool)`

GetAllRolesOk returns a tuple with the AllRoles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllRoles

`func (o *GetUserRolesData) SetAllRoles(v []RoleInfo)`

SetAllRoles sets AllRoles field to given value.


### GetUser

`func (o *GetUserRolesData) GetUser() UserInfo`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *GetUserRolesData) GetUserOk() (*UserInfo, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *GetUserRolesData) SetUser(v UserInfo)`

SetUser sets User field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


