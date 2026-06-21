# ResponseUserIdentity

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**UserIdentity**](UserIdentity.md) |  | 
**Error** | Pointer to [**NullableError**](Error.md) |  | [optional] 
**Meta** | Pointer to [**NullableMeta**](Meta.md) |  | [optional] 
**Success** | **bool** |  | 

## Methods

### NewResponseUserIdentity

`func NewResponseUserIdentity(data UserIdentity, success bool, ) *ResponseUserIdentity`

NewResponseUserIdentity instantiates a new ResponseUserIdentity object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResponseUserIdentityWithDefaults

`func NewResponseUserIdentityWithDefaults() *ResponseUserIdentity`

NewResponseUserIdentityWithDefaults instantiates a new ResponseUserIdentity object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *ResponseUserIdentity) GetData() UserIdentity`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ResponseUserIdentity) GetDataOk() (*UserIdentity, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ResponseUserIdentity) SetData(v UserIdentity)`

SetData sets Data field to given value.


### GetError

`func (o *ResponseUserIdentity) GetError() Error`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ResponseUserIdentity) GetErrorOk() (*Error, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ResponseUserIdentity) SetError(v Error)`

SetError sets Error field to given value.

### HasError

`func (o *ResponseUserIdentity) HasError() bool`

HasError returns a boolean if a field has been set.

### SetErrorNil

`func (o *ResponseUserIdentity) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *ResponseUserIdentity) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetMeta

`func (o *ResponseUserIdentity) GetMeta() Meta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *ResponseUserIdentity) GetMetaOk() (*Meta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *ResponseUserIdentity) SetMeta(v Meta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *ResponseUserIdentity) HasMeta() bool`

HasMeta returns a boolean if a field has been set.

### SetMetaNil

`func (o *ResponseUserIdentity) SetMetaNil(b bool)`

 SetMetaNil sets the value for Meta to be an explicit nil

### UnsetMeta
`func (o *ResponseUserIdentity) UnsetMeta()`

UnsetMeta ensures that no value is present for Meta, not even an explicit nil
### GetSuccess

`func (o *ResponseUserIdentity) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *ResponseUserIdentity) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *ResponseUserIdentity) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


