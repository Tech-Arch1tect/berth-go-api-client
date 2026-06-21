# ApiV1ProfileGet200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**UserIdentity**](UserIdentity.md) |  | 
**Error** | Pointer to [**NullableError**](Error.md) |  | [optional] 
**Meta** | Pointer to [**NullableMeta**](Meta.md) |  | [optional] 
**Success** | **bool** |  | 

## Methods

### NewApiV1ProfileGet200Response

`func NewApiV1ProfileGet200Response(data UserIdentity, success bool, ) *ApiV1ProfileGet200Response`

NewApiV1ProfileGet200Response instantiates a new ApiV1ProfileGet200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApiV1ProfileGet200ResponseWithDefaults

`func NewApiV1ProfileGet200ResponseWithDefaults() *ApiV1ProfileGet200Response`

NewApiV1ProfileGet200ResponseWithDefaults instantiates a new ApiV1ProfileGet200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *ApiV1ProfileGet200Response) GetData() UserIdentity`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ApiV1ProfileGet200Response) GetDataOk() (*UserIdentity, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ApiV1ProfileGet200Response) SetData(v UserIdentity)`

SetData sets Data field to given value.


### GetError

`func (o *ApiV1ProfileGet200Response) GetError() Error`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ApiV1ProfileGet200Response) GetErrorOk() (*Error, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ApiV1ProfileGet200Response) SetError(v Error)`

SetError sets Error field to given value.

### HasError

`func (o *ApiV1ProfileGet200Response) HasError() bool`

HasError returns a boolean if a field has been set.

### SetErrorNil

`func (o *ApiV1ProfileGet200Response) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *ApiV1ProfileGet200Response) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetMeta

`func (o *ApiV1ProfileGet200Response) GetMeta() Meta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *ApiV1ProfileGet200Response) GetMetaOk() (*Meta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *ApiV1ProfileGet200Response) SetMeta(v Meta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *ApiV1ProfileGet200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.

### SetMetaNil

`func (o *ApiV1ProfileGet200Response) SetMetaNil(b bool)`

 SetMetaNil sets the value for Meta to be an explicit nil

### UnsetMeta
`func (o *ApiV1ProfileGet200Response) UnsetMeta()`

UnsetMeta ensures that no value is present for Meta, not even an explicit nil
### GetSuccess

`func (o *ApiV1ProfileGet200Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *ApiV1ProfileGet200Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *ApiV1ProfileGet200Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


