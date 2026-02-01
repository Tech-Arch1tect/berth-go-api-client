# ImageInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Created** | **time.Time** |  | 
**Dangling** | **bool** |  | 
**Id** | **string** |  | 
**Repository** | **string** |  | 
**Size** | **int32** |  | 
**Tag** | **string** |  | 
**Unused** | **bool** |  | 

## Methods

### NewImageInfo

`func NewImageInfo(created time.Time, dangling bool, id string, repository string, size int32, tag string, unused bool, ) *ImageInfo`

NewImageInfo instantiates a new ImageInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImageInfoWithDefaults

`func NewImageInfoWithDefaults() *ImageInfo`

NewImageInfoWithDefaults instantiates a new ImageInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

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


### GetRepository

`func (o *ImageInfo) GetRepository() string`

GetRepository returns the Repository field if non-nil, zero value otherwise.

### GetRepositoryOk

`func (o *ImageInfo) GetRepositoryOk() (*string, bool)`

GetRepositoryOk returns a tuple with the Repository field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepository

`func (o *ImageInfo) SetRepository(v string)`

SetRepository sets Repository field to given value.


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


### GetTag

`func (o *ImageInfo) GetTag() string`

GetTag returns the Tag field if non-nil, zero value otherwise.

### GetTagOk

`func (o *ImageInfo) GetTagOk() (*string, bool)`

GetTagOk returns a tuple with the Tag field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTag

`func (o *ImageInfo) SetTag(v string)`

SetTag sets Tag field to given value.


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


