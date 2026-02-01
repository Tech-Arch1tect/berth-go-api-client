# PaginatedOperationLogsData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**[]OperationLogInfo**](OperationLogInfo.md) |  | 
**Pagination** | [**PaginationInfo**](PaginationInfo.md) |  | 

## Methods

### NewPaginatedOperationLogsData

`func NewPaginatedOperationLogsData(data []OperationLogInfo, pagination PaginationInfo, ) *PaginatedOperationLogsData`

NewPaginatedOperationLogsData instantiates a new PaginatedOperationLogsData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPaginatedOperationLogsDataWithDefaults

`func NewPaginatedOperationLogsDataWithDefaults() *PaginatedOperationLogsData`

NewPaginatedOperationLogsDataWithDefaults instantiates a new PaginatedOperationLogsData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *PaginatedOperationLogsData) GetData() []OperationLogInfo`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *PaginatedOperationLogsData) GetDataOk() (*[]OperationLogInfo, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *PaginatedOperationLogsData) SetData(v []OperationLogInfo)`

SetData sets Data field to given value.


### GetPagination

`func (o *PaginatedOperationLogsData) GetPagination() PaginationInfo`

GetPagination returns the Pagination field if non-nil, zero value otherwise.

### GetPaginationOk

`func (o *PaginatedOperationLogsData) GetPaginationOk() (*PaginationInfo, bool)`

GetPaginationOk returns a tuple with the Pagination field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPagination

`func (o *PaginatedOperationLogsData) SetPagination(v PaginationInfo)`

SetPagination sets Pagination field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


