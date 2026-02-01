# OperationLogMessage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CreatedAt** | **time.Time** |  | 
**DeletedAt** | Pointer to [**DeletedAt**](DeletedAt.md) |  | [optional] 
**Id** | **int32** |  | 
**MessageData** | **string** |  | 
**MessageType** | **string** |  | 
**OperationLog** | [**OperationLog**](OperationLog.md) |  | 
**OperationLogId** | **int32** |  | 
**SequenceNumber** | **int32** |  | 
**Timestamp** | **time.Time** |  | 
**UpdatedAt** | **time.Time** |  | 

## Methods

### NewOperationLogMessage

`func NewOperationLogMessage(createdAt time.Time, id int32, messageData string, messageType string, operationLog OperationLog, operationLogId int32, sequenceNumber int32, timestamp time.Time, updatedAt time.Time, ) *OperationLogMessage`

NewOperationLogMessage instantiates a new OperationLogMessage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperationLogMessageWithDefaults

`func NewOperationLogMessageWithDefaults() *OperationLogMessage`

NewOperationLogMessageWithDefaults instantiates a new OperationLogMessage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreatedAt

`func (o *OperationLogMessage) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *OperationLogMessage) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *OperationLogMessage) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetDeletedAt

`func (o *OperationLogMessage) GetDeletedAt() DeletedAt`

GetDeletedAt returns the DeletedAt field if non-nil, zero value otherwise.

### GetDeletedAtOk

`func (o *OperationLogMessage) GetDeletedAtOk() (*DeletedAt, bool)`

GetDeletedAtOk returns a tuple with the DeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedAt

`func (o *OperationLogMessage) SetDeletedAt(v DeletedAt)`

SetDeletedAt sets DeletedAt field to given value.

### HasDeletedAt

`func (o *OperationLogMessage) HasDeletedAt() bool`

HasDeletedAt returns a boolean if a field has been set.

### GetId

`func (o *OperationLogMessage) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *OperationLogMessage) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *OperationLogMessage) SetId(v int32)`

SetId sets Id field to given value.


### GetMessageData

`func (o *OperationLogMessage) GetMessageData() string`

GetMessageData returns the MessageData field if non-nil, zero value otherwise.

### GetMessageDataOk

`func (o *OperationLogMessage) GetMessageDataOk() (*string, bool)`

GetMessageDataOk returns a tuple with the MessageData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageData

`func (o *OperationLogMessage) SetMessageData(v string)`

SetMessageData sets MessageData field to given value.


### GetMessageType

`func (o *OperationLogMessage) GetMessageType() string`

GetMessageType returns the MessageType field if non-nil, zero value otherwise.

### GetMessageTypeOk

`func (o *OperationLogMessage) GetMessageTypeOk() (*string, bool)`

GetMessageTypeOk returns a tuple with the MessageType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageType

`func (o *OperationLogMessage) SetMessageType(v string)`

SetMessageType sets MessageType field to given value.


### GetOperationLog

`func (o *OperationLogMessage) GetOperationLog() OperationLog`

GetOperationLog returns the OperationLog field if non-nil, zero value otherwise.

### GetOperationLogOk

`func (o *OperationLogMessage) GetOperationLogOk() (*OperationLog, bool)`

GetOperationLogOk returns a tuple with the OperationLog field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationLog

`func (o *OperationLogMessage) SetOperationLog(v OperationLog)`

SetOperationLog sets OperationLog field to given value.


### GetOperationLogId

`func (o *OperationLogMessage) GetOperationLogId() int32`

GetOperationLogId returns the OperationLogId field if non-nil, zero value otherwise.

### GetOperationLogIdOk

`func (o *OperationLogMessage) GetOperationLogIdOk() (*int32, bool)`

GetOperationLogIdOk returns a tuple with the OperationLogId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationLogId

`func (o *OperationLogMessage) SetOperationLogId(v int32)`

SetOperationLogId sets OperationLogId field to given value.


### GetSequenceNumber

`func (o *OperationLogMessage) GetSequenceNumber() int32`

GetSequenceNumber returns the SequenceNumber field if non-nil, zero value otherwise.

### GetSequenceNumberOk

`func (o *OperationLogMessage) GetSequenceNumberOk() (*int32, bool)`

GetSequenceNumberOk returns a tuple with the SequenceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSequenceNumber

`func (o *OperationLogMessage) SetSequenceNumber(v int32)`

SetSequenceNumber sets SequenceNumber field to given value.


### GetTimestamp

`func (o *OperationLogMessage) GetTimestamp() time.Time`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *OperationLogMessage) GetTimestampOk() (*time.Time, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *OperationLogMessage) SetTimestamp(v time.Time)`

SetTimestamp sets Timestamp field to given value.


### GetUpdatedAt

`func (o *OperationLogMessage) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *OperationLogMessage) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *OperationLogMessage) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


