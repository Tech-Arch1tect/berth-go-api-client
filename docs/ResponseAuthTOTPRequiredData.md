# ResponseAuthTOTPRequiredData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**AuthTOTPRequiredData**](AuthTOTPRequiredData.md) |  | 
**Error** | Pointer to [**NullableError**](Error.md) |  | [optional] 
**Meta** | Pointer to [**NullableMeta**](Meta.md) |  | [optional] 
**Success** | **bool** |  | 

## Methods

### NewResponseAuthTOTPRequiredData

`func NewResponseAuthTOTPRequiredData(data AuthTOTPRequiredData, success bool, ) *ResponseAuthTOTPRequiredData`

NewResponseAuthTOTPRequiredData instantiates a new ResponseAuthTOTPRequiredData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResponseAuthTOTPRequiredDataWithDefaults

`func NewResponseAuthTOTPRequiredDataWithDefaults() *ResponseAuthTOTPRequiredData`

NewResponseAuthTOTPRequiredDataWithDefaults instantiates a new ResponseAuthTOTPRequiredData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *ResponseAuthTOTPRequiredData) GetData() AuthTOTPRequiredData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ResponseAuthTOTPRequiredData) GetDataOk() (*AuthTOTPRequiredData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ResponseAuthTOTPRequiredData) SetData(v AuthTOTPRequiredData)`

SetData sets Data field to given value.


### GetError

`func (o *ResponseAuthTOTPRequiredData) GetError() Error`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ResponseAuthTOTPRequiredData) GetErrorOk() (*Error, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ResponseAuthTOTPRequiredData) SetError(v Error)`

SetError sets Error field to given value.

### HasError

`func (o *ResponseAuthTOTPRequiredData) HasError() bool`

HasError returns a boolean if a field has been set.

### SetErrorNil

`func (o *ResponseAuthTOTPRequiredData) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *ResponseAuthTOTPRequiredData) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetMeta

`func (o *ResponseAuthTOTPRequiredData) GetMeta() Meta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *ResponseAuthTOTPRequiredData) GetMetaOk() (*Meta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *ResponseAuthTOTPRequiredData) SetMeta(v Meta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *ResponseAuthTOTPRequiredData) HasMeta() bool`

HasMeta returns a boolean if a field has been set.

### SetMetaNil

`func (o *ResponseAuthTOTPRequiredData) SetMetaNil(b bool)`

 SetMetaNil sets the value for Meta to be an explicit nil

### UnsetMeta
`func (o *ResponseAuthTOTPRequiredData) UnsetMeta()`

UnsetMeta ensures that no value is present for Meta, not even an explicit nil
### GetSuccess

`func (o *ResponseAuthTOTPRequiredData) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *ResponseAuthTOTPRequiredData) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *ResponseAuthTOTPRequiredData) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


