# TerminalOutputMessage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Output** | **string** | Base64-encoded output bytes | 
**SessionId** | **string** |  | 
**Timestamp** | Pointer to **string** |  | [optional] 
**Type** | **string** | Always terminal_output | 

## Methods

### NewTerminalOutputMessage

`func NewTerminalOutputMessage(output string, sessionId string, type_ string, ) *TerminalOutputMessage`

NewTerminalOutputMessage instantiates a new TerminalOutputMessage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTerminalOutputMessageWithDefaults

`func NewTerminalOutputMessageWithDefaults() *TerminalOutputMessage`

NewTerminalOutputMessageWithDefaults instantiates a new TerminalOutputMessage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOutput

`func (o *TerminalOutputMessage) GetOutput() string`

GetOutput returns the Output field if non-nil, zero value otherwise.

### GetOutputOk

`func (o *TerminalOutputMessage) GetOutputOk() (*string, bool)`

GetOutputOk returns a tuple with the Output field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutput

`func (o *TerminalOutputMessage) SetOutput(v string)`

SetOutput sets Output field to given value.


### GetSessionId

`func (o *TerminalOutputMessage) GetSessionId() string`

GetSessionId returns the SessionId field if non-nil, zero value otherwise.

### GetSessionIdOk

`func (o *TerminalOutputMessage) GetSessionIdOk() (*string, bool)`

GetSessionIdOk returns a tuple with the SessionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSessionId

`func (o *TerminalOutputMessage) SetSessionId(v string)`

SetSessionId sets SessionId field to given value.


### GetTimestamp

`func (o *TerminalOutputMessage) GetTimestamp() string`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *TerminalOutputMessage) GetTimestampOk() (*string, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *TerminalOutputMessage) SetTimestamp(v string)`

SetTimestamp sets Timestamp field to given value.

### HasTimestamp

`func (o *TerminalOutputMessage) HasTimestamp() bool`

HasTimestamp returns a boolean if a field has been set.

### GetType

`func (o *TerminalOutputMessage) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *TerminalOutputMessage) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *TerminalOutputMessage) SetType(v string)`

SetType sets Type field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


