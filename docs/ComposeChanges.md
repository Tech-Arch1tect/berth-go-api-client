# ComposeChanges

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AddServices** | Pointer to [**map[string]NewServiceConfig**](NewServiceConfig.md) |  | [optional] 
**ConfigChanges** | Pointer to [**map[string]ConfigConfig**](ConfigConfig.md) |  | [optional] 
**DeleteServices** | Pointer to **[]string** |  | [optional] 
**NetworkChanges** | Pointer to [**map[string]NetworkConfig**](NetworkConfig.md) |  | [optional] 
**RenameServices** | Pointer to **map[string]string** |  | [optional] 
**SecretChanges** | Pointer to [**map[string]SecretConfig**](SecretConfig.md) |  | [optional] 
**ServiceChanges** | Pointer to [**map[string]ServiceChanges**](ServiceChanges.md) |  | [optional] 
**VolumeChanges** | Pointer to [**map[string]VolumeConfig**](VolumeConfig.md) |  | [optional] 

## Methods

### NewComposeChanges

`func NewComposeChanges() *ComposeChanges`

NewComposeChanges instantiates a new ComposeChanges object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewComposeChangesWithDefaults

`func NewComposeChangesWithDefaults() *ComposeChanges`

NewComposeChangesWithDefaults instantiates a new ComposeChanges object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddServices

`func (o *ComposeChanges) GetAddServices() map[string]NewServiceConfig`

GetAddServices returns the AddServices field if non-nil, zero value otherwise.

### GetAddServicesOk

`func (o *ComposeChanges) GetAddServicesOk() (*map[string]NewServiceConfig, bool)`

GetAddServicesOk returns a tuple with the AddServices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddServices

`func (o *ComposeChanges) SetAddServices(v map[string]NewServiceConfig)`

SetAddServices sets AddServices field to given value.

### HasAddServices

`func (o *ComposeChanges) HasAddServices() bool`

HasAddServices returns a boolean if a field has been set.

### GetConfigChanges

`func (o *ComposeChanges) GetConfigChanges() map[string]ConfigConfig`

GetConfigChanges returns the ConfigChanges field if non-nil, zero value otherwise.

### GetConfigChangesOk

`func (o *ComposeChanges) GetConfigChangesOk() (*map[string]ConfigConfig, bool)`

GetConfigChangesOk returns a tuple with the ConfigChanges field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfigChanges

`func (o *ComposeChanges) SetConfigChanges(v map[string]ConfigConfig)`

SetConfigChanges sets ConfigChanges field to given value.

### HasConfigChanges

`func (o *ComposeChanges) HasConfigChanges() bool`

HasConfigChanges returns a boolean if a field has been set.

### GetDeleteServices

`func (o *ComposeChanges) GetDeleteServices() []string`

GetDeleteServices returns the DeleteServices field if non-nil, zero value otherwise.

### GetDeleteServicesOk

`func (o *ComposeChanges) GetDeleteServicesOk() (*[]string, bool)`

GetDeleteServicesOk returns a tuple with the DeleteServices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeleteServices

`func (o *ComposeChanges) SetDeleteServices(v []string)`

SetDeleteServices sets DeleteServices field to given value.

### HasDeleteServices

`func (o *ComposeChanges) HasDeleteServices() bool`

HasDeleteServices returns a boolean if a field has been set.

### GetNetworkChanges

`func (o *ComposeChanges) GetNetworkChanges() map[string]NetworkConfig`

GetNetworkChanges returns the NetworkChanges field if non-nil, zero value otherwise.

### GetNetworkChangesOk

`func (o *ComposeChanges) GetNetworkChangesOk() (*map[string]NetworkConfig, bool)`

GetNetworkChangesOk returns a tuple with the NetworkChanges field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworkChanges

`func (o *ComposeChanges) SetNetworkChanges(v map[string]NetworkConfig)`

SetNetworkChanges sets NetworkChanges field to given value.

### HasNetworkChanges

`func (o *ComposeChanges) HasNetworkChanges() bool`

HasNetworkChanges returns a boolean if a field has been set.

### GetRenameServices

`func (o *ComposeChanges) GetRenameServices() map[string]string`

GetRenameServices returns the RenameServices field if non-nil, zero value otherwise.

### GetRenameServicesOk

`func (o *ComposeChanges) GetRenameServicesOk() (*map[string]string, bool)`

GetRenameServicesOk returns a tuple with the RenameServices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRenameServices

`func (o *ComposeChanges) SetRenameServices(v map[string]string)`

SetRenameServices sets RenameServices field to given value.

### HasRenameServices

`func (o *ComposeChanges) HasRenameServices() bool`

HasRenameServices returns a boolean if a field has been set.

### GetSecretChanges

`func (o *ComposeChanges) GetSecretChanges() map[string]SecretConfig`

GetSecretChanges returns the SecretChanges field if non-nil, zero value otherwise.

### GetSecretChangesOk

`func (o *ComposeChanges) GetSecretChangesOk() (*map[string]SecretConfig, bool)`

GetSecretChangesOk returns a tuple with the SecretChanges field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecretChanges

`func (o *ComposeChanges) SetSecretChanges(v map[string]SecretConfig)`

SetSecretChanges sets SecretChanges field to given value.

### HasSecretChanges

`func (o *ComposeChanges) HasSecretChanges() bool`

HasSecretChanges returns a boolean if a field has been set.

### GetServiceChanges

`func (o *ComposeChanges) GetServiceChanges() map[string]ServiceChanges`

GetServiceChanges returns the ServiceChanges field if non-nil, zero value otherwise.

### GetServiceChangesOk

`func (o *ComposeChanges) GetServiceChangesOk() (*map[string]ServiceChanges, bool)`

GetServiceChangesOk returns a tuple with the ServiceChanges field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceChanges

`func (o *ComposeChanges) SetServiceChanges(v map[string]ServiceChanges)`

SetServiceChanges sets ServiceChanges field to given value.

### HasServiceChanges

`func (o *ComposeChanges) HasServiceChanges() bool`

HasServiceChanges returns a boolean if a field has been set.

### GetVolumeChanges

`func (o *ComposeChanges) GetVolumeChanges() map[string]VolumeConfig`

GetVolumeChanges returns the VolumeChanges field if non-nil, zero value otherwise.

### GetVolumeChangesOk

`func (o *ComposeChanges) GetVolumeChangesOk() (*map[string]VolumeConfig, bool)`

GetVolumeChangesOk returns a tuple with the VolumeChanges field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVolumeChanges

`func (o *ComposeChanges) SetVolumeChanges(v map[string]VolumeConfig)`

SetVolumeChanges sets VolumeChanges field to given value.

### HasVolumeChanges

`func (o *ComposeChanges) HasVolumeChanges() bool`

HasVolumeChanges returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


