# GetLatestScanData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Scan** | [**ImageScan**](ImageScan.md) |  | 
**Summary** | [**NullableVulnerabilitySummary**](VulnerabilitySummary.md) |  | 

## Methods

### NewGetLatestScanData

`func NewGetLatestScanData(scan ImageScan, summary NullableVulnerabilitySummary, ) *GetLatestScanData`

NewGetLatestScanData instantiates a new GetLatestScanData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetLatestScanDataWithDefaults

`func NewGetLatestScanDataWithDefaults() *GetLatestScanData`

NewGetLatestScanDataWithDefaults instantiates a new GetLatestScanData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetScan

`func (o *GetLatestScanData) GetScan() ImageScan`

GetScan returns the Scan field if non-nil, zero value otherwise.

### GetScanOk

`func (o *GetLatestScanData) GetScanOk() (*ImageScan, bool)`

GetScanOk returns a tuple with the Scan field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScan

`func (o *GetLatestScanData) SetScan(v ImageScan)`

SetScan sets Scan field to given value.


### GetSummary

`func (o *GetLatestScanData) GetSummary() VulnerabilitySummary`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *GetLatestScanData) GetSummaryOk() (*VulnerabilitySummary, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *GetLatestScanData) SetSummary(v VulnerabilitySummary)`

SetSummary sets Summary field to given value.


### SetSummaryNil

`func (o *GetLatestScanData) SetSummaryNil(b bool)`

 SetSummaryNil sets the value for Summary to be an explicit nil

### UnsetSummary
`func (o *GetLatestScanData) UnsetSummary()`

UnsetSummary ensures that no value is present for Summary, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


