# ListLogsResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Logs** | [**[]SecurityAuditLogInfo**](SecurityAuditLogInfo.md) |  | 
**Page** | **int32** |  | 
**PerPage** | **int32** |  | 
**Total** | **int32** |  | 
**TotalPages** | **int32** |  | 

## Methods

### NewListLogsResponseData

`func NewListLogsResponseData(logs []SecurityAuditLogInfo, page int32, perPage int32, total int32, totalPages int32, ) *ListLogsResponseData`

NewListLogsResponseData instantiates a new ListLogsResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListLogsResponseDataWithDefaults

`func NewListLogsResponseDataWithDefaults() *ListLogsResponseData`

NewListLogsResponseDataWithDefaults instantiates a new ListLogsResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLogs

`func (o *ListLogsResponseData) GetLogs() []SecurityAuditLogInfo`

GetLogs returns the Logs field if non-nil, zero value otherwise.

### GetLogsOk

`func (o *ListLogsResponseData) GetLogsOk() (*[]SecurityAuditLogInfo, bool)`

GetLogsOk returns a tuple with the Logs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogs

`func (o *ListLogsResponseData) SetLogs(v []SecurityAuditLogInfo)`

SetLogs sets Logs field to given value.


### GetPage

`func (o *ListLogsResponseData) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *ListLogsResponseData) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *ListLogsResponseData) SetPage(v int32)`

SetPage sets Page field to given value.


### GetPerPage

`func (o *ListLogsResponseData) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *ListLogsResponseData) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *ListLogsResponseData) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.


### GetTotal

`func (o *ListLogsResponseData) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *ListLogsResponseData) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *ListLogsResponseData) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetTotalPages

`func (o *ListLogsResponseData) GetTotalPages() int32`

GetTotalPages returns the TotalPages field if non-nil, zero value otherwise.

### GetTotalPagesOk

`func (o *ListLogsResponseData) GetTotalPagesOk() (*int32, bool)`

GetTotalPagesOk returns a tuple with the TotalPages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalPages

`func (o *ListLogsResponseData) SetTotalPages(v int32)`

SetTotalPages sets TotalPages field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


