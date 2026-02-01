# UpdateRollbackConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Delay** | Pointer to **string** |  | [optional] 
**FailureAction** | Pointer to **string** |  | [optional] 
**MaxFailureRatio** | Pointer to **float32** |  | [optional] 
**Monitor** | Pointer to **string** |  | [optional] 
**Order** | Pointer to **string** |  | [optional] 
**Parallelism** | Pointer to **NullableInt32** |  | [optional] 

## Methods

### NewUpdateRollbackConfig

`func NewUpdateRollbackConfig() *UpdateRollbackConfig`

NewUpdateRollbackConfig instantiates a new UpdateRollbackConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateRollbackConfigWithDefaults

`func NewUpdateRollbackConfigWithDefaults() *UpdateRollbackConfig`

NewUpdateRollbackConfigWithDefaults instantiates a new UpdateRollbackConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDelay

`func (o *UpdateRollbackConfig) GetDelay() string`

GetDelay returns the Delay field if non-nil, zero value otherwise.

### GetDelayOk

`func (o *UpdateRollbackConfig) GetDelayOk() (*string, bool)`

GetDelayOk returns a tuple with the Delay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelay

`func (o *UpdateRollbackConfig) SetDelay(v string)`

SetDelay sets Delay field to given value.

### HasDelay

`func (o *UpdateRollbackConfig) HasDelay() bool`

HasDelay returns a boolean if a field has been set.

### GetFailureAction

`func (o *UpdateRollbackConfig) GetFailureAction() string`

GetFailureAction returns the FailureAction field if non-nil, zero value otherwise.

### GetFailureActionOk

`func (o *UpdateRollbackConfig) GetFailureActionOk() (*string, bool)`

GetFailureActionOk returns a tuple with the FailureAction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureAction

`func (o *UpdateRollbackConfig) SetFailureAction(v string)`

SetFailureAction sets FailureAction field to given value.

### HasFailureAction

`func (o *UpdateRollbackConfig) HasFailureAction() bool`

HasFailureAction returns a boolean if a field has been set.

### GetMaxFailureRatio

`func (o *UpdateRollbackConfig) GetMaxFailureRatio() float32`

GetMaxFailureRatio returns the MaxFailureRatio field if non-nil, zero value otherwise.

### GetMaxFailureRatioOk

`func (o *UpdateRollbackConfig) GetMaxFailureRatioOk() (*float32, bool)`

GetMaxFailureRatioOk returns a tuple with the MaxFailureRatio field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxFailureRatio

`func (o *UpdateRollbackConfig) SetMaxFailureRatio(v float32)`

SetMaxFailureRatio sets MaxFailureRatio field to given value.

### HasMaxFailureRatio

`func (o *UpdateRollbackConfig) HasMaxFailureRatio() bool`

HasMaxFailureRatio returns a boolean if a field has been set.

### GetMonitor

`func (o *UpdateRollbackConfig) GetMonitor() string`

GetMonitor returns the Monitor field if non-nil, zero value otherwise.

### GetMonitorOk

`func (o *UpdateRollbackConfig) GetMonitorOk() (*string, bool)`

GetMonitorOk returns a tuple with the Monitor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonitor

`func (o *UpdateRollbackConfig) SetMonitor(v string)`

SetMonitor sets Monitor field to given value.

### HasMonitor

`func (o *UpdateRollbackConfig) HasMonitor() bool`

HasMonitor returns a boolean if a field has been set.

### GetOrder

`func (o *UpdateRollbackConfig) GetOrder() string`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *UpdateRollbackConfig) GetOrderOk() (*string, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *UpdateRollbackConfig) SetOrder(v string)`

SetOrder sets Order field to given value.

### HasOrder

`func (o *UpdateRollbackConfig) HasOrder() bool`

HasOrder returns a boolean if a field has been set.

### GetParallelism

`func (o *UpdateRollbackConfig) GetParallelism() int32`

GetParallelism returns the Parallelism field if non-nil, zero value otherwise.

### GetParallelismOk

`func (o *UpdateRollbackConfig) GetParallelismOk() (*int32, bool)`

GetParallelismOk returns a tuple with the Parallelism field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParallelism

`func (o *UpdateRollbackConfig) SetParallelism(v int32)`

SetParallelism sets Parallelism field to given value.

### HasParallelism

`func (o *UpdateRollbackConfig) HasParallelism() bool`

HasParallelism returns a boolean if a field has been set.

### SetParallelismNil

`func (o *UpdateRollbackConfig) SetParallelismNil(b bool)`

 SetParallelismNil sets the value for Parallelism to be an explicit nil

### UnsetParallelism
`func (o *UpdateRollbackConfig) UnsetParallelism()`

UnsetParallelism ensures that no value is present for Parallelism, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


