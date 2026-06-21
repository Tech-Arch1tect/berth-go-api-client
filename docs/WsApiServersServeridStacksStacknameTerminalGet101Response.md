# WsApiServersServeridStacksStacknameTerminalGet101Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Cols** | **int32** |  | 
**ContainerName** | Pointer to **string** |  | [optional] 
**Rows** | **int32** |  | 
**ServiceName** | **string** |  | 
**StackName** | Pointer to **string** | Optional; must match the URL stack when set | [optional] 
**Type** | **string** | Always error | 
**Input** | **[]int32** | Raw input bytes as integer values | 
**SessionId** | **string** |  | 
**Timestamp** | Pointer to **string** |  | [optional] 
**ExitCode** | Pointer to **int32** |  | [optional] 
**Output** | **string** | Base64-encoded output bytes | 
**Message** | Pointer to **string** |  | [optional] 
**Error** | **string** |  | 

## Methods

### NewWsApiServersServeridStacksStacknameTerminalGet101Response

`func NewWsApiServersServeridStacksStacknameTerminalGet101Response(cols int32, rows int32, serviceName string, type_ string, input []int32, sessionId string, output string, error_ string, ) *WsApiServersServeridStacksStacknameTerminalGet101Response`

NewWsApiServersServeridStacksStacknameTerminalGet101Response instantiates a new WsApiServersServeridStacksStacknameTerminalGet101Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWsApiServersServeridStacksStacknameTerminalGet101ResponseWithDefaults

`func NewWsApiServersServeridStacksStacknameTerminalGet101ResponseWithDefaults() *WsApiServersServeridStacksStacknameTerminalGet101Response`

NewWsApiServersServeridStacksStacknameTerminalGet101ResponseWithDefaults instantiates a new WsApiServersServeridStacksStacknameTerminalGet101Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCols

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) GetCols() int32`

GetCols returns the Cols field if non-nil, zero value otherwise.

### GetColsOk

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) GetColsOk() (*int32, bool)`

GetColsOk returns a tuple with the Cols field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCols

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) SetCols(v int32)`

SetCols sets Cols field to given value.


### GetContainerName

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) GetContainerName() string`

GetContainerName returns the ContainerName field if non-nil, zero value otherwise.

### GetContainerNameOk

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) GetContainerNameOk() (*string, bool)`

GetContainerNameOk returns a tuple with the ContainerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainerName

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) SetContainerName(v string)`

SetContainerName sets ContainerName field to given value.

### HasContainerName

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) HasContainerName() bool`

HasContainerName returns a boolean if a field has been set.

### GetRows

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) GetRows() int32`

GetRows returns the Rows field if non-nil, zero value otherwise.

### GetRowsOk

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) GetRowsOk() (*int32, bool)`

GetRowsOk returns a tuple with the Rows field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRows

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) SetRows(v int32)`

SetRows sets Rows field to given value.


### GetServiceName

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) GetServiceName() string`

GetServiceName returns the ServiceName field if non-nil, zero value otherwise.

### GetServiceNameOk

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) GetServiceNameOk() (*string, bool)`

GetServiceNameOk returns a tuple with the ServiceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceName

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) SetServiceName(v string)`

SetServiceName sets ServiceName field to given value.


### GetStackName

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) GetStackName() string`

GetStackName returns the StackName field if non-nil, zero value otherwise.

### GetStackNameOk

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) GetStackNameOk() (*string, bool)`

GetStackNameOk returns a tuple with the StackName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStackName

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) SetStackName(v string)`

SetStackName sets StackName field to given value.

### HasStackName

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) HasStackName() bool`

HasStackName returns a boolean if a field has been set.

### GetType

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) SetType(v string)`

SetType sets Type field to given value.


### GetInput

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) GetInput() []int32`

GetInput returns the Input field if non-nil, zero value otherwise.

### GetInputOk

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) GetInputOk() (*[]int32, bool)`

GetInputOk returns a tuple with the Input field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInput

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) SetInput(v []int32)`

SetInput sets Input field to given value.


### GetSessionId

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) GetSessionId() string`

GetSessionId returns the SessionId field if non-nil, zero value otherwise.

### GetSessionIdOk

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) GetSessionIdOk() (*string, bool)`

GetSessionIdOk returns a tuple with the SessionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSessionId

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) SetSessionId(v string)`

SetSessionId sets SessionId field to given value.


### GetTimestamp

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) GetTimestamp() string`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) GetTimestampOk() (*string, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) SetTimestamp(v string)`

SetTimestamp sets Timestamp field to given value.

### HasTimestamp

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) HasTimestamp() bool`

HasTimestamp returns a boolean if a field has been set.

### GetExitCode

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) GetExitCode() int32`

GetExitCode returns the ExitCode field if non-nil, zero value otherwise.

### GetExitCodeOk

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) GetExitCodeOk() (*int32, bool)`

GetExitCodeOk returns a tuple with the ExitCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExitCode

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) SetExitCode(v int32)`

SetExitCode sets ExitCode field to given value.

### HasExitCode

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) HasExitCode() bool`

HasExitCode returns a boolean if a field has been set.

### GetOutput

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) GetOutput() string`

GetOutput returns the Output field if non-nil, zero value otherwise.

### GetOutputOk

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) GetOutputOk() (*string, bool)`

GetOutputOk returns a tuple with the Output field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutput

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) SetOutput(v string)`

SetOutput sets Output field to given value.


### GetMessage

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetError

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *WsApiServersServeridStacksStacknameTerminalGet101Response) SetError(v string)`

SetError sets Error field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


