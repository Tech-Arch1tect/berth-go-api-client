# CreateStackPermissionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PermissionId** | **int32** |  | 
**ServerId** | **int32** |  | 
**StackPattern** | **string** |  | 

## Methods

### NewCreateStackPermissionRequest

`func NewCreateStackPermissionRequest(permissionId int32, serverId int32, stackPattern string, ) *CreateStackPermissionRequest`

NewCreateStackPermissionRequest instantiates a new CreateStackPermissionRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateStackPermissionRequestWithDefaults

`func NewCreateStackPermissionRequestWithDefaults() *CreateStackPermissionRequest`

NewCreateStackPermissionRequestWithDefaults instantiates a new CreateStackPermissionRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPermissionId

`func (o *CreateStackPermissionRequest) GetPermissionId() int32`

GetPermissionId returns the PermissionId field if non-nil, zero value otherwise.

### GetPermissionIdOk

`func (o *CreateStackPermissionRequest) GetPermissionIdOk() (*int32, bool)`

GetPermissionIdOk returns a tuple with the PermissionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissionId

`func (o *CreateStackPermissionRequest) SetPermissionId(v int32)`

SetPermissionId sets PermissionId field to given value.


### GetServerId

`func (o *CreateStackPermissionRequest) GetServerId() int32`

GetServerId returns the ServerId field if non-nil, zero value otherwise.

### GetServerIdOk

`func (o *CreateStackPermissionRequest) GetServerIdOk() (*int32, bool)`

GetServerIdOk returns a tuple with the ServerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerId

`func (o *CreateStackPermissionRequest) SetServerId(v int32)`

SetServerId sets ServerId field to given value.


### GetStackPattern

`func (o *CreateStackPermissionRequest) GetStackPattern() string`

GetStackPattern returns the StackPattern field if non-nil, zero value otherwise.

### GetStackPatternOk

`func (o *CreateStackPermissionRequest) GetStackPatternOk() (*string, bool)`

GetStackPatternOk returns a tuple with the StackPattern field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStackPattern

`func (o *CreateStackPermissionRequest) SetStackPattern(v string)`

SetStackPattern sets StackPattern field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


