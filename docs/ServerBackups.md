# ServerBackups

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Configured** | **bool** |  | 
**Enabled** | **bool** |  | 
**Error** | Pointer to **string** |  | [optional] 
**ServerId** | **int32** |  | 
**ServerName** | **string** |  | 
**Stacks** | [**[]StackBackupSummary**](StackBackupSummary.md) |  | 

## Methods

### NewServerBackups

`func NewServerBackups(configured bool, enabled bool, serverId int32, serverName string, stacks []StackBackupSummary, ) *ServerBackups`

NewServerBackups instantiates a new ServerBackups object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewServerBackupsWithDefaults

`func NewServerBackupsWithDefaults() *ServerBackups`

NewServerBackupsWithDefaults instantiates a new ServerBackups object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConfigured

`func (o *ServerBackups) GetConfigured() bool`

GetConfigured returns the Configured field if non-nil, zero value otherwise.

### GetConfiguredOk

`func (o *ServerBackups) GetConfiguredOk() (*bool, bool)`

GetConfiguredOk returns a tuple with the Configured field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfigured

`func (o *ServerBackups) SetConfigured(v bool)`

SetConfigured sets Configured field to given value.


### GetEnabled

`func (o *ServerBackups) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *ServerBackups) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *ServerBackups) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetError

`func (o *ServerBackups) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ServerBackups) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ServerBackups) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *ServerBackups) HasError() bool`

HasError returns a boolean if a field has been set.

### GetServerId

`func (o *ServerBackups) GetServerId() int32`

GetServerId returns the ServerId field if non-nil, zero value otherwise.

### GetServerIdOk

`func (o *ServerBackups) GetServerIdOk() (*int32, bool)`

GetServerIdOk returns a tuple with the ServerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerId

`func (o *ServerBackups) SetServerId(v int32)`

SetServerId sets ServerId field to given value.


### GetServerName

`func (o *ServerBackups) GetServerName() string`

GetServerName returns the ServerName field if non-nil, zero value otherwise.

### GetServerNameOk

`func (o *ServerBackups) GetServerNameOk() (*string, bool)`

GetServerNameOk returns a tuple with the ServerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerName

`func (o *ServerBackups) SetServerName(v string)`

SetServerName sets ServerName field to given value.


### GetStacks

`func (o *ServerBackups) GetStacks() []StackBackupSummary`

GetStacks returns the Stacks field if non-nil, zero value otherwise.

### GetStacksOk

`func (o *ServerBackups) GetStacksOk() (*[]StackBackupSummary, bool)`

GetStacksOk returns a tuple with the Stacks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStacks

`func (o *ServerBackups) SetStacks(v []StackBackupSummary)`

SetStacks sets Stacks field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


