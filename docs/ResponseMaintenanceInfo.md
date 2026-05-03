# ResponseMaintenanceInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**MaintenanceInfo**](MaintenanceInfo.md) |  | 
**Error** | Pointer to [**NullableError**](Error.md) |  | [optional] 
**Meta** | Pointer to [**NullableMeta**](Meta.md) |  | [optional] 
**Success** | **bool** |  | 

## Methods

### NewResponseMaintenanceInfo

`func NewResponseMaintenanceInfo(data MaintenanceInfo, success bool, ) *ResponseMaintenanceInfo`

NewResponseMaintenanceInfo instantiates a new ResponseMaintenanceInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResponseMaintenanceInfoWithDefaults

`func NewResponseMaintenanceInfoWithDefaults() *ResponseMaintenanceInfo`

NewResponseMaintenanceInfoWithDefaults instantiates a new ResponseMaintenanceInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *ResponseMaintenanceInfo) GetData() MaintenanceInfo`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ResponseMaintenanceInfo) GetDataOk() (*MaintenanceInfo, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ResponseMaintenanceInfo) SetData(v MaintenanceInfo)`

SetData sets Data field to given value.


### GetError

`func (o *ResponseMaintenanceInfo) GetError() Error`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ResponseMaintenanceInfo) GetErrorOk() (*Error, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ResponseMaintenanceInfo) SetError(v Error)`

SetError sets Error field to given value.

### HasError

`func (o *ResponseMaintenanceInfo) HasError() bool`

HasError returns a boolean if a field has been set.

### SetErrorNil

`func (o *ResponseMaintenanceInfo) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *ResponseMaintenanceInfo) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetMeta

`func (o *ResponseMaintenanceInfo) GetMeta() Meta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *ResponseMaintenanceInfo) GetMetaOk() (*Meta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *ResponseMaintenanceInfo) SetMeta(v Meta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *ResponseMaintenanceInfo) HasMeta() bool`

HasMeta returns a boolean if a field has been set.

### SetMetaNil

`func (o *ResponseMaintenanceInfo) SetMetaNil(b bool)`

 SetMetaNil sets the value for Meta to be an explicit nil

### UnsetMeta
`func (o *ResponseMaintenanceInfo) UnsetMeta()`

UnsetMeta ensures that no value is present for Meta, not even an explicit nil
### GetSuccess

`func (o *ResponseMaintenanceInfo) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *ResponseMaintenanceInfo) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *ResponseMaintenanceInfo) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


