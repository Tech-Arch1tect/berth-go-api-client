# TerminalCloseMessage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ExitCode** | Pointer to **int32** |  | [optional] 
**SessionId** | **string** |  | 
**Timestamp** | Pointer to **string** |  | [optional] 
**Type** | **string** | Always terminal_close | 

## Methods

### NewTerminalCloseMessage

`func NewTerminalCloseMessage(sessionId string, type_ string, ) *TerminalCloseMessage`

NewTerminalCloseMessage instantiates a new TerminalCloseMessage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTerminalCloseMessageWithDefaults

`func NewTerminalCloseMessageWithDefaults() *TerminalCloseMessage`

NewTerminalCloseMessageWithDefaults instantiates a new TerminalCloseMessage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExitCode

`func (o *TerminalCloseMessage) GetExitCode() int32`

GetExitCode returns the ExitCode field if non-nil, zero value otherwise.

### GetExitCodeOk

`func (o *TerminalCloseMessage) GetExitCodeOk() (*int32, bool)`

GetExitCodeOk returns a tuple with the ExitCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExitCode

`func (o *TerminalCloseMessage) SetExitCode(v int32)`

SetExitCode sets ExitCode field to given value.

### HasExitCode

`func (o *TerminalCloseMessage) HasExitCode() bool`

HasExitCode returns a boolean if a field has been set.

### GetSessionId

`func (o *TerminalCloseMessage) GetSessionId() string`

GetSessionId returns the SessionId field if non-nil, zero value otherwise.

### GetSessionIdOk

`func (o *TerminalCloseMessage) GetSessionIdOk() (*string, bool)`

GetSessionIdOk returns a tuple with the SessionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSessionId

`func (o *TerminalCloseMessage) SetSessionId(v string)`

SetSessionId sets SessionId field to given value.


### GetTimestamp

`func (o *TerminalCloseMessage) GetTimestamp() string`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *TerminalCloseMessage) GetTimestampOk() (*string, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *TerminalCloseMessage) SetTimestamp(v string)`

SetTimestamp sets Timestamp field to given value.

### HasTimestamp

`func (o *TerminalCloseMessage) HasTimestamp() bool`

HasTimestamp returns a boolean if a field has been set.

### GetType

`func (o *TerminalCloseMessage) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *TerminalCloseMessage) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *TerminalCloseMessage) SetType(v string)`

SetType sets Type field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


