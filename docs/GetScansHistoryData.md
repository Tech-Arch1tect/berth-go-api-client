# GetScansHistoryData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Page** | **int32** |  | 
**PageSize** | **int32** |  | 
**Scans** | [**[]ScanWithSummary**](ScanWithSummary.md) |  | 
**Total** | **int32** |  | 

## Methods

### NewGetScansHistoryData

`func NewGetScansHistoryData(page int32, pageSize int32, scans []ScanWithSummary, total int32, ) *GetScansHistoryData`

NewGetScansHistoryData instantiates a new GetScansHistoryData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetScansHistoryDataWithDefaults

`func NewGetScansHistoryDataWithDefaults() *GetScansHistoryData`

NewGetScansHistoryDataWithDefaults instantiates a new GetScansHistoryData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPage

`func (o *GetScansHistoryData) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *GetScansHistoryData) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *GetScansHistoryData) SetPage(v int32)`

SetPage sets Page field to given value.


### GetPageSize

`func (o *GetScansHistoryData) GetPageSize() int32`

GetPageSize returns the PageSize field if non-nil, zero value otherwise.

### GetPageSizeOk

`func (o *GetScansHistoryData) GetPageSizeOk() (*int32, bool)`

GetPageSizeOk returns a tuple with the PageSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageSize

`func (o *GetScansHistoryData) SetPageSize(v int32)`

SetPageSize sets PageSize field to given value.


### GetScans

`func (o *GetScansHistoryData) GetScans() []ScanWithSummary`

GetScans returns the Scans field if non-nil, zero value otherwise.

### GetScansOk

`func (o *GetScansHistoryData) GetScansOk() (*[]ScanWithSummary, bool)`

GetScansOk returns a tuple with the Scans field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScans

`func (o *GetScansHistoryData) SetScans(v []ScanWithSummary)`

SetScans sets Scans field to given value.


### GetTotal

`func (o *GetScansHistoryData) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *GetScansHistoryData) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *GetScansHistoryData) SetTotal(v int32)`

SetTotal sets Total field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


