# StackPermissionRule

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**IsStackBased** | **bool** |  | 
**PermissionId** | **int32** |  | 
**ServerId** | **int32** |  | 
**StackPattern** | **string** |  | 

## Methods

### NewStackPermissionRule

`func NewStackPermissionRule(id int32, isStackBased bool, permissionId int32, serverId int32, stackPattern string, ) *StackPermissionRule`

NewStackPermissionRule instantiates a new StackPermissionRule object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStackPermissionRuleWithDefaults

`func NewStackPermissionRuleWithDefaults() *StackPermissionRule`

NewStackPermissionRuleWithDefaults instantiates a new StackPermissionRule object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *StackPermissionRule) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *StackPermissionRule) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *StackPermissionRule) SetId(v int32)`

SetId sets Id field to given value.


### GetIsStackBased

`func (o *StackPermissionRule) GetIsStackBased() bool`

GetIsStackBased returns the IsStackBased field if non-nil, zero value otherwise.

### GetIsStackBasedOk

`func (o *StackPermissionRule) GetIsStackBasedOk() (*bool, bool)`

GetIsStackBasedOk returns a tuple with the IsStackBased field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsStackBased

`func (o *StackPermissionRule) SetIsStackBased(v bool)`

SetIsStackBased sets IsStackBased field to given value.


### GetPermissionId

`func (o *StackPermissionRule) GetPermissionId() int32`

GetPermissionId returns the PermissionId field if non-nil, zero value otherwise.

### GetPermissionIdOk

`func (o *StackPermissionRule) GetPermissionIdOk() (*int32, bool)`

GetPermissionIdOk returns a tuple with the PermissionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissionId

`func (o *StackPermissionRule) SetPermissionId(v int32)`

SetPermissionId sets PermissionId field to given value.


### GetServerId

`func (o *StackPermissionRule) GetServerId() int32`

GetServerId returns the ServerId field if non-nil, zero value otherwise.

### GetServerIdOk

`func (o *StackPermissionRule) GetServerIdOk() (*int32, bool)`

GetServerIdOk returns a tuple with the ServerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerId

`func (o *StackPermissionRule) SetServerId(v int32)`

SetServerId sets ServerId field to given value.


### GetStackPattern

`func (o *StackPermissionRule) GetStackPattern() string`

GetStackPattern returns the StackPattern field if non-nil, zero value otherwise.

### GetStackPatternOk

`func (o *StackPermissionRule) GetStackPatternOk() (*string, bool)`

GetStackPatternOk returns a tuple with the StackPattern field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStackPattern

`func (o *StackPermissionRule) SetStackPattern(v string)`

SetStackPattern sets StackPattern field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


