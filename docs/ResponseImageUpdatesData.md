# ResponseImageUpdatesData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**ImageUpdatesData**](ImageUpdatesData.md) |  | 
**Error** | Pointer to [**NullableError**](Error.md) |  | [optional] 
**Meta** | Pointer to [**NullableMeta**](Meta.md) |  | [optional] 
**Success** | **bool** |  | 

## Methods

### NewResponseImageUpdatesData

`func NewResponseImageUpdatesData(data ImageUpdatesData, success bool, ) *ResponseImageUpdatesData`

NewResponseImageUpdatesData instantiates a new ResponseImageUpdatesData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResponseImageUpdatesDataWithDefaults

`func NewResponseImageUpdatesDataWithDefaults() *ResponseImageUpdatesData`

NewResponseImageUpdatesDataWithDefaults instantiates a new ResponseImageUpdatesData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *ResponseImageUpdatesData) GetData() ImageUpdatesData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ResponseImageUpdatesData) GetDataOk() (*ImageUpdatesData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ResponseImageUpdatesData) SetData(v ImageUpdatesData)`

SetData sets Data field to given value.


### GetError

`func (o *ResponseImageUpdatesData) GetError() Error`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ResponseImageUpdatesData) GetErrorOk() (*Error, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ResponseImageUpdatesData) SetError(v Error)`

SetError sets Error field to given value.

### HasError

`func (o *ResponseImageUpdatesData) HasError() bool`

HasError returns a boolean if a field has been set.

### SetErrorNil

`func (o *ResponseImageUpdatesData) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *ResponseImageUpdatesData) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetMeta

`func (o *ResponseImageUpdatesData) GetMeta() Meta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *ResponseImageUpdatesData) GetMetaOk() (*Meta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *ResponseImageUpdatesData) SetMeta(v Meta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *ResponseImageUpdatesData) HasMeta() bool`

HasMeta returns a boolean if a field has been set.

### SetMetaNil

`func (o *ResponseImageUpdatesData) SetMetaNil(b bool)`

 SetMetaNil sets the value for Meta to be an explicit nil

### UnsetMeta
`func (o *ResponseImageUpdatesData) UnsetMeta()`

UnsetMeta ensures that no value is present for Meta, not even an explicit nil
### GetSuccess

`func (o *ResponseImageUpdatesData) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *ResponseImageUpdatesData) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *ResponseImageUpdatesData) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


