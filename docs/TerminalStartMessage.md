# TerminalStartMessage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Cols** | Pointer to **int32** |  | [optional] 
**ContainerName** | Pointer to **string** |  | [optional] 
**Rows** | Pointer to **int32** |  | [optional] 
**ServiceName** | **string** |  | 
**StackName** | Pointer to **string** | Optional; must match the URL stack when set | [optional] 
**Type** | **string** | Always terminal_start | 

## Methods

### NewTerminalStartMessage

`func NewTerminalStartMessage(serviceName string, type_ string, ) *TerminalStartMessage`

NewTerminalStartMessage instantiates a new TerminalStartMessage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTerminalStartMessageWithDefaults

`func NewTerminalStartMessageWithDefaults() *TerminalStartMessage`

NewTerminalStartMessageWithDefaults instantiates a new TerminalStartMessage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCols

`func (o *TerminalStartMessage) GetCols() int32`

GetCols returns the Cols field if non-nil, zero value otherwise.

### GetColsOk

`func (o *TerminalStartMessage) GetColsOk() (*int32, bool)`

GetColsOk returns a tuple with the Cols field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCols

`func (o *TerminalStartMessage) SetCols(v int32)`

SetCols sets Cols field to given value.

### HasCols

`func (o *TerminalStartMessage) HasCols() bool`

HasCols returns a boolean if a field has been set.

### GetContainerName

`func (o *TerminalStartMessage) GetContainerName() string`

GetContainerName returns the ContainerName field if non-nil, zero value otherwise.

### GetContainerNameOk

`func (o *TerminalStartMessage) GetContainerNameOk() (*string, bool)`

GetContainerNameOk returns a tuple with the ContainerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainerName

`func (o *TerminalStartMessage) SetContainerName(v string)`

SetContainerName sets ContainerName field to given value.

### HasContainerName

`func (o *TerminalStartMessage) HasContainerName() bool`

HasContainerName returns a boolean if a field has been set.

### GetRows

`func (o *TerminalStartMessage) GetRows() int32`

GetRows returns the Rows field if non-nil, zero value otherwise.

### GetRowsOk

`func (o *TerminalStartMessage) GetRowsOk() (*int32, bool)`

GetRowsOk returns a tuple with the Rows field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRows

`func (o *TerminalStartMessage) SetRows(v int32)`

SetRows sets Rows field to given value.

### HasRows

`func (o *TerminalStartMessage) HasRows() bool`

HasRows returns a boolean if a field has been set.

### GetServiceName

`func (o *TerminalStartMessage) GetServiceName() string`

GetServiceName returns the ServiceName field if non-nil, zero value otherwise.

### GetServiceNameOk

`func (o *TerminalStartMessage) GetServiceNameOk() (*string, bool)`

GetServiceNameOk returns a tuple with the ServiceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceName

`func (o *TerminalStartMessage) SetServiceName(v string)`

SetServiceName sets ServiceName field to given value.


### GetStackName

`func (o *TerminalStartMessage) GetStackName() string`

GetStackName returns the StackName field if non-nil, zero value otherwise.

### GetStackNameOk

`func (o *TerminalStartMessage) GetStackNameOk() (*string, bool)`

GetStackNameOk returns a tuple with the StackName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStackName

`func (o *TerminalStartMessage) SetStackName(v string)`

SetStackName sets StackName field to given value.

### HasStackName

`func (o *TerminalStartMessage) HasStackName() bool`

HasStackName returns a boolean if a field has been set.

### GetType

`func (o *TerminalStartMessage) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *TerminalStartMessage) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *TerminalStartMessage) SetType(v string)`

SetType sets Type field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


