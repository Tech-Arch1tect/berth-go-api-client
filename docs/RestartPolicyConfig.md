# RestartPolicyConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Condition** | Pointer to **string** |  | [optional] 
**Delay** | Pointer to **string** |  | [optional] 
**MaxAttempts** | Pointer to **NullableInt32** |  | [optional] 
**Window** | Pointer to **string** |  | [optional] 

## Methods

### NewRestartPolicyConfig

`func NewRestartPolicyConfig() *RestartPolicyConfig`

NewRestartPolicyConfig instantiates a new RestartPolicyConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRestartPolicyConfigWithDefaults

`func NewRestartPolicyConfigWithDefaults() *RestartPolicyConfig`

NewRestartPolicyConfigWithDefaults instantiates a new RestartPolicyConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCondition

`func (o *RestartPolicyConfig) GetCondition() string`

GetCondition returns the Condition field if non-nil, zero value otherwise.

### GetConditionOk

`func (o *RestartPolicyConfig) GetConditionOk() (*string, bool)`

GetConditionOk returns a tuple with the Condition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCondition

`func (o *RestartPolicyConfig) SetCondition(v string)`

SetCondition sets Condition field to given value.

### HasCondition

`func (o *RestartPolicyConfig) HasCondition() bool`

HasCondition returns a boolean if a field has been set.

### GetDelay

`func (o *RestartPolicyConfig) GetDelay() string`

GetDelay returns the Delay field if non-nil, zero value otherwise.

### GetDelayOk

`func (o *RestartPolicyConfig) GetDelayOk() (*string, bool)`

GetDelayOk returns a tuple with the Delay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelay

`func (o *RestartPolicyConfig) SetDelay(v string)`

SetDelay sets Delay field to given value.

### HasDelay

`func (o *RestartPolicyConfig) HasDelay() bool`

HasDelay returns a boolean if a field has been set.

### GetMaxAttempts

`func (o *RestartPolicyConfig) GetMaxAttempts() int32`

GetMaxAttempts returns the MaxAttempts field if non-nil, zero value otherwise.

### GetMaxAttemptsOk

`func (o *RestartPolicyConfig) GetMaxAttemptsOk() (*int32, bool)`

GetMaxAttemptsOk returns a tuple with the MaxAttempts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxAttempts

`func (o *RestartPolicyConfig) SetMaxAttempts(v int32)`

SetMaxAttempts sets MaxAttempts field to given value.

### HasMaxAttempts

`func (o *RestartPolicyConfig) HasMaxAttempts() bool`

HasMaxAttempts returns a boolean if a field has been set.

### SetMaxAttemptsNil

`func (o *RestartPolicyConfig) SetMaxAttemptsNil(b bool)`

 SetMaxAttemptsNil sets the value for MaxAttempts to be an explicit nil

### UnsetMaxAttempts
`func (o *RestartPolicyConfig) UnsetMaxAttempts()`

UnsetMaxAttempts ensures that no value is present for MaxAttempts, not even an explicit nil
### GetWindow

`func (o *RestartPolicyConfig) GetWindow() string`

GetWindow returns the Window field if non-nil, zero value otherwise.

### GetWindowOk

`func (o *RestartPolicyConfig) GetWindowOk() (*string, bool)`

GetWindowOk returns a tuple with the Window field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWindow

`func (o *RestartPolicyConfig) SetWindow(v string)`

SetWindow sets Window field to given value.

### HasWindow

`func (o *RestartPolicyConfig) HasWindow() bool`

HasWindow returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


