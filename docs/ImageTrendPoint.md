# ImageTrendPoint

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Date** | **time.Time** |  | 
**ScanId** | **int32** |  | 
**Summary** | [**NullableVulnerabilitySummary**](VulnerabilitySummary.md) |  | 

## Methods

### NewImageTrendPoint

`func NewImageTrendPoint(date time.Time, scanId int32, summary NullableVulnerabilitySummary, ) *ImageTrendPoint`

NewImageTrendPoint instantiates a new ImageTrendPoint object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImageTrendPointWithDefaults

`func NewImageTrendPointWithDefaults() *ImageTrendPoint`

NewImageTrendPointWithDefaults instantiates a new ImageTrendPoint object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDate

`func (o *ImageTrendPoint) GetDate() time.Time`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *ImageTrendPoint) GetDateOk() (*time.Time, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *ImageTrendPoint) SetDate(v time.Time)`

SetDate sets Date field to given value.


### GetScanId

`func (o *ImageTrendPoint) GetScanId() int32`

GetScanId returns the ScanId field if non-nil, zero value otherwise.

### GetScanIdOk

`func (o *ImageTrendPoint) GetScanIdOk() (*int32, bool)`

GetScanIdOk returns a tuple with the ScanId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScanId

`func (o *ImageTrendPoint) SetScanId(v int32)`

SetScanId sets ScanId field to given value.


### GetSummary

`func (o *ImageTrendPoint) GetSummary() VulnerabilitySummary`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *ImageTrendPoint) GetSummaryOk() (*VulnerabilitySummary, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *ImageTrendPoint) SetSummary(v VulnerabilitySummary)`

SetSummary sets Summary field to given value.


### SetSummaryNil

`func (o *ImageTrendPoint) SetSummaryNil(b bool)`

 SetSummaryNil sets the value for Summary to be an explicit nil

### UnsetSummary
`func (o *ImageTrendPoint) UnsetSummary()`

UnsetSummary ensures that no value is present for Summary, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


