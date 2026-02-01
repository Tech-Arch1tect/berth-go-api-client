# CreateRoleResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**RoleWithPermissions**](RoleWithPermissions.md) |  | 
**Success** | **bool** |  | 

## Methods

### NewCreateRoleResponse

`func NewCreateRoleResponse(data RoleWithPermissions, success bool, ) *CreateRoleResponse`

NewCreateRoleResponse instantiates a new CreateRoleResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateRoleResponseWithDefaults

`func NewCreateRoleResponseWithDefaults() *CreateRoleResponse`

NewCreateRoleResponseWithDefaults instantiates a new CreateRoleResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *CreateRoleResponse) GetData() RoleWithPermissions`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *CreateRoleResponse) GetDataOk() (*RoleWithPermissions, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *CreateRoleResponse) SetData(v RoleWithPermissions)`

SetData sets Data field to given value.


### GetSuccess

`func (o *CreateRoleResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *CreateRoleResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *CreateRoleResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


