# StackStatistics

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**HealthyStacks** | **int32** |  | 
**TotalStacks** | **int32** |  | 
**UnhealthyStacks** | **int32** |  | 

## Methods

### NewStackStatistics

`func NewStackStatistics(healthyStacks int32, totalStacks int32, unhealthyStacks int32, ) *StackStatistics`

NewStackStatistics instantiates a new StackStatistics object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStackStatisticsWithDefaults

`func NewStackStatisticsWithDefaults() *StackStatistics`

NewStackStatisticsWithDefaults instantiates a new StackStatistics object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHealthyStacks

`func (o *StackStatistics) GetHealthyStacks() int32`

GetHealthyStacks returns the HealthyStacks field if non-nil, zero value otherwise.

### GetHealthyStacksOk

`func (o *StackStatistics) GetHealthyStacksOk() (*int32, bool)`

GetHealthyStacksOk returns a tuple with the HealthyStacks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHealthyStacks

`func (o *StackStatistics) SetHealthyStacks(v int32)`

SetHealthyStacks sets HealthyStacks field to given value.


### GetTotalStacks

`func (o *StackStatistics) GetTotalStacks() int32`

GetTotalStacks returns the TotalStacks field if non-nil, zero value otherwise.

### GetTotalStacksOk

`func (o *StackStatistics) GetTotalStacksOk() (*int32, bool)`

GetTotalStacksOk returns a tuple with the TotalStacks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalStacks

`func (o *StackStatistics) SetTotalStacks(v int32)`

SetTotalStacks sets TotalStacks field to given value.


### GetUnhealthyStacks

`func (o *StackStatistics) GetUnhealthyStacks() int32`

GetUnhealthyStacks returns the UnhealthyStacks field if non-nil, zero value otherwise.

### GetUnhealthyStacksOk

`func (o *StackStatistics) GetUnhealthyStacksOk() (*int32, bool)`

GetUnhealthyStacksOk returns a tuple with the UnhealthyStacks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnhealthyStacks

`func (o *StackStatistics) SetUnhealthyStacks(v int32)`

SetUnhealthyStacks sets UnhealthyStacks field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


