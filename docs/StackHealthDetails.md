# StackHealthDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**HealthyCount** | **int32** |  | 
**Percentage** | **int32** |  | 
**Reasons** | **[]string** |  | 
**StoppedCount** | **int32** |  | 
**UnhealthyCount** | **int32** |  | 

## Methods

### NewStackHealthDetails

`func NewStackHealthDetails(healthyCount int32, percentage int32, reasons []string, stoppedCount int32, unhealthyCount int32, ) *StackHealthDetails`

NewStackHealthDetails instantiates a new StackHealthDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStackHealthDetailsWithDefaults

`func NewStackHealthDetailsWithDefaults() *StackHealthDetails`

NewStackHealthDetailsWithDefaults instantiates a new StackHealthDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHealthyCount

`func (o *StackHealthDetails) GetHealthyCount() int32`

GetHealthyCount returns the HealthyCount field if non-nil, zero value otherwise.

### GetHealthyCountOk

`func (o *StackHealthDetails) GetHealthyCountOk() (*int32, bool)`

GetHealthyCountOk returns a tuple with the HealthyCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHealthyCount

`func (o *StackHealthDetails) SetHealthyCount(v int32)`

SetHealthyCount sets HealthyCount field to given value.


### GetPercentage

`func (o *StackHealthDetails) GetPercentage() int32`

GetPercentage returns the Percentage field if non-nil, zero value otherwise.

### GetPercentageOk

`func (o *StackHealthDetails) GetPercentageOk() (*int32, bool)`

GetPercentageOk returns a tuple with the Percentage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPercentage

`func (o *StackHealthDetails) SetPercentage(v int32)`

SetPercentage sets Percentage field to given value.


### GetReasons

`func (o *StackHealthDetails) GetReasons() []string`

GetReasons returns the Reasons field if non-nil, zero value otherwise.

### GetReasonsOk

`func (o *StackHealthDetails) GetReasonsOk() (*[]string, bool)`

GetReasonsOk returns a tuple with the Reasons field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReasons

`func (o *StackHealthDetails) SetReasons(v []string)`

SetReasons sets Reasons field to given value.


### GetStoppedCount

`func (o *StackHealthDetails) GetStoppedCount() int32`

GetStoppedCount returns the StoppedCount field if non-nil, zero value otherwise.

### GetStoppedCountOk

`func (o *StackHealthDetails) GetStoppedCountOk() (*int32, bool)`

GetStoppedCountOk returns a tuple with the StoppedCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStoppedCount

`func (o *StackHealthDetails) SetStoppedCount(v int32)`

SetStoppedCount sets StoppedCount field to given value.


### GetUnhealthyCount

`func (o *StackHealthDetails) GetUnhealthyCount() int32`

GetUnhealthyCount returns the UnhealthyCount field if non-nil, zero value otherwise.

### GetUnhealthyCountOk

`func (o *StackHealthDetails) GetUnhealthyCountOk() (*int32, bool)`

GetUnhealthyCountOk returns a tuple with the UnhealthyCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnhealthyCount

`func (o *StackHealthDetails) SetUnhealthyCount(v int32)`

SetUnhealthyCount sets UnhealthyCount field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


