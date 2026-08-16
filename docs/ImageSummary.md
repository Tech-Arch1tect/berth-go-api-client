# ImageSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Images** | [**[]ImageInfo**](ImageInfo.md) |  | 
**Total** | [**Amount**](Amount.md) |  | 
**UnusedCount** | **int32** |  | 

## Methods

### NewImageSummary

`func NewImageSummary(images []ImageInfo, total Amount, unusedCount int32, ) *ImageSummary`

NewImageSummary instantiates a new ImageSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImageSummaryWithDefaults

`func NewImageSummaryWithDefaults() *ImageSummary`

NewImageSummaryWithDefaults instantiates a new ImageSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

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


### GetTotal

`func (o *ImageSummary) GetTotal() Amount`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *ImageSummary) GetTotalOk() (*Amount, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *ImageSummary) SetTotal(v Amount)`

SetTotal sets Total field to given value.


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



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


