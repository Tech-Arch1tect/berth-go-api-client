# RevokeRoleRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RoleId** | **int32** |  | 
**UserId** | **int32** |  | 

## Methods

### NewRevokeRoleRequest

`func NewRevokeRoleRequest(roleId int32, userId int32, ) *RevokeRoleRequest`

NewRevokeRoleRequest instantiates a new RevokeRoleRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRevokeRoleRequestWithDefaults

`func NewRevokeRoleRequestWithDefaults() *RevokeRoleRequest`

NewRevokeRoleRequestWithDefaults instantiates a new RevokeRoleRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRoleId

`func (o *RevokeRoleRequest) GetRoleId() int32`

GetRoleId returns the RoleId field if non-nil, zero value otherwise.

### GetRoleIdOk

`func (o *RevokeRoleRequest) GetRoleIdOk() (*int32, bool)`

GetRoleIdOk returns a tuple with the RoleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoleId

`func (o *RevokeRoleRequest) SetRoleId(v int32)`

SetRoleId sets RoleId field to given value.


### GetUserId

`func (o *RevokeRoleRequest) GetUserId() int32`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *RevokeRoleRequest) GetUserIdOk() (*int32, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *RevokeRoleRequest) SetUserId(v int32)`

SetUserId sets UserId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


