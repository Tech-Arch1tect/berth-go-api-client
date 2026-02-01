# ImageHistoryLayer

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Comment** | Pointer to **string** |  | [optional] 
**Created** | **int32** |  | 
**CreatedBy** | **string** |  | 
**Id** | **string** |  | 
**Size** | **int32** |  | 
**Tags** | Pointer to **[]string** |  | [optional] 

## Methods

### NewImageHistoryLayer

`func NewImageHistoryLayer(created int32, createdBy string, id string, size int32, ) *ImageHistoryLayer`

NewImageHistoryLayer instantiates a new ImageHistoryLayer object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImageHistoryLayerWithDefaults

`func NewImageHistoryLayerWithDefaults() *ImageHistoryLayer`

NewImageHistoryLayerWithDefaults instantiates a new ImageHistoryLayer object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetComment

`func (o *ImageHistoryLayer) GetComment() string`

GetComment returns the Comment field if non-nil, zero value otherwise.

### GetCommentOk

`func (o *ImageHistoryLayer) GetCommentOk() (*string, bool)`

GetCommentOk returns a tuple with the Comment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComment

`func (o *ImageHistoryLayer) SetComment(v string)`

SetComment sets Comment field to given value.

### HasComment

`func (o *ImageHistoryLayer) HasComment() bool`

HasComment returns a boolean if a field has been set.

### GetCreated

`func (o *ImageHistoryLayer) GetCreated() int32`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *ImageHistoryLayer) GetCreatedOk() (*int32, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *ImageHistoryLayer) SetCreated(v int32)`

SetCreated sets Created field to given value.


### GetCreatedBy

`func (o *ImageHistoryLayer) GetCreatedBy() string`

GetCreatedBy returns the CreatedBy field if non-nil, zero value otherwise.

### GetCreatedByOk

`func (o *ImageHistoryLayer) GetCreatedByOk() (*string, bool)`

GetCreatedByOk returns a tuple with the CreatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBy

`func (o *ImageHistoryLayer) SetCreatedBy(v string)`

SetCreatedBy sets CreatedBy field to given value.


### GetId

`func (o *ImageHistoryLayer) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ImageHistoryLayer) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ImageHistoryLayer) SetId(v string)`

SetId sets Id field to given value.


### GetSize

`func (o *ImageHistoryLayer) GetSize() int32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *ImageHistoryLayer) GetSizeOk() (*int32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *ImageHistoryLayer) SetSize(v int32)`

SetSize sets Size field to given value.


### GetTags

`func (o *ImageHistoryLayer) GetTags() []string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *ImageHistoryLayer) GetTagsOk() (*[]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *ImageHistoryLayer) SetTags(v []string)`

SetTags sets Tags field to given value.

### HasTags

`func (o *ImageHistoryLayer) HasTags() bool`

HasTags returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


