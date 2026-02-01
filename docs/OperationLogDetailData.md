# OperationLogDetailData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Log** | [**OperationLogInfo**](OperationLogInfo.md) |  | 
**Messages** | [**[]OperationLogMessage**](OperationLogMessage.md) |  | 

## Methods

### NewOperationLogDetailData

`func NewOperationLogDetailData(log OperationLogInfo, messages []OperationLogMessage, ) *OperationLogDetailData`

NewOperationLogDetailData instantiates a new OperationLogDetailData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperationLogDetailDataWithDefaults

`func NewOperationLogDetailDataWithDefaults() *OperationLogDetailData`

NewOperationLogDetailDataWithDefaults instantiates a new OperationLogDetailData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLog

`func (o *OperationLogDetailData) GetLog() OperationLogInfo`

GetLog returns the Log field if non-nil, zero value otherwise.

### GetLogOk

`func (o *OperationLogDetailData) GetLogOk() (*OperationLogInfo, bool)`

GetLogOk returns a tuple with the Log field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLog

`func (o *OperationLogDetailData) SetLog(v OperationLogInfo)`

SetLog sets Log field to given value.


### GetMessages

`func (o *OperationLogDetailData) GetMessages() []OperationLogMessage`

GetMessages returns the Messages field if non-nil, zero value otherwise.

### GetMessagesOk

`func (o *OperationLogDetailData) GetMessagesOk() (*[]OperationLogMessage, bool)`

GetMessagesOk returns a tuple with the Messages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessages

`func (o *OperationLogDetailData) SetMessages(v []OperationLogMessage)`

SetMessages sets Messages field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


