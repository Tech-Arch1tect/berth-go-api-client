# ImageInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Containers** | **int32** |  | 
**Created** | **time.Time** |  | 
**Dangling** | **bool** |  | 
**Id** | **string** |  | 
**Removal** | **string** |  | 
**SharedSize** | **int32** |  | 
**Size** | **int32** |  | 
**Tags** | **[]string** |  | 
**Unused** | **bool** |  | 

## Methods

### NewImageInfo

`func NewImageInfo(containers int32, created time.Time, dangling bool, id string, removal string, sharedSize int32, size int32, tags []string, unused bool, ) *ImageInfo`

NewImageInfo instantiates a new ImageInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImageInfoWithDefaults

`func NewImageInfoWithDefaults() *ImageInfo`

NewImageInfoWithDefaults instantiates a new ImageInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContainers

`func (o *ImageInfo) GetContainers() int32`

GetContainers returns the Containers field if non-nil, zero value otherwise.

### GetContainersOk

`func (o *ImageInfo) GetContainersOk() (*int32, bool)`

GetContainersOk returns a tuple with the Containers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainers

`func (o *ImageInfo) SetContainers(v int32)`

SetContainers sets Containers field to given value.


### GetCreated

`func (o *ImageInfo) GetCreated() time.Time`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *ImageInfo) GetCreatedOk() (*time.Time, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *ImageInfo) SetCreated(v time.Time)`

SetCreated sets Created field to given value.


### GetDangling

`func (o *ImageInfo) GetDangling() bool`

GetDangling returns the Dangling field if non-nil, zero value otherwise.

### GetDanglingOk

`func (o *ImageInfo) GetDanglingOk() (*bool, bool)`

GetDanglingOk returns a tuple with the Dangling field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDangling

`func (o *ImageInfo) SetDangling(v bool)`

SetDangling sets Dangling field to given value.


### GetId

`func (o *ImageInfo) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ImageInfo) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ImageInfo) SetId(v string)`

SetId sets Id field to given value.


### GetRemoval

`func (o *ImageInfo) GetRemoval() string`

GetRemoval returns the Removal field if non-nil, zero value otherwise.

### GetRemovalOk

`func (o *ImageInfo) GetRemovalOk() (*string, bool)`

GetRemovalOk returns a tuple with the Removal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemoval

`func (o *ImageInfo) SetRemoval(v string)`

SetRemoval sets Removal field to given value.


### GetSharedSize

`func (o *ImageInfo) GetSharedSize() int32`

GetSharedSize returns the SharedSize field if non-nil, zero value otherwise.

### GetSharedSizeOk

`func (o *ImageInfo) GetSharedSizeOk() (*int32, bool)`

GetSharedSizeOk returns a tuple with the SharedSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharedSize

`func (o *ImageInfo) SetSharedSize(v int32)`

SetSharedSize sets SharedSize field to given value.


### GetSize

`func (o *ImageInfo) GetSize() int32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *ImageInfo) GetSizeOk() (*int32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *ImageInfo) SetSize(v int32)`

SetSize sets Size field to given value.


### GetTags

`func (o *ImageInfo) GetTags() []string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *ImageInfo) GetTagsOk() (*[]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *ImageInfo) SetTags(v []string)`

SetTags sets Tags field to given value.


### GetUnused

`func (o *ImageInfo) GetUnused() bool`

GetUnused returns the Unused field if non-nil, zero value otherwise.

### GetUnusedOk

`func (o *ImageInfo) GetUnusedOk() (*bool, bool)`

GetUnusedOk returns a tuple with the Unused field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnused

`func (o *ImageInfo) SetUnused(v bool)`

SetUnused sets Unused field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


