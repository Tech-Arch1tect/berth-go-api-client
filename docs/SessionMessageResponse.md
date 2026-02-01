# SessionMessageResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**SessionMessageData**](SessionMessageData.md) |  | 
**Success** | **bool** |  | 

## Methods

### NewSessionMessageResponse

`func NewSessionMessageResponse(data SessionMessageData, success bool, ) *SessionMessageResponse`

NewSessionMessageResponse instantiates a new SessionMessageResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSessionMessageResponseWithDefaults

`func NewSessionMessageResponseWithDefaults() *SessionMessageResponse`

NewSessionMessageResponseWithDefaults instantiates a new SessionMessageResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *SessionMessageResponse) GetData() SessionMessageData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *SessionMessageResponse) GetDataOk() (*SessionMessageData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *SessionMessageResponse) SetData(v SessionMessageData)`

SetData sets Data field to given value.


### GetSuccess

`func (o *SessionMessageResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *SessionMessageResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *SessionMessageResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


