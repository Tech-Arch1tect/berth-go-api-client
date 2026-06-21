# StreamMessage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to **string** |  | [optional] 
**ExitCode** | Pointer to **NullableInt32** |  | [optional] 
**Success** | Pointer to **NullableBool** |  | [optional] 
**Timestamp** | **time.Time** |  | 
**Type** | **string** |  | 

## Methods

### NewStreamMessage

`func NewStreamMessage(timestamp time.Time, type_ string, ) *StreamMessage`

NewStreamMessage instantiates a new StreamMessage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStreamMessageWithDefaults

`func NewStreamMessageWithDefaults() *StreamMessage`

NewStreamMessageWithDefaults instantiates a new StreamMessage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *StreamMessage) GetData() string`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *StreamMessage) GetDataOk() (*string, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *StreamMessage) SetData(v string)`

SetData sets Data field to given value.

### HasData

`func (o *StreamMessage) HasData() bool`

HasData returns a boolean if a field has been set.

### GetExitCode

`func (o *StreamMessage) GetExitCode() int32`

GetExitCode returns the ExitCode field if non-nil, zero value otherwise.

### GetExitCodeOk

`func (o *StreamMessage) GetExitCodeOk() (*int32, bool)`

GetExitCodeOk returns a tuple with the ExitCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExitCode

`func (o *StreamMessage) SetExitCode(v int32)`

SetExitCode sets ExitCode field to given value.

### HasExitCode

`func (o *StreamMessage) HasExitCode() bool`

HasExitCode returns a boolean if a field has been set.

### SetExitCodeNil

`func (o *StreamMessage) SetExitCodeNil(b bool)`

 SetExitCodeNil sets the value for ExitCode to be an explicit nil

### UnsetExitCode
`func (o *StreamMessage) UnsetExitCode()`

UnsetExitCode ensures that no value is present for ExitCode, not even an explicit nil
### GetSuccess

`func (o *StreamMessage) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *StreamMessage) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *StreamMessage) SetSuccess(v bool)`

SetSuccess sets Success field to given value.

### HasSuccess

`func (o *StreamMessage) HasSuccess() bool`

HasSuccess returns a boolean if a field has been set.

### SetSuccessNil

`func (o *StreamMessage) SetSuccessNil(b bool)`

 SetSuccessNil sets the value for Success to be an explicit nil

### UnsetSuccess
`func (o *StreamMessage) UnsetSuccess()`

UnsetSuccess ensures that no value is present for Success, not even an explicit nil
### GetTimestamp

`func (o *StreamMessage) GetTimestamp() time.Time`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *StreamMessage) GetTimestampOk() (*time.Time, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *StreamMessage) SetTimestamp(v time.Time)`

SetTimestamp sets Timestamp field to given value.


### GetType

`func (o *StreamMessage) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *StreamMessage) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *StreamMessage) SetType(v string)`

SetType sets Type field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


