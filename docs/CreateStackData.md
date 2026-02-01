# CreateStackData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | **string** |  | 
**Stack** | [**NullableStack**](Stack.md) |  | 

## Methods

### NewCreateStackData

`func NewCreateStackData(message string, stack NullableStack, ) *CreateStackData`

NewCreateStackData instantiates a new CreateStackData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateStackDataWithDefaults

`func NewCreateStackDataWithDefaults() *CreateStackData`

NewCreateStackDataWithDefaults instantiates a new CreateStackData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *CreateStackData) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *CreateStackData) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *CreateStackData) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetStack

`func (o *CreateStackData) GetStack() Stack`

GetStack returns the Stack field if non-nil, zero value otherwise.

### GetStackOk

`func (o *CreateStackData) GetStackOk() (*Stack, bool)`

GetStackOk returns a tuple with the Stack field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStack

`func (o *CreateStackData) SetStack(v Stack)`

SetStack sets Stack field to given value.


### SetStackNil

`func (o *CreateStackData) SetStackNil(b bool)`

 SetStackNil sets the value for Stack to be an explicit nil

### UnsetStack
`func (o *CreateStackData) UnsetStack()`

UnsetStack ensures that no value is present for Stack, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


