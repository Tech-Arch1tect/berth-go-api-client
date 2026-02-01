# HealthStatus

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FailingStreak** | Pointer to **int32** |  | [optional] 
**Log** | Pointer to [**[]HealthLog**](HealthLog.md) |  | [optional] 
**Status** | **string** |  | 

## Methods

### NewHealthStatus

`func NewHealthStatus(status string, ) *HealthStatus`

NewHealthStatus instantiates a new HealthStatus object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHealthStatusWithDefaults

`func NewHealthStatusWithDefaults() *HealthStatus`

NewHealthStatusWithDefaults instantiates a new HealthStatus object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFailingStreak

`func (o *HealthStatus) GetFailingStreak() int32`

GetFailingStreak returns the FailingStreak field if non-nil, zero value otherwise.

### GetFailingStreakOk

`func (o *HealthStatus) GetFailingStreakOk() (*int32, bool)`

GetFailingStreakOk returns a tuple with the FailingStreak field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailingStreak

`func (o *HealthStatus) SetFailingStreak(v int32)`

SetFailingStreak sets FailingStreak field to given value.

### HasFailingStreak

`func (o *HealthStatus) HasFailingStreak() bool`

HasFailingStreak returns a boolean if a field has been set.

### GetLog

`func (o *HealthStatus) GetLog() []HealthLog`

GetLog returns the Log field if non-nil, zero value otherwise.

### GetLogOk

`func (o *HealthStatus) GetLogOk() (*[]HealthLog, bool)`

GetLogOk returns a tuple with the Log field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLog

`func (o *HealthStatus) SetLog(v []HealthLog)`

SetLog sets Log field to given value.

### HasLog

`func (o *HealthStatus) HasLog() bool`

HasLog returns a boolean if a field has been set.

### GetStatus

`func (o *HealthStatus) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *HealthStatus) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *HealthStatus) SetStatus(v string)`

SetStatus sets Status field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


