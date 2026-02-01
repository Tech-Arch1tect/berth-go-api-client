# GetScansHistoryResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**GetScansHistoryData**](GetScansHistoryData.md) |  | 
**Success** | **bool** |  | 

## Methods

### NewGetScansHistoryResponse

`func NewGetScansHistoryResponse(data GetScansHistoryData, success bool, ) *GetScansHistoryResponse`

NewGetScansHistoryResponse instantiates a new GetScansHistoryResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetScansHistoryResponseWithDefaults

`func NewGetScansHistoryResponseWithDefaults() *GetScansHistoryResponse`

NewGetScansHistoryResponseWithDefaults instantiates a new GetScansHistoryResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *GetScansHistoryResponse) GetData() GetScansHistoryData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetScansHistoryResponse) GetDataOk() (*GetScansHistoryData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetScansHistoryResponse) SetData(v GetScansHistoryData)`

SetData sets Data field to given value.


### GetSuccess

`func (o *GetScansHistoryResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *GetScansHistoryResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *GetScansHistoryResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


