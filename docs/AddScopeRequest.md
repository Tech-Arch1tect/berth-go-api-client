# AddScopeRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Permission** | **string** |  | 
**ServerId** | Pointer to **NullableInt32** |  | [optional] 
**StackPattern** | **string** |  | 

## Methods

### NewAddScopeRequest

`func NewAddScopeRequest(permission string, stackPattern string, ) *AddScopeRequest`

NewAddScopeRequest instantiates a new AddScopeRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAddScopeRequestWithDefaults

`func NewAddScopeRequestWithDefaults() *AddScopeRequest`

NewAddScopeRequestWithDefaults instantiates a new AddScopeRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPermission

`func (o *AddScopeRequest) GetPermission() string`

GetPermission returns the Permission field if non-nil, zero value otherwise.

### GetPermissionOk

`func (o *AddScopeRequest) GetPermissionOk() (*string, bool)`

GetPermissionOk returns a tuple with the Permission field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermission

`func (o *AddScopeRequest) SetPermission(v string)`

SetPermission sets Permission field to given value.


### GetServerId

`func (o *AddScopeRequest) GetServerId() int32`

GetServerId returns the ServerId field if non-nil, zero value otherwise.

### GetServerIdOk

`func (o *AddScopeRequest) GetServerIdOk() (*int32, bool)`

GetServerIdOk returns a tuple with the ServerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerId

`func (o *AddScopeRequest) SetServerId(v int32)`

SetServerId sets ServerId field to given value.

### HasServerId

`func (o *AddScopeRequest) HasServerId() bool`

HasServerId returns a boolean if a field has been set.

### SetServerIdNil

`func (o *AddScopeRequest) SetServerIdNil(b bool)`

 SetServerIdNil sets the value for ServerId to be an explicit nil

### UnsetServerId
`func (o *AddScopeRequest) UnsetServerId()`

UnsetServerId ensures that no value is present for ServerId, not even an explicit nil
### GetStackPattern

`func (o *AddScopeRequest) GetStackPattern() string`

GetStackPattern returns the StackPattern field if non-nil, zero value otherwise.

### GetStackPatternOk

`func (o *AddScopeRequest) GetStackPatternOk() (*string, bool)`

GetStackPatternOk returns a tuple with the StackPattern field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStackPattern

`func (o *AddScopeRequest) SetStackPattern(v string)`

SetStackPattern sets StackPattern field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


