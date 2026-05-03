# ResponseListRoleStackPermissionsData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**ListRoleStackPermissionsData**](ListRoleStackPermissionsData.md) |  | 
**Error** | Pointer to [**NullableError**](Error.md) |  | [optional] 
**Meta** | Pointer to [**NullableMeta**](Meta.md) |  | [optional] 
**Success** | **bool** |  | 

## Methods

### NewResponseListRoleStackPermissionsData

`func NewResponseListRoleStackPermissionsData(data ListRoleStackPermissionsData, success bool, ) *ResponseListRoleStackPermissionsData`

NewResponseListRoleStackPermissionsData instantiates a new ResponseListRoleStackPermissionsData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResponseListRoleStackPermissionsDataWithDefaults

`func NewResponseListRoleStackPermissionsDataWithDefaults() *ResponseListRoleStackPermissionsData`

NewResponseListRoleStackPermissionsDataWithDefaults instantiates a new ResponseListRoleStackPermissionsData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *ResponseListRoleStackPermissionsData) GetData() ListRoleStackPermissionsData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ResponseListRoleStackPermissionsData) GetDataOk() (*ListRoleStackPermissionsData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ResponseListRoleStackPermissionsData) SetData(v ListRoleStackPermissionsData)`

SetData sets Data field to given value.


### GetError

`func (o *ResponseListRoleStackPermissionsData) GetError() Error`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ResponseListRoleStackPermissionsData) GetErrorOk() (*Error, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ResponseListRoleStackPermissionsData) SetError(v Error)`

SetError sets Error field to given value.

### HasError

`func (o *ResponseListRoleStackPermissionsData) HasError() bool`

HasError returns a boolean if a field has been set.

### SetErrorNil

`func (o *ResponseListRoleStackPermissionsData) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *ResponseListRoleStackPermissionsData) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetMeta

`func (o *ResponseListRoleStackPermissionsData) GetMeta() Meta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *ResponseListRoleStackPermissionsData) GetMetaOk() (*Meta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *ResponseListRoleStackPermissionsData) SetMeta(v Meta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *ResponseListRoleStackPermissionsData) HasMeta() bool`

HasMeta returns a boolean if a field has been set.

### SetMetaNil

`func (o *ResponseListRoleStackPermissionsData) SetMetaNil(b bool)`

 SetMetaNil sets the value for Meta to be an explicit nil

### UnsetMeta
`func (o *ResponseListRoleStackPermissionsData) UnsetMeta()`

UnsetMeta ensures that no value is present for Meta, not even an explicit nil
### GetSuccess

`func (o *ResponseListRoleStackPermissionsData) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *ResponseListRoleStackPermissionsData) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *ResponseListRoleStackPermissionsData) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


