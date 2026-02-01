# UpdateComposeResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** |  | [optional] 
**ModifiedYaml** | Pointer to **string** |  | [optional] 
**OriginalYaml** | Pointer to **string** |  | [optional] 
**Success** | **bool** |  | 

## Methods

### NewUpdateComposeResponse

`func NewUpdateComposeResponse(success bool, ) *UpdateComposeResponse`

NewUpdateComposeResponse instantiates a new UpdateComposeResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateComposeResponseWithDefaults

`func NewUpdateComposeResponseWithDefaults() *UpdateComposeResponse`

NewUpdateComposeResponseWithDefaults instantiates a new UpdateComposeResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *UpdateComposeResponse) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *UpdateComposeResponse) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *UpdateComposeResponse) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *UpdateComposeResponse) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetModifiedYaml

`func (o *UpdateComposeResponse) GetModifiedYaml() string`

GetModifiedYaml returns the ModifiedYaml field if non-nil, zero value otherwise.

### GetModifiedYamlOk

`func (o *UpdateComposeResponse) GetModifiedYamlOk() (*string, bool)`

GetModifiedYamlOk returns a tuple with the ModifiedYaml field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedYaml

`func (o *UpdateComposeResponse) SetModifiedYaml(v string)`

SetModifiedYaml sets ModifiedYaml field to given value.

### HasModifiedYaml

`func (o *UpdateComposeResponse) HasModifiedYaml() bool`

HasModifiedYaml returns a boolean if a field has been set.

### GetOriginalYaml

`func (o *UpdateComposeResponse) GetOriginalYaml() string`

GetOriginalYaml returns the OriginalYaml field if non-nil, zero value otherwise.

### GetOriginalYamlOk

`func (o *UpdateComposeResponse) GetOriginalYamlOk() (*string, bool)`

GetOriginalYamlOk returns a tuple with the OriginalYaml field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalYaml

`func (o *UpdateComposeResponse) SetOriginalYaml(v string)`

SetOriginalYaml sets OriginalYaml field to given value.

### HasOriginalYaml

`func (o *UpdateComposeResponse) HasOriginalYaml() bool`

HasOriginalYaml returns a boolean if a field has been set.

### GetSuccess

`func (o *UpdateComposeResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *UpdateComposeResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *UpdateComposeResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


