# NewServiceConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Environment** | Pointer to **map[string]string** |  | [optional] 
**Image** | **string** |  | 
**Ports** | Pointer to [**[]PortMapping**](PortMapping.md) |  | [optional] 
**Restart** | Pointer to **string** |  | [optional] 
**Volumes** | Pointer to [**[]VolumeMount2**](VolumeMount2.md) |  | [optional] 

## Methods

### NewNewServiceConfig

`func NewNewServiceConfig(image string, ) *NewServiceConfig`

NewNewServiceConfig instantiates a new NewServiceConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewNewServiceConfigWithDefaults

`func NewNewServiceConfigWithDefaults() *NewServiceConfig`

NewNewServiceConfigWithDefaults instantiates a new NewServiceConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnvironment

`func (o *NewServiceConfig) GetEnvironment() map[string]string`

GetEnvironment returns the Environment field if non-nil, zero value otherwise.

### GetEnvironmentOk

`func (o *NewServiceConfig) GetEnvironmentOk() (*map[string]string, bool)`

GetEnvironmentOk returns a tuple with the Environment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnvironment

`func (o *NewServiceConfig) SetEnvironment(v map[string]string)`

SetEnvironment sets Environment field to given value.

### HasEnvironment

`func (o *NewServiceConfig) HasEnvironment() bool`

HasEnvironment returns a boolean if a field has been set.

### GetImage

`func (o *NewServiceConfig) GetImage() string`

GetImage returns the Image field if non-nil, zero value otherwise.

### GetImageOk

`func (o *NewServiceConfig) GetImageOk() (*string, bool)`

GetImageOk returns a tuple with the Image field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImage

`func (o *NewServiceConfig) SetImage(v string)`

SetImage sets Image field to given value.


### GetPorts

`func (o *NewServiceConfig) GetPorts() []PortMapping`

GetPorts returns the Ports field if non-nil, zero value otherwise.

### GetPortsOk

`func (o *NewServiceConfig) GetPortsOk() (*[]PortMapping, bool)`

GetPortsOk returns a tuple with the Ports field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPorts

`func (o *NewServiceConfig) SetPorts(v []PortMapping)`

SetPorts sets Ports field to given value.

### HasPorts

`func (o *NewServiceConfig) HasPorts() bool`

HasPorts returns a boolean if a field has been set.

### GetRestart

`func (o *NewServiceConfig) GetRestart() string`

GetRestart returns the Restart field if non-nil, zero value otherwise.

### GetRestartOk

`func (o *NewServiceConfig) GetRestartOk() (*string, bool)`

GetRestartOk returns a tuple with the Restart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRestart

`func (o *NewServiceConfig) SetRestart(v string)`

SetRestart sets Restart field to given value.

### HasRestart

`func (o *NewServiceConfig) HasRestart() bool`

HasRestart returns a boolean if a field has been set.

### GetVolumes

`func (o *NewServiceConfig) GetVolumes() []VolumeMount2`

GetVolumes returns the Volumes field if non-nil, zero value otherwise.

### GetVolumesOk

`func (o *NewServiceConfig) GetVolumesOk() (*[]VolumeMount2, bool)`

GetVolumesOk returns a tuple with the Volumes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVolumes

`func (o *NewServiceConfig) SetVolumes(v []VolumeMount2)`

SetVolumes sets Volumes field to given value.

### HasVolumes

`func (o *NewServiceConfig) HasVolumes() bool`

HasVolumes returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


