# DependsOnConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Condition** | Pointer to **string** |  | [optional] 
**Required** | Pointer to **bool** |  | [optional] 
**Restart** | Pointer to **bool** |  | [optional] 

## Methods

### NewDependsOnConfig

`func NewDependsOnConfig() *DependsOnConfig`

NewDependsOnConfig instantiates a new DependsOnConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDependsOnConfigWithDefaults

`func NewDependsOnConfigWithDefaults() *DependsOnConfig`

NewDependsOnConfigWithDefaults instantiates a new DependsOnConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCondition

`func (o *DependsOnConfig) GetCondition() string`

GetCondition returns the Condition field if non-nil, zero value otherwise.

### GetConditionOk

`func (o *DependsOnConfig) GetConditionOk() (*string, bool)`

GetConditionOk returns a tuple with the Condition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCondition

`func (o *DependsOnConfig) SetCondition(v string)`

SetCondition sets Condition field to given value.

### HasCondition

`func (o *DependsOnConfig) HasCondition() bool`

HasCondition returns a boolean if a field has been set.

### GetRequired

`func (o *DependsOnConfig) GetRequired() bool`

GetRequired returns the Required field if non-nil, zero value otherwise.

### GetRequiredOk

`func (o *DependsOnConfig) GetRequiredOk() (*bool, bool)`

GetRequiredOk returns a tuple with the Required field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequired

`func (o *DependsOnConfig) SetRequired(v bool)`

SetRequired sets Required field to given value.

### HasRequired

`func (o *DependsOnConfig) HasRequired() bool`

HasRequired returns a boolean if a field has been set.

### GetRestart

`func (o *DependsOnConfig) GetRestart() bool`

GetRestart returns the Restart field if non-nil, zero value otherwise.

### GetRestartOk

`func (o *DependsOnConfig) GetRestartOk() (*bool, bool)`

GetRestartOk returns a tuple with the Restart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRestart

`func (o *DependsOnConfig) SetRestart(v bool)`

SetRestart sets Restart field to given value.

### HasRestart

`func (o *DependsOnConfig) HasRestart() bool`

HasRestart returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


