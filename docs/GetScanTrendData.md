# GetScanTrendData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PerImageTrend** | [**[]PerImageTrend**](PerImageTrend.md) |  | 
**ScopeWarning** | Pointer to **string** |  | [optional] 
**StackTrend** | [**[]ScanTrendPoint**](ScanTrendPoint.md) |  | 

## Methods

### NewGetScanTrendData

`func NewGetScanTrendData(perImageTrend []PerImageTrend, stackTrend []ScanTrendPoint, ) *GetScanTrendData`

NewGetScanTrendData instantiates a new GetScanTrendData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetScanTrendDataWithDefaults

`func NewGetScanTrendDataWithDefaults() *GetScanTrendData`

NewGetScanTrendDataWithDefaults instantiates a new GetScanTrendData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPerImageTrend

`func (o *GetScanTrendData) GetPerImageTrend() []PerImageTrend`

GetPerImageTrend returns the PerImageTrend field if non-nil, zero value otherwise.

### GetPerImageTrendOk

`func (o *GetScanTrendData) GetPerImageTrendOk() (*[]PerImageTrend, bool)`

GetPerImageTrendOk returns a tuple with the PerImageTrend field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerImageTrend

`func (o *GetScanTrendData) SetPerImageTrend(v []PerImageTrend)`

SetPerImageTrend sets PerImageTrend field to given value.


### GetScopeWarning

`func (o *GetScanTrendData) GetScopeWarning() string`

GetScopeWarning returns the ScopeWarning field if non-nil, zero value otherwise.

### GetScopeWarningOk

`func (o *GetScanTrendData) GetScopeWarningOk() (*string, bool)`

GetScopeWarningOk returns a tuple with the ScopeWarning field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScopeWarning

`func (o *GetScanTrendData) SetScopeWarning(v string)`

SetScopeWarning sets ScopeWarning field to given value.

### HasScopeWarning

`func (o *GetScanTrendData) HasScopeWarning() bool`

HasScopeWarning returns a boolean if a field has been set.

### GetStackTrend

`func (o *GetScanTrendData) GetStackTrend() []ScanTrendPoint`

GetStackTrend returns the StackTrend field if non-nil, zero value otherwise.

### GetStackTrendOk

`func (o *GetScanTrendData) GetStackTrendOk() (*[]ScanTrendPoint, bool)`

GetStackTrendOk returns a tuple with the StackTrend field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStackTrend

`func (o *GetScanTrendData) SetStackTrend(v []ScanTrendPoint)`

SetStackTrend sets StackTrend field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


