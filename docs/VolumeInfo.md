# VolumeInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Created** | **time.Time** |  | 
**Driver** | **string** |  | 
**Labels** | **map[string]string** |  | 
**Mountpoint** | **string** |  | 
**Name** | **string** |  | 
**Size** | **int32** |  | 
**Unused** | **bool** |  | 

## Methods

### NewVolumeInfo

`func NewVolumeInfo(created time.Time, driver string, labels map[string]string, mountpoint string, name string, size int32, unused bool, ) *VolumeInfo`

NewVolumeInfo instantiates a new VolumeInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVolumeInfoWithDefaults

`func NewVolumeInfoWithDefaults() *VolumeInfo`

NewVolumeInfoWithDefaults instantiates a new VolumeInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreated

`func (o *VolumeInfo) GetCreated() time.Time`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *VolumeInfo) GetCreatedOk() (*time.Time, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *VolumeInfo) SetCreated(v time.Time)`

SetCreated sets Created field to given value.


### GetDriver

`func (o *VolumeInfo) GetDriver() string`

GetDriver returns the Driver field if non-nil, zero value otherwise.

### GetDriverOk

`func (o *VolumeInfo) GetDriverOk() (*string, bool)`

GetDriverOk returns a tuple with the Driver field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDriver

`func (o *VolumeInfo) SetDriver(v string)`

SetDriver sets Driver field to given value.


### GetLabels

`func (o *VolumeInfo) GetLabels() map[string]string`

GetLabels returns the Labels field if non-nil, zero value otherwise.

### GetLabelsOk

`func (o *VolumeInfo) GetLabelsOk() (*map[string]string, bool)`

GetLabelsOk returns a tuple with the Labels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabels

`func (o *VolumeInfo) SetLabels(v map[string]string)`

SetLabels sets Labels field to given value.


### GetMountpoint

`func (o *VolumeInfo) GetMountpoint() string`

GetMountpoint returns the Mountpoint field if non-nil, zero value otherwise.

### GetMountpointOk

`func (o *VolumeInfo) GetMountpointOk() (*string, bool)`

GetMountpointOk returns a tuple with the Mountpoint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMountpoint

`func (o *VolumeInfo) SetMountpoint(v string)`

SetMountpoint sets Mountpoint field to given value.


### GetName

`func (o *VolumeInfo) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *VolumeInfo) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *VolumeInfo) SetName(v string)`

SetName sets Name field to given value.


### GetSize

`func (o *VolumeInfo) GetSize() int32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *VolumeInfo) GetSizeOk() (*int32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *VolumeInfo) SetSize(v int32)`

SetSize sets Size field to given value.


### GetUnused

`func (o *VolumeInfo) GetUnused() bool`

GetUnused returns the Unused field if non-nil, zero value otherwise.

### GetUnusedOk

`func (o *VolumeInfo) GetUnusedOk() (*bool, bool)`

GetUnusedOk returns a tuple with the Unused field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnused

`func (o *VolumeInfo) SetUnused(v bool)`

SetUnused sets Unused field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


