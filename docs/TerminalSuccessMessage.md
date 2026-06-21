# TerminalSuccessMessage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** |  | [optional] 
**SessionId** | **string** |  | 
**Timestamp** | Pointer to **string** |  | [optional] 
**Type** | **string** | Always success | 

## Methods

### NewTerminalSuccessMessage

`func NewTerminalSuccessMessage(sessionId string, type_ string, ) *TerminalSuccessMessage`

NewTerminalSuccessMessage instantiates a new TerminalSuccessMessage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTerminalSuccessMessageWithDefaults

`func NewTerminalSuccessMessageWithDefaults() *TerminalSuccessMessage`

NewTerminalSuccessMessageWithDefaults instantiates a new TerminalSuccessMessage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *TerminalSuccessMessage) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *TerminalSuccessMessage) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *TerminalSuccessMessage) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *TerminalSuccessMessage) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetSessionId

`func (o *TerminalSuccessMessage) GetSessionId() string`

GetSessionId returns the SessionId field if non-nil, zero value otherwise.

### GetSessionIdOk

`func (o *TerminalSuccessMessage) GetSessionIdOk() (*string, bool)`

GetSessionIdOk returns a tuple with the SessionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSessionId

`func (o *TerminalSuccessMessage) SetSessionId(v string)`

SetSessionId sets SessionId field to given value.


### GetTimestamp

`func (o *TerminalSuccessMessage) GetTimestamp() string`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *TerminalSuccessMessage) GetTimestampOk() (*string, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *TerminalSuccessMessage) SetTimestamp(v string)`

SetTimestamp sets Timestamp field to given value.

### HasTimestamp

`func (o *TerminalSuccessMessage) HasTimestamp() bool`

HasTimestamp returns a boolean if a field has been set.

### GetType

`func (o *TerminalSuccessMessage) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *TerminalSuccessMessage) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *TerminalSuccessMessage) SetType(v string)`

SetType sets Type field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


