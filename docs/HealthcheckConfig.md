# HealthcheckConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Disable** | Pointer to **bool** |  | [optional] 
**Interval** | Pointer to **string** |  | [optional] 
**Retries** | Pointer to **NullableInt32** |  | [optional] 
**StartInterval** | Pointer to **string** |  | [optional] 
**StartPeriod** | Pointer to **string** |  | [optional] 
**Test** | Pointer to **[]string** |  | [optional] 
**Timeout** | Pointer to **string** |  | [optional] 

## Methods

### NewHealthcheckConfig

`func NewHealthcheckConfig() *HealthcheckConfig`

NewHealthcheckConfig instantiates a new HealthcheckConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHealthcheckConfigWithDefaults

`func NewHealthcheckConfigWithDefaults() *HealthcheckConfig`

NewHealthcheckConfigWithDefaults instantiates a new HealthcheckConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDisable

`func (o *HealthcheckConfig) GetDisable() bool`

GetDisable returns the Disable field if non-nil, zero value otherwise.

### GetDisableOk

`func (o *HealthcheckConfig) GetDisableOk() (*bool, bool)`

GetDisableOk returns a tuple with the Disable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisable

`func (o *HealthcheckConfig) SetDisable(v bool)`

SetDisable sets Disable field to given value.

### HasDisable

`func (o *HealthcheckConfig) HasDisable() bool`

HasDisable returns a boolean if a field has been set.

### GetInterval

`func (o *HealthcheckConfig) GetInterval() string`

GetInterval returns the Interval field if non-nil, zero value otherwise.

### GetIntervalOk

`func (o *HealthcheckConfig) GetIntervalOk() (*string, bool)`

GetIntervalOk returns a tuple with the Interval field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterval

`func (o *HealthcheckConfig) SetInterval(v string)`

SetInterval sets Interval field to given value.

### HasInterval

`func (o *HealthcheckConfig) HasInterval() bool`

HasInterval returns a boolean if a field has been set.

### GetRetries

`func (o *HealthcheckConfig) GetRetries() int32`

GetRetries returns the Retries field if non-nil, zero value otherwise.

### GetRetriesOk

`func (o *HealthcheckConfig) GetRetriesOk() (*int32, bool)`

GetRetriesOk returns a tuple with the Retries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetries

`func (o *HealthcheckConfig) SetRetries(v int32)`

SetRetries sets Retries field to given value.

### HasRetries

`func (o *HealthcheckConfig) HasRetries() bool`

HasRetries returns a boolean if a field has been set.

### SetRetriesNil

`func (o *HealthcheckConfig) SetRetriesNil(b bool)`

 SetRetriesNil sets the value for Retries to be an explicit nil

### UnsetRetries
`func (o *HealthcheckConfig) UnsetRetries()`

UnsetRetries ensures that no value is present for Retries, not even an explicit nil
### GetStartInterval

`func (o *HealthcheckConfig) GetStartInterval() string`

GetStartInterval returns the StartInterval field if non-nil, zero value otherwise.

### GetStartIntervalOk

`func (o *HealthcheckConfig) GetStartIntervalOk() (*string, bool)`

GetStartIntervalOk returns a tuple with the StartInterval field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartInterval

`func (o *HealthcheckConfig) SetStartInterval(v string)`

SetStartInterval sets StartInterval field to given value.

### HasStartInterval

`func (o *HealthcheckConfig) HasStartInterval() bool`

HasStartInterval returns a boolean if a field has been set.

### GetStartPeriod

`func (o *HealthcheckConfig) GetStartPeriod() string`

GetStartPeriod returns the StartPeriod field if non-nil, zero value otherwise.

### GetStartPeriodOk

`func (o *HealthcheckConfig) GetStartPeriodOk() (*string, bool)`

GetStartPeriodOk returns a tuple with the StartPeriod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartPeriod

`func (o *HealthcheckConfig) SetStartPeriod(v string)`

SetStartPeriod sets StartPeriod field to given value.

### HasStartPeriod

`func (o *HealthcheckConfig) HasStartPeriod() bool`

HasStartPeriod returns a boolean if a field has been set.

### GetTest

`func (o *HealthcheckConfig) GetTest() []string`

GetTest returns the Test field if non-nil, zero value otherwise.

### GetTestOk

`func (o *HealthcheckConfig) GetTestOk() (*[]string, bool)`

GetTestOk returns a tuple with the Test field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTest

`func (o *HealthcheckConfig) SetTest(v []string)`

SetTest sets Test field to given value.

### HasTest

`func (o *HealthcheckConfig) HasTest() bool`

HasTest returns a boolean if a field has been set.

### GetTimeout

`func (o *HealthcheckConfig) GetTimeout() string`

GetTimeout returns the Timeout field if non-nil, zero value otherwise.

### GetTimeoutOk

`func (o *HealthcheckConfig) GetTimeoutOk() (*string, bool)`

GetTimeoutOk returns a tuple with the Timeout field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeout

`func (o *HealthcheckConfig) SetTimeout(v string)`

SetTimeout sets Timeout field to given value.

### HasTimeout

`func (o *HealthcheckConfig) HasTimeout() bool`

HasTimeout returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


