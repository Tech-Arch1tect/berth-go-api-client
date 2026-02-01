# VolumeConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Driver** | Pointer to **string** |  | [optional] 
**DriverOpts** | Pointer to **map[string]string** |  | [optional] 
**External** | Pointer to **bool** |  | [optional] 
**Labels** | Pointer to **map[string]string** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 

## Methods

### NewVolumeConfig

`func NewVolumeConfig() *VolumeConfig`

NewVolumeConfig instantiates a new VolumeConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVolumeConfigWithDefaults

`func NewVolumeConfigWithDefaults() *VolumeConfig`

NewVolumeConfigWithDefaults instantiates a new VolumeConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDriver

`func (o *VolumeConfig) GetDriver() string`

GetDriver returns the Driver field if non-nil, zero value otherwise.

### GetDriverOk

`func (o *VolumeConfig) GetDriverOk() (*string, bool)`

GetDriverOk returns a tuple with the Driver field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDriver

`func (o *VolumeConfig) SetDriver(v string)`

SetDriver sets Driver field to given value.

### HasDriver

`func (o *VolumeConfig) HasDriver() bool`

HasDriver returns a boolean if a field has been set.

### GetDriverOpts

`func (o *VolumeConfig) GetDriverOpts() map[string]string`

GetDriverOpts returns the DriverOpts field if non-nil, zero value otherwise.

### GetDriverOptsOk

`func (o *VolumeConfig) GetDriverOptsOk() (*map[string]string, bool)`

GetDriverOptsOk returns a tuple with the DriverOpts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDriverOpts

`func (o *VolumeConfig) SetDriverOpts(v map[string]string)`

SetDriverOpts sets DriverOpts field to given value.

### HasDriverOpts

`func (o *VolumeConfig) HasDriverOpts() bool`

HasDriverOpts returns a boolean if a field has been set.

### GetExternal

`func (o *VolumeConfig) GetExternal() bool`

GetExternal returns the External field if non-nil, zero value otherwise.

### GetExternalOk

`func (o *VolumeConfig) GetExternalOk() (*bool, bool)`

GetExternalOk returns a tuple with the External field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternal

`func (o *VolumeConfig) SetExternal(v bool)`

SetExternal sets External field to given value.

### HasExternal

`func (o *VolumeConfig) HasExternal() bool`

HasExternal returns a boolean if a field has been set.

### GetLabels

`func (o *VolumeConfig) GetLabels() map[string]string`

GetLabels returns the Labels field if non-nil, zero value otherwise.

### GetLabelsOk

`func (o *VolumeConfig) GetLabelsOk() (*map[string]string, bool)`

GetLabelsOk returns a tuple with the Labels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabels

`func (o *VolumeConfig) SetLabels(v map[string]string)`

SetLabels sets Labels field to given value.

### HasLabels

`func (o *VolumeConfig) HasLabels() bool`

HasLabels returns a boolean if a field has been set.

### GetName

`func (o *VolumeConfig) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *VolumeConfig) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *VolumeConfig) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *VolumeConfig) HasName() bool`

HasName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


