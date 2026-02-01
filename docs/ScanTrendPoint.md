# ScanTrendPoint

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Date** | **time.Time** |  | 
**ScanId** | **int32** |  | 
**Summary** | [**NullableVulnerabilitySummary**](VulnerabilitySummary.md) |  | 

## Methods

### NewScanTrendPoint

`func NewScanTrendPoint(date time.Time, scanId int32, summary NullableVulnerabilitySummary, ) *ScanTrendPoint`

NewScanTrendPoint instantiates a new ScanTrendPoint object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewScanTrendPointWithDefaults

`func NewScanTrendPointWithDefaults() *ScanTrendPoint`

NewScanTrendPointWithDefaults instantiates a new ScanTrendPoint object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDate

`func (o *ScanTrendPoint) GetDate() time.Time`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *ScanTrendPoint) GetDateOk() (*time.Time, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *ScanTrendPoint) SetDate(v time.Time)`

SetDate sets Date field to given value.


### GetScanId

`func (o *ScanTrendPoint) GetScanId() int32`

GetScanId returns the ScanId field if non-nil, zero value otherwise.

### GetScanIdOk

`func (o *ScanTrendPoint) GetScanIdOk() (*int32, bool)`

GetScanIdOk returns a tuple with the ScanId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScanId

`func (o *ScanTrendPoint) SetScanId(v int32)`

SetScanId sets ScanId field to given value.


### GetSummary

`func (o *ScanTrendPoint) GetSummary() VulnerabilitySummary`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *ScanTrendPoint) GetSummaryOk() (*VulnerabilitySummary, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *ScanTrendPoint) SetSummary(v VulnerabilitySummary)`

SetSummary sets Summary field to given value.


### SetSummaryNil

`func (o *ScanTrendPoint) SetSummaryNil(b bool)`

 SetSummaryNil sets the value for Summary to be an explicit nil

### UnsetSummary
`func (o *ScanTrendPoint) UnsetSummary()`

UnsetSummary ensures that no value is present for Summary, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


