# PerImageTrend

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ImageName** | **string** |  | 
**TrendPoints** | [**[]ImageTrendPoint**](ImageTrendPoint.md) |  | 

## Methods

### NewPerImageTrend

`func NewPerImageTrend(imageName string, trendPoints []ImageTrendPoint, ) *PerImageTrend`

NewPerImageTrend instantiates a new PerImageTrend object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPerImageTrendWithDefaults

`func NewPerImageTrendWithDefaults() *PerImageTrend`

NewPerImageTrendWithDefaults instantiates a new PerImageTrend object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetImageName

`func (o *PerImageTrend) GetImageName() string`

GetImageName returns the ImageName field if non-nil, zero value otherwise.

### GetImageNameOk

`func (o *PerImageTrend) GetImageNameOk() (*string, bool)`

GetImageNameOk returns a tuple with the ImageName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageName

`func (o *PerImageTrend) SetImageName(v string)`

SetImageName sets ImageName field to given value.


### GetTrendPoints

`func (o *PerImageTrend) GetTrendPoints() []ImageTrendPoint`

GetTrendPoints returns the TrendPoints field if non-nil, zero value otherwise.

### GetTrendPointsOk

`func (o *PerImageTrend) GetTrendPointsOk() (*[]ImageTrendPoint, bool)`

GetTrendPointsOk returns a tuple with the TrendPoints field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrendPoints

`func (o *PerImageTrend) SetTrendPoints(v []ImageTrendPoint)`

SetTrendPoints sets TrendPoints field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


