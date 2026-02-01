# GetUserRolesResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AllRoles** | [**[]RoleInfo**](RoleInfo.md) |  | 
**User** | [**UserInfo**](UserInfo.md) |  | 

## Methods

### NewGetUserRolesResponseData

`func NewGetUserRolesResponseData(allRoles []RoleInfo, user UserInfo, ) *GetUserRolesResponseData`

NewGetUserRolesResponseData instantiates a new GetUserRolesResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetUserRolesResponseDataWithDefaults

`func NewGetUserRolesResponseDataWithDefaults() *GetUserRolesResponseData`

NewGetUserRolesResponseDataWithDefaults instantiates a new GetUserRolesResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAllRoles

`func (o *GetUserRolesResponseData) GetAllRoles() []RoleInfo`

GetAllRoles returns the AllRoles field if non-nil, zero value otherwise.

### GetAllRolesOk

`func (o *GetUserRolesResponseData) GetAllRolesOk() (*[]RoleInfo, bool)`

GetAllRolesOk returns a tuple with the AllRoles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllRoles

`func (o *GetUserRolesResponseData) SetAllRoles(v []RoleInfo)`

SetAllRoles sets AllRoles field to given value.


### GetUser

`func (o *GetUserRolesResponseData) GetUser() UserInfo`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *GetUserRolesResponseData) GetUserOk() (*UserInfo, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *GetUserRolesResponseData) SetUser(v UserInfo)`

SetUser sets User field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


