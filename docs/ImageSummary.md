# ImageSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DanglingCount** | **int32** |  | 
**DanglingSize** | **int32** |  | 
**Images** | [**[]ImageInfo**](ImageInfo.md) |  | 
**TotalCount** | **int32** |  | 
**TotalSize** | **int32** |  | 
**UnusedCount** | **int32** |  | 
**UnusedSize** | **int32** |  | 

## Methods

### NewImageSummary

`func NewImageSummary(danglingCount int32, danglingSize int32, images []ImageInfo, totalCount int32, totalSize int32, unusedCount int32, unusedSize int32, ) *ImageSummary`

NewImageSummary instantiates a new ImageSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImageSummaryWithDefaults

`func NewImageSummaryWithDefaults() *ImageSummary`

NewImageSummaryWithDefaults instantiates a new ImageSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDanglingCount

`func (o *ImageSummary) GetDanglingCount() int32`

GetDanglingCount returns the DanglingCount field if non-nil, zero value otherwise.

### GetDanglingCountOk

`func (o *ImageSummary) GetDanglingCountOk() (*int32, bool)`

GetDanglingCountOk returns a tuple with the DanglingCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDanglingCount

`func (o *ImageSummary) SetDanglingCount(v int32)`

SetDanglingCount sets DanglingCount field to given value.


### GetDanglingSize

`func (o *ImageSummary) GetDanglingSize() int32`

GetDanglingSize returns the DanglingSize field if non-nil, zero value otherwise.

### GetDanglingSizeOk

`func (o *ImageSummary) GetDanglingSizeOk() (*int32, bool)`

GetDanglingSizeOk returns a tuple with the DanglingSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDanglingSize

`func (o *ImageSummary) SetDanglingSize(v int32)`

SetDanglingSize sets DanglingSize field to given value.


### GetImages

`func (o *ImageSummary) GetImages() []ImageInfo`

GetImages returns the Images field if non-nil, zero value otherwise.

### GetImagesOk

`func (o *ImageSummary) GetImagesOk() (*[]ImageInfo, bool)`

GetImagesOk returns a tuple with the Images field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImages

`func (o *ImageSummary) SetImages(v []ImageInfo)`

SetImages sets Images field to given value.


### GetTotalCount

`func (o *ImageSummary) GetTotalCount() int32`

GetTotalCount returns the TotalCount field if non-nil, zero value otherwise.

### GetTotalCountOk

`func (o *ImageSummary) GetTotalCountOk() (*int32, bool)`

GetTotalCountOk returns a tuple with the TotalCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCount

`func (o *ImageSummary) SetTotalCount(v int32)`

SetTotalCount sets TotalCount field to given value.


### GetTotalSize

`func (o *ImageSummary) GetTotalSize() int32`

GetTotalSize returns the TotalSize field if non-nil, zero value otherwise.

### GetTotalSizeOk

`func (o *ImageSummary) GetTotalSizeOk() (*int32, bool)`

GetTotalSizeOk returns a tuple with the TotalSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalSize

`func (o *ImageSummary) SetTotalSize(v int32)`

SetTotalSize sets TotalSize field to given value.


### GetUnusedCount

`func (o *ImageSummary) GetUnusedCount() int32`

GetUnusedCount returns the UnusedCount field if non-nil, zero value otherwise.

### GetUnusedCountOk

`func (o *ImageSummary) GetUnusedCountOk() (*int32, bool)`

GetUnusedCountOk returns a tuple with the UnusedCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnusedCount

`func (o *ImageSummary) SetUnusedCount(v int32)`

SetUnusedCount sets UnusedCount field to given value.


### GetUnusedSize

`func (o *ImageSummary) GetUnusedSize() int32`

GetUnusedSize returns the UnusedSize field if non-nil, zero value otherwise.

### GetUnusedSizeOk

`func (o *ImageSummary) GetUnusedSizeOk() (*int32, bool)`

GetUnusedSizeOk returns a tuple with the UnusedSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnusedSize

`func (o *ImageSummary) SetUnusedSize(v int32)`

SetUnusedSize sets UnusedSize field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


