# RawComposeConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ComposeFile** | **string** |  | 
**Configs** | Pointer to **map[string]map[string]interface{}** |  | [optional] 
**Networks** | Pointer to **map[string]map[string]interface{}** |  | [optional] 
**Secrets** | Pointer to **map[string]map[string]interface{}** |  | [optional] 
**Services** | **map[string]map[string]interface{}** |  | 
**Volumes** | Pointer to **map[string]map[string]interface{}** |  | [optional] 

## Methods

### NewRawComposeConfig

`func NewRawComposeConfig(composeFile string, services map[string]map[string]interface{}, ) *RawComposeConfig`

NewRawComposeConfig instantiates a new RawComposeConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRawComposeConfigWithDefaults

`func NewRawComposeConfigWithDefaults() *RawComposeConfig`

NewRawComposeConfigWithDefaults instantiates a new RawComposeConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetComposeFile

`func (o *RawComposeConfig) GetComposeFile() string`

GetComposeFile returns the ComposeFile field if non-nil, zero value otherwise.

### GetComposeFileOk

`func (o *RawComposeConfig) GetComposeFileOk() (*string, bool)`

GetComposeFileOk returns a tuple with the ComposeFile field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComposeFile

`func (o *RawComposeConfig) SetComposeFile(v string)`

SetComposeFile sets ComposeFile field to given value.


### GetConfigs

`func (o *RawComposeConfig) GetConfigs() map[string]map[string]interface{}`

GetConfigs returns the Configs field if non-nil, zero value otherwise.

### GetConfigsOk

`func (o *RawComposeConfig) GetConfigsOk() (*map[string]map[string]interface{}, bool)`

GetConfigsOk returns a tuple with the Configs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfigs

`func (o *RawComposeConfig) SetConfigs(v map[string]map[string]interface{})`

SetConfigs sets Configs field to given value.

### HasConfigs

`func (o *RawComposeConfig) HasConfigs() bool`

HasConfigs returns a boolean if a field has been set.

### GetNetworks

`func (o *RawComposeConfig) GetNetworks() map[string]map[string]interface{}`

GetNetworks returns the Networks field if non-nil, zero value otherwise.

### GetNetworksOk

`func (o *RawComposeConfig) GetNetworksOk() (*map[string]map[string]interface{}, bool)`

GetNetworksOk returns a tuple with the Networks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworks

`func (o *RawComposeConfig) SetNetworks(v map[string]map[string]interface{})`

SetNetworks sets Networks field to given value.

### HasNetworks

`func (o *RawComposeConfig) HasNetworks() bool`

HasNetworks returns a boolean if a field has been set.

### GetSecrets

`func (o *RawComposeConfig) GetSecrets() map[string]map[string]interface{}`

GetSecrets returns the Secrets field if non-nil, zero value otherwise.

### GetSecretsOk

`func (o *RawComposeConfig) GetSecretsOk() (*map[string]map[string]interface{}, bool)`

GetSecretsOk returns a tuple with the Secrets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecrets

`func (o *RawComposeConfig) SetSecrets(v map[string]map[string]interface{})`

SetSecrets sets Secrets field to given value.

### HasSecrets

`func (o *RawComposeConfig) HasSecrets() bool`

HasSecrets returns a boolean if a field has been set.

### GetServices

`func (o *RawComposeConfig) GetServices() map[string]map[string]interface{}`

GetServices returns the Services field if non-nil, zero value otherwise.

### GetServicesOk

`func (o *RawComposeConfig) GetServicesOk() (*map[string]map[string]interface{}, bool)`

GetServicesOk returns a tuple with the Services field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServices

`func (o *RawComposeConfig) SetServices(v map[string]map[string]interface{})`

SetServices sets Services field to given value.


### GetVolumes

`func (o *RawComposeConfig) GetVolumes() map[string]map[string]interface{}`

GetVolumes returns the Volumes field if non-nil, zero value otherwise.

### GetVolumesOk

`func (o *RawComposeConfig) GetVolumesOk() (*map[string]map[string]interface{}, bool)`

GetVolumesOk returns a tuple with the Volumes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVolumes

`func (o *RawComposeConfig) SetVolumes(v map[string]map[string]interface{})`

SetVolumes sets Volumes field to given value.

### HasVolumes

`func (o *RawComposeConfig) HasVolumes() bool`

HasVolumes returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


