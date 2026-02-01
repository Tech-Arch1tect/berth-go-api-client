# ScanWithSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Scan** | [**ImageScan**](ImageScan.md) |  | 
**Summary** | Pointer to [**NullableVulnerabilitySummary**](VulnerabilitySummary.md) |  | [optional] 

## Methods

### NewScanWithSummary

`func NewScanWithSummary(scan ImageScan, ) *ScanWithSummary`

NewScanWithSummary instantiates a new ScanWithSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewScanWithSummaryWithDefaults

`func NewScanWithSummaryWithDefaults() *ScanWithSummary`

NewScanWithSummaryWithDefaults instantiates a new ScanWithSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetScan

`func (o *ScanWithSummary) GetScan() ImageScan`

GetScan returns the Scan field if non-nil, zero value otherwise.

### GetScanOk

`func (o *ScanWithSummary) GetScanOk() (*ImageScan, bool)`

GetScanOk returns a tuple with the Scan field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScan

`func (o *ScanWithSummary) SetScan(v ImageScan)`

SetScan sets Scan field to given value.


### GetSummary

`func (o *ScanWithSummary) GetSummary() VulnerabilitySummary`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *ScanWithSummary) GetSummaryOk() (*VulnerabilitySummary, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *ScanWithSummary) SetSummary(v VulnerabilitySummary)`

SetSummary sets Summary field to given value.

### HasSummary

`func (o *ScanWithSummary) HasSummary() bool`

HasSummary returns a boolean if a field has been set.

### SetSummaryNil

`func (o *ScanWithSummary) SetSummaryNil(b bool)`

 SetSummaryNil sets the value for Summary to be an explicit nil

### UnsetSummary
`func (o *ScanWithSummary) UnsetSummary()`

UnsetSummary ensures that no value is present for Summary, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


