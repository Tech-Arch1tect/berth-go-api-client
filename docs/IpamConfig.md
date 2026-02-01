# IpamConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Config** | Pointer to [**[]IpamPool**](IpamPool.md) |  | [optional] 
**Driver** | Pointer to **string** |  | [optional] 

## Methods

### NewIpamConfig

`func NewIpamConfig() *IpamConfig`

NewIpamConfig instantiates a new IpamConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIpamConfigWithDefaults

`func NewIpamConfigWithDefaults() *IpamConfig`

NewIpamConfigWithDefaults instantiates a new IpamConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConfig

`func (o *IpamConfig) GetConfig() []IpamPool`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *IpamConfig) GetConfigOk() (*[]IpamPool, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *IpamConfig) SetConfig(v []IpamPool)`

SetConfig sets Config field to given value.

### HasConfig

`func (o *IpamConfig) HasConfig() bool`

HasConfig returns a boolean if a field has been set.

### GetDriver

`func (o *IpamConfig) GetDriver() string`

GetDriver returns the Driver field if non-nil, zero value otherwise.

### GetDriverOk

`func (o *IpamConfig) GetDriverOk() (*string, bool)`

GetDriverOk returns a tuple with the Driver field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDriver

`func (o *IpamConfig) SetDriver(v string)`

SetDriver sets Driver field to given value.

### HasDriver

`func (o *IpamConfig) HasDriver() bool`

HasDriver returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


