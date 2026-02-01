# DeleteCredentialResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**DeleteCredentialMessageData**](DeleteCredentialMessageData.md) |  | 
**Success** | **bool** |  | 

## Methods

### NewDeleteCredentialResponse

`func NewDeleteCredentialResponse(data DeleteCredentialMessageData, success bool, ) *DeleteCredentialResponse`

NewDeleteCredentialResponse instantiates a new DeleteCredentialResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeleteCredentialResponseWithDefaults

`func NewDeleteCredentialResponseWithDefaults() *DeleteCredentialResponse`

NewDeleteCredentialResponseWithDefaults instantiates a new DeleteCredentialResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *DeleteCredentialResponse) GetData() DeleteCredentialMessageData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *DeleteCredentialResponse) GetDataOk() (*DeleteCredentialMessageData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *DeleteCredentialResponse) SetData(v DeleteCredentialMessageData)`

SetData sets Data field to given value.


### GetSuccess

`func (o *DeleteCredentialResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *DeleteCredentialResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *DeleteCredentialResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


