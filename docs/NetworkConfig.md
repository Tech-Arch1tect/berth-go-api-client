# NetworkConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Driver** | Pointer to **string** |  | [optional] 
**DriverOpts** | Pointer to **map[string]string** |  | [optional] 
**External** | Pointer to **bool** |  | [optional] 
**Ipam** | Pointer to [**NullableIpamConfig**](IpamConfig.md) |  | [optional] 
**Labels** | Pointer to **map[string]string** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 

## Methods

### NewNetworkConfig

`func NewNetworkConfig() *NetworkConfig`

NewNetworkConfig instantiates a new NetworkConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewNetworkConfigWithDefaults

`func NewNetworkConfigWithDefaults() *NetworkConfig`

NewNetworkConfigWithDefaults instantiates a new NetworkConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDriver

`func (o *NetworkConfig) GetDriver() string`

GetDriver returns the Driver field if non-nil, zero value otherwise.

### GetDriverOk

`func (o *NetworkConfig) GetDriverOk() (*string, bool)`

GetDriverOk returns a tuple with the Driver field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDriver

`func (o *NetworkConfig) SetDriver(v string)`

SetDriver sets Driver field to given value.

### HasDriver

`func (o *NetworkConfig) HasDriver() bool`

HasDriver returns a boolean if a field has been set.

### GetDriverOpts

`func (o *NetworkConfig) GetDriverOpts() map[string]string`

GetDriverOpts returns the DriverOpts field if non-nil, zero value otherwise.

### GetDriverOptsOk

`func (o *NetworkConfig) GetDriverOptsOk() (*map[string]string, bool)`

GetDriverOptsOk returns a tuple with the DriverOpts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDriverOpts

`func (o *NetworkConfig) SetDriverOpts(v map[string]string)`

SetDriverOpts sets DriverOpts field to given value.

### HasDriverOpts

`func (o *NetworkConfig) HasDriverOpts() bool`

HasDriverOpts returns a boolean if a field has been set.

### GetExternal

`func (o *NetworkConfig) GetExternal() bool`

GetExternal returns the External field if non-nil, zero value otherwise.

### GetExternalOk

`func (o *NetworkConfig) GetExternalOk() (*bool, bool)`

GetExternalOk returns a tuple with the External field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternal

`func (o *NetworkConfig) SetExternal(v bool)`

SetExternal sets External field to given value.

### HasExternal

`func (o *NetworkConfig) HasExternal() bool`

HasExternal returns a boolean if a field has been set.

### GetIpam

`func (o *NetworkConfig) GetIpam() IpamConfig`

GetIpam returns the Ipam field if non-nil, zero value otherwise.

### GetIpamOk

`func (o *NetworkConfig) GetIpamOk() (*IpamConfig, bool)`

GetIpamOk returns a tuple with the Ipam field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpam

`func (o *NetworkConfig) SetIpam(v IpamConfig)`

SetIpam sets Ipam field to given value.

### HasIpam

`func (o *NetworkConfig) HasIpam() bool`

HasIpam returns a boolean if a field has been set.

### SetIpamNil

`func (o *NetworkConfig) SetIpamNil(b bool)`

 SetIpamNil sets the value for Ipam to be an explicit nil

### UnsetIpam
`func (o *NetworkConfig) UnsetIpam()`

UnsetIpam ensures that no value is present for Ipam, not even an explicit nil
### GetLabels

`func (o *NetworkConfig) GetLabels() map[string]string`

GetLabels returns the Labels field if non-nil, zero value otherwise.

### GetLabelsOk

`func (o *NetworkConfig) GetLabelsOk() (*map[string]string, bool)`

GetLabelsOk returns a tuple with the Labels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabels

`func (o *NetworkConfig) SetLabels(v map[string]string)`

SetLabels sets Labels field to given value.

### HasLabels

`func (o *NetworkConfig) HasLabels() bool`

HasLabels returns a boolean if a field has been set.

### GetName

`func (o *NetworkConfig) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *NetworkConfig) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *NetworkConfig) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *NetworkConfig) HasName() bool`

HasName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


