# APIKeyScopeInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApiKeyId** | **int32** |  | 
**CreatedAt** | **string** |  | 
**Id** | **int32** |  | 
**Permission** | **string** |  | 
**PermissionId** | **int32** |  | 
**ServerId** | **NullableInt32** |  | 
**ServerName** | Pointer to **string** |  | [optional] 
**StackPattern** | **string** |  | 
**UpdatedAt** | **string** |  | 

## Methods

### NewAPIKeyScopeInfo

`func NewAPIKeyScopeInfo(apiKeyId int32, createdAt string, id int32, permission string, permissionId int32, serverId NullableInt32, stackPattern string, updatedAt string, ) *APIKeyScopeInfo`

NewAPIKeyScopeInfo instantiates a new APIKeyScopeInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAPIKeyScopeInfoWithDefaults

`func NewAPIKeyScopeInfoWithDefaults() *APIKeyScopeInfo`

NewAPIKeyScopeInfoWithDefaults instantiates a new APIKeyScopeInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApiKeyId

`func (o *APIKeyScopeInfo) GetApiKeyId() int32`

GetApiKeyId returns the ApiKeyId field if non-nil, zero value otherwise.

### GetApiKeyIdOk

`func (o *APIKeyScopeInfo) GetApiKeyIdOk() (*int32, bool)`

GetApiKeyIdOk returns a tuple with the ApiKeyId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApiKeyId

`func (o *APIKeyScopeInfo) SetApiKeyId(v int32)`

SetApiKeyId sets ApiKeyId field to given value.


### GetCreatedAt

`func (o *APIKeyScopeInfo) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *APIKeyScopeInfo) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *APIKeyScopeInfo) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetId

`func (o *APIKeyScopeInfo) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *APIKeyScopeInfo) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *APIKeyScopeInfo) SetId(v int32)`

SetId sets Id field to given value.


### GetPermission

`func (o *APIKeyScopeInfo) GetPermission() string`

GetPermission returns the Permission field if non-nil, zero value otherwise.

### GetPermissionOk

`func (o *APIKeyScopeInfo) GetPermissionOk() (*string, bool)`

GetPermissionOk returns a tuple with the Permission field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermission

`func (o *APIKeyScopeInfo) SetPermission(v string)`

SetPermission sets Permission field to given value.


### GetPermissionId

`func (o *APIKeyScopeInfo) GetPermissionId() int32`

GetPermissionId returns the PermissionId field if non-nil, zero value otherwise.

### GetPermissionIdOk

`func (o *APIKeyScopeInfo) GetPermissionIdOk() (*int32, bool)`

GetPermissionIdOk returns a tuple with the PermissionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissionId

`func (o *APIKeyScopeInfo) SetPermissionId(v int32)`

SetPermissionId sets PermissionId field to given value.


### GetServerId

`func (o *APIKeyScopeInfo) GetServerId() int32`

GetServerId returns the ServerId field if non-nil, zero value otherwise.

### GetServerIdOk

`func (o *APIKeyScopeInfo) GetServerIdOk() (*int32, bool)`

GetServerIdOk returns a tuple with the ServerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerId

`func (o *APIKeyScopeInfo) SetServerId(v int32)`

SetServerId sets ServerId field to given value.


### SetServerIdNil

`func (o *APIKeyScopeInfo) SetServerIdNil(b bool)`

 SetServerIdNil sets the value for ServerId to be an explicit nil

### UnsetServerId
`func (o *APIKeyScopeInfo) UnsetServerId()`

UnsetServerId ensures that no value is present for ServerId, not even an explicit nil
### GetServerName

`func (o *APIKeyScopeInfo) GetServerName() string`

GetServerName returns the ServerName field if non-nil, zero value otherwise.

### GetServerNameOk

`func (o *APIKeyScopeInfo) GetServerNameOk() (*string, bool)`

GetServerNameOk returns a tuple with the ServerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerName

`func (o *APIKeyScopeInfo) SetServerName(v string)`

SetServerName sets ServerName field to given value.

### HasServerName

`func (o *APIKeyScopeInfo) HasServerName() bool`

HasServerName returns a boolean if a field has been set.

### GetStackPattern

`func (o *APIKeyScopeInfo) GetStackPattern() string`

GetStackPattern returns the StackPattern field if non-nil, zero value otherwise.

### GetStackPatternOk

`func (o *APIKeyScopeInfo) GetStackPatternOk() (*string, bool)`

GetStackPatternOk returns a tuple with the StackPattern field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStackPattern

`func (o *APIKeyScopeInfo) SetStackPattern(v string)`

SetStackPattern sets StackPattern field to given value.


### GetUpdatedAt

`func (o *APIKeyScopeInfo) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *APIKeyScopeInfo) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *APIKeyScopeInfo) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


