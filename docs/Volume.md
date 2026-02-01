# Volume

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Created** | Pointer to **string** |  | [optional] 
**Driver** | Pointer to **string** |  | [optional] 
**DriverOpts** | Pointer to **map[string]string** |  | [optional] 
**Exists** | **bool** |  | 
**External** | Pointer to **bool** |  | [optional] 
**Labels** | Pointer to **map[string]string** |  | [optional] 
**Mountpoint** | Pointer to **string** |  | [optional] 
**Name** | **string** |  | 
**Scope** | Pointer to **string** |  | [optional] 
**UsedBy** | Pointer to [**[]VolumeUsage**](VolumeUsage.md) |  | [optional] 

## Methods

### NewVolume

`func NewVolume(exists bool, name string, ) *Volume`

NewVolume instantiates a new Volume object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVolumeWithDefaults

`func NewVolumeWithDefaults() *Volume`

NewVolumeWithDefaults instantiates a new Volume object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreated

`func (o *Volume) GetCreated() string`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *Volume) GetCreatedOk() (*string, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *Volume) SetCreated(v string)`

SetCreated sets Created field to given value.

### HasCreated

`func (o *Volume) HasCreated() bool`

HasCreated returns a boolean if a field has been set.

### GetDriver

`func (o *Volume) GetDriver() string`

GetDriver returns the Driver field if non-nil, zero value otherwise.

### GetDriverOk

`func (o *Volume) GetDriverOk() (*string, bool)`

GetDriverOk returns a tuple with the Driver field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDriver

`func (o *Volume) SetDriver(v string)`

SetDriver sets Driver field to given value.

### HasDriver

`func (o *Volume) HasDriver() bool`

HasDriver returns a boolean if a field has been set.

### GetDriverOpts

`func (o *Volume) GetDriverOpts() map[string]string`

GetDriverOpts returns the DriverOpts field if non-nil, zero value otherwise.

### GetDriverOptsOk

`func (o *Volume) GetDriverOptsOk() (*map[string]string, bool)`

GetDriverOptsOk returns a tuple with the DriverOpts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDriverOpts

`func (o *Volume) SetDriverOpts(v map[string]string)`

SetDriverOpts sets DriverOpts field to given value.

### HasDriverOpts

`func (o *Volume) HasDriverOpts() bool`

HasDriverOpts returns a boolean if a field has been set.

### GetExists

`func (o *Volume) GetExists() bool`

GetExists returns the Exists field if non-nil, zero value otherwise.

### GetExistsOk

`func (o *Volume) GetExistsOk() (*bool, bool)`

GetExistsOk returns a tuple with the Exists field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExists

`func (o *Volume) SetExists(v bool)`

SetExists sets Exists field to given value.


### GetExternal

`func (o *Volume) GetExternal() bool`

GetExternal returns the External field if non-nil, zero value otherwise.

### GetExternalOk

`func (o *Volume) GetExternalOk() (*bool, bool)`

GetExternalOk returns a tuple with the External field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternal

`func (o *Volume) SetExternal(v bool)`

SetExternal sets External field to given value.

### HasExternal

`func (o *Volume) HasExternal() bool`

HasExternal returns a boolean if a field has been set.

### GetLabels

`func (o *Volume) GetLabels() map[string]string`

GetLabels returns the Labels field if non-nil, zero value otherwise.

### GetLabelsOk

`func (o *Volume) GetLabelsOk() (*map[string]string, bool)`

GetLabelsOk returns a tuple with the Labels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabels

`func (o *Volume) SetLabels(v map[string]string)`

SetLabels sets Labels field to given value.

### HasLabels

`func (o *Volume) HasLabels() bool`

HasLabels returns a boolean if a field has been set.

### GetMountpoint

`func (o *Volume) GetMountpoint() string`

GetMountpoint returns the Mountpoint field if non-nil, zero value otherwise.

### GetMountpointOk

`func (o *Volume) GetMountpointOk() (*string, bool)`

GetMountpointOk returns a tuple with the Mountpoint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMountpoint

`func (o *Volume) SetMountpoint(v string)`

SetMountpoint sets Mountpoint field to given value.

### HasMountpoint

`func (o *Volume) HasMountpoint() bool`

HasMountpoint returns a boolean if a field has been set.

### GetName

`func (o *Volume) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Volume) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Volume) SetName(v string)`

SetName sets Name field to given value.


### GetScope

`func (o *Volume) GetScope() string`

GetScope returns the Scope field if non-nil, zero value otherwise.

### GetScopeOk

`func (o *Volume) GetScopeOk() (*string, bool)`

GetScopeOk returns a tuple with the Scope field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScope

`func (o *Volume) SetScope(v string)`

SetScope sets Scope field to given value.

### HasScope

`func (o *Volume) HasScope() bool`

HasScope returns a boolean if a field has been set.

### GetUsedBy

`func (o *Volume) GetUsedBy() []VolumeUsage`

GetUsedBy returns the UsedBy field if non-nil, zero value otherwise.

### GetUsedByOk

`func (o *Volume) GetUsedByOk() (*[]VolumeUsage, bool)`

GetUsedByOk returns a tuple with the UsedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsedBy

`func (o *Volume) SetUsedBy(v []VolumeUsage)`

SetUsedBy sets UsedBy field to given value.

### HasUsedBy

`func (o *Volume) HasUsedBy() bool`

HasUsedBy returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


