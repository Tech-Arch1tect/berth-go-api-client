# ResponseRebuildResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**RebuildResult**](RebuildResult.md) |  | 
**Error** | Pointer to [**NullableError**](Error.md) |  | [optional] 
**Meta** | Pointer to [**NullableMeta**](Meta.md) |  | [optional] 
**Success** | **bool** |  | 

## Methods

### NewResponseRebuildResult

`func NewResponseRebuildResult(data RebuildResult, success bool, ) *ResponseRebuildResult`

NewResponseRebuildResult instantiates a new ResponseRebuildResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResponseRebuildResultWithDefaults

`func NewResponseRebuildResultWithDefaults() *ResponseRebuildResult`

NewResponseRebuildResultWithDefaults instantiates a new ResponseRebuildResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *ResponseRebuildResult) GetData() RebuildResult`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ResponseRebuildResult) GetDataOk() (*RebuildResult, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ResponseRebuildResult) SetData(v RebuildResult)`

SetData sets Data field to given value.


### GetError

`func (o *ResponseRebuildResult) GetError() Error`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ResponseRebuildResult) GetErrorOk() (*Error, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ResponseRebuildResult) SetError(v Error)`

SetError sets Error field to given value.

### HasError

`func (o *ResponseRebuildResult) HasError() bool`

HasError returns a boolean if a field has been set.

### SetErrorNil

`func (o *ResponseRebuildResult) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *ResponseRebuildResult) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetMeta

`func (o *ResponseRebuildResult) GetMeta() Meta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *ResponseRebuildResult) GetMetaOk() (*Meta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *ResponseRebuildResult) SetMeta(v Meta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *ResponseRebuildResult) HasMeta() bool`

HasMeta returns a boolean if a field has been set.

### SetMetaNil

`func (o *ResponseRebuildResult) SetMetaNil(b bool)`

 SetMetaNil sets the value for Meta to be an explicit nil

### UnsetMeta
`func (o *ResponseRebuildResult) UnsetMeta()`

UnsetMeta ensures that no value is present for Meta, not even an explicit nil
### GetSuccess

`func (o *ResponseRebuildResult) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *ResponseRebuildResult) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *ResponseRebuildResult) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


