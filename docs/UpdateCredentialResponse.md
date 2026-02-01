# UpdateCredentialResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**GetCredentialData**](GetCredentialData.md) |  | 
**Success** | **bool** |  | 

## Methods

### NewUpdateCredentialResponse

`func NewUpdateCredentialResponse(data GetCredentialData, success bool, ) *UpdateCredentialResponse`

NewUpdateCredentialResponse instantiates a new UpdateCredentialResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateCredentialResponseWithDefaults

`func NewUpdateCredentialResponseWithDefaults() *UpdateCredentialResponse`

NewUpdateCredentialResponseWithDefaults instantiates a new UpdateCredentialResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *UpdateCredentialResponse) GetData() GetCredentialData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *UpdateCredentialResponse) GetDataOk() (*GetCredentialData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *UpdateCredentialResponse) SetData(v GetCredentialData)`

SetData sets Data field to given value.


### GetSuccess

`func (o *UpdateCredentialResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *UpdateCredentialResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *UpdateCredentialResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


