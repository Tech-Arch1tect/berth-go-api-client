# CreateCredentialResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**GetCredentialData**](GetCredentialData.md) |  | 
**Success** | **bool** |  | 

## Methods

### NewCreateCredentialResponse

`func NewCreateCredentialResponse(data GetCredentialData, success bool, ) *CreateCredentialResponse`

NewCreateCredentialResponse instantiates a new CreateCredentialResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateCredentialResponseWithDefaults

`func NewCreateCredentialResponseWithDefaults() *CreateCredentialResponse`

NewCreateCredentialResponseWithDefaults instantiates a new CreateCredentialResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *CreateCredentialResponse) GetData() GetCredentialData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *CreateCredentialResponse) GetDataOk() (*GetCredentialData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *CreateCredentialResponse) SetData(v GetCredentialData)`

SetData sets Data field to given value.


### GetSuccess

`func (o *CreateCredentialResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *CreateCredentialResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *CreateCredentialResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


