# ResponseAPIKeyScopeInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**[]APIKeyScopeInfo**](APIKeyScopeInfo.md) |  | 
**Error** | Pointer to [**NullableError**](Error.md) |  | [optional] 
**Meta** | Pointer to [**NullableMeta**](Meta.md) |  | [optional] 
**Success** | **bool** |  | 

## Methods

### NewResponseAPIKeyScopeInfo

`func NewResponseAPIKeyScopeInfo(data []APIKeyScopeInfo, success bool, ) *ResponseAPIKeyScopeInfo`

NewResponseAPIKeyScopeInfo instantiates a new ResponseAPIKeyScopeInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResponseAPIKeyScopeInfoWithDefaults

`func NewResponseAPIKeyScopeInfoWithDefaults() *ResponseAPIKeyScopeInfo`

NewResponseAPIKeyScopeInfoWithDefaults instantiates a new ResponseAPIKeyScopeInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *ResponseAPIKeyScopeInfo) GetData() []APIKeyScopeInfo`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ResponseAPIKeyScopeInfo) GetDataOk() (*[]APIKeyScopeInfo, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ResponseAPIKeyScopeInfo) SetData(v []APIKeyScopeInfo)`

SetData sets Data field to given value.


### GetError

`func (o *ResponseAPIKeyScopeInfo) GetError() Error`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ResponseAPIKeyScopeInfo) GetErrorOk() (*Error, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ResponseAPIKeyScopeInfo) SetError(v Error)`

SetError sets Error field to given value.

### HasError

`func (o *ResponseAPIKeyScopeInfo) HasError() bool`

HasError returns a boolean if a field has been set.

### SetErrorNil

`func (o *ResponseAPIKeyScopeInfo) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *ResponseAPIKeyScopeInfo) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetMeta

`func (o *ResponseAPIKeyScopeInfo) GetMeta() Meta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *ResponseAPIKeyScopeInfo) GetMetaOk() (*Meta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *ResponseAPIKeyScopeInfo) SetMeta(v Meta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *ResponseAPIKeyScopeInfo) HasMeta() bool`

HasMeta returns a boolean if a field has been set.

### SetMetaNil

`func (o *ResponseAPIKeyScopeInfo) SetMetaNil(b bool)`

 SetMetaNil sets the value for Meta to be an explicit nil

### UnsetMeta
`func (o *ResponseAPIKeyScopeInfo) UnsetMeta()`

UnsetMeta ensures that no value is present for Meta, not even an explicit nil
### GetSuccess

`func (o *ResponseAPIKeyScopeInfo) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *ResponseAPIKeyScopeInfo) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *ResponseAPIKeyScopeInfo) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


