# GetCredentialResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**GetCredentialData**](GetCredentialData.md) |  | 
**Success** | **bool** |  | 

## Methods

### NewGetCredentialResponse

`func NewGetCredentialResponse(data GetCredentialData, success bool, ) *GetCredentialResponse`

NewGetCredentialResponse instantiates a new GetCredentialResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetCredentialResponseWithDefaults

`func NewGetCredentialResponseWithDefaults() *GetCredentialResponse`

NewGetCredentialResponseWithDefaults instantiates a new GetCredentialResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *GetCredentialResponse) GetData() GetCredentialData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetCredentialResponse) GetDataOk() (*GetCredentialData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetCredentialResponse) SetData(v GetCredentialData)`

SetData sets Data field to given value.


### GetSuccess

`func (o *GetCredentialResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *GetCredentialResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *GetCredentialResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


