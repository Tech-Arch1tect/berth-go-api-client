# TerminalResizeMessage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Cols** | **int32** |  | 
**Rows** | **int32** |  | 
**SessionId** | **string** |  | 
**Timestamp** | Pointer to **string** |  | [optional] 
**Type** | **string** | Always terminal_resize | 

## Methods

### NewTerminalResizeMessage

`func NewTerminalResizeMessage(cols int32, rows int32, sessionId string, type_ string, ) *TerminalResizeMessage`

NewTerminalResizeMessage instantiates a new TerminalResizeMessage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTerminalResizeMessageWithDefaults

`func NewTerminalResizeMessageWithDefaults() *TerminalResizeMessage`

NewTerminalResizeMessageWithDefaults instantiates a new TerminalResizeMessage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCols

`func (o *TerminalResizeMessage) GetCols() int32`

GetCols returns the Cols field if non-nil, zero value otherwise.

### GetColsOk

`func (o *TerminalResizeMessage) GetColsOk() (*int32, bool)`

GetColsOk returns a tuple with the Cols field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCols

`func (o *TerminalResizeMessage) SetCols(v int32)`

SetCols sets Cols field to given value.


### GetRows

`func (o *TerminalResizeMessage) GetRows() int32`

GetRows returns the Rows field if non-nil, zero value otherwise.

### GetRowsOk

`func (o *TerminalResizeMessage) GetRowsOk() (*int32, bool)`

GetRowsOk returns a tuple with the Rows field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRows

`func (o *TerminalResizeMessage) SetRows(v int32)`

SetRows sets Rows field to given value.


### GetSessionId

`func (o *TerminalResizeMessage) GetSessionId() string`

GetSessionId returns the SessionId field if non-nil, zero value otherwise.

### GetSessionIdOk

`func (o *TerminalResizeMessage) GetSessionIdOk() (*string, bool)`

GetSessionIdOk returns a tuple with the SessionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSessionId

`func (o *TerminalResizeMessage) SetSessionId(v string)`

SetSessionId sets SessionId field to given value.


### GetTimestamp

`func (o *TerminalResizeMessage) GetTimestamp() string`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *TerminalResizeMessage) GetTimestampOk() (*string, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *TerminalResizeMessage) SetTimestamp(v string)`

SetTimestamp sets Timestamp field to given value.

### HasTimestamp

`func (o *TerminalResizeMessage) HasTimestamp() bool`

HasTimestamp returns a boolean if a field has been set.

### GetType

`func (o *TerminalResizeMessage) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *TerminalResizeMessage) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *TerminalResizeMessage) SetType(v string)`

SetType sets Type field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


