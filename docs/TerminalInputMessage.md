# TerminalInputMessage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Input** | **[]int32** | Raw input bytes as integer values | 
**SessionId** | **string** |  | 
**Timestamp** | Pointer to **string** |  | [optional] 
**Type** | **string** | Always terminal_input | 

## Methods

### NewTerminalInputMessage

`func NewTerminalInputMessage(input []int32, sessionId string, type_ string, ) *TerminalInputMessage`

NewTerminalInputMessage instantiates a new TerminalInputMessage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTerminalInputMessageWithDefaults

`func NewTerminalInputMessageWithDefaults() *TerminalInputMessage`

NewTerminalInputMessageWithDefaults instantiates a new TerminalInputMessage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetInput

`func (o *TerminalInputMessage) GetInput() []int32`

GetInput returns the Input field if non-nil, zero value otherwise.

### GetInputOk

`func (o *TerminalInputMessage) GetInputOk() (*[]int32, bool)`

GetInputOk returns a tuple with the Input field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInput

`func (o *TerminalInputMessage) SetInput(v []int32)`

SetInput sets Input field to given value.


### GetSessionId

`func (o *TerminalInputMessage) GetSessionId() string`

GetSessionId returns the SessionId field if non-nil, zero value otherwise.

### GetSessionIdOk

`func (o *TerminalInputMessage) GetSessionIdOk() (*string, bool)`

GetSessionIdOk returns a tuple with the SessionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSessionId

`func (o *TerminalInputMessage) SetSessionId(v string)`

SetSessionId sets SessionId field to given value.


### GetTimestamp

`func (o *TerminalInputMessage) GetTimestamp() string`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *TerminalInputMessage) GetTimestampOk() (*string, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *TerminalInputMessage) SetTimestamp(v string)`

SetTimestamp sets Timestamp field to given value.

### HasTimestamp

`func (o *TerminalInputMessage) HasTimestamp() bool`

HasTimestamp returns a boolean if a field has been set.

### GetType

`func (o *TerminalInputMessage) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *TerminalInputMessage) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *TerminalInputMessage) SetType(v string)`

SetType sets Type field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


