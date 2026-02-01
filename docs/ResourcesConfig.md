# ResourcesConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Limits** | Pointer to [**NullableResourceLimits2**](ResourceLimits2.md) |  | [optional] 
**Reservations** | Pointer to [**NullableResourceLimits2**](ResourceLimits2.md) |  | [optional] 

## Methods

### NewResourcesConfig

`func NewResourcesConfig() *ResourcesConfig`

NewResourcesConfig instantiates a new ResourcesConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResourcesConfigWithDefaults

`func NewResourcesConfigWithDefaults() *ResourcesConfig`

NewResourcesConfigWithDefaults instantiates a new ResourcesConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLimits

`func (o *ResourcesConfig) GetLimits() ResourceLimits2`

GetLimits returns the Limits field if non-nil, zero value otherwise.

### GetLimitsOk

`func (o *ResourcesConfig) GetLimitsOk() (*ResourceLimits2, bool)`

GetLimitsOk returns a tuple with the Limits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimits

`func (o *ResourcesConfig) SetLimits(v ResourceLimits2)`

SetLimits sets Limits field to given value.

### HasLimits

`func (o *ResourcesConfig) HasLimits() bool`

HasLimits returns a boolean if a field has been set.

### SetLimitsNil

`func (o *ResourcesConfig) SetLimitsNil(b bool)`

 SetLimitsNil sets the value for Limits to be an explicit nil

### UnsetLimits
`func (o *ResourcesConfig) UnsetLimits()`

UnsetLimits ensures that no value is present for Limits, not even an explicit nil
### GetReservations

`func (o *ResourcesConfig) GetReservations() ResourceLimits2`

GetReservations returns the Reservations field if non-nil, zero value otherwise.

### GetReservationsOk

`func (o *ResourcesConfig) GetReservationsOk() (*ResourceLimits2, bool)`

GetReservationsOk returns a tuple with the Reservations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReservations

`func (o *ResourcesConfig) SetReservations(v ResourceLimits2)`

SetReservations sets Reservations field to given value.

### HasReservations

`func (o *ResourcesConfig) HasReservations() bool`

HasReservations returns a boolean if a field has been set.

### SetReservationsNil

`func (o *ResourcesConfig) SetReservationsNil(b bool)`

 SetReservationsNil sets the value for Reservations to be an explicit nil

### UnsetReservations
`func (o *ResourcesConfig) UnsetReservations()`

UnsetReservations ensures that no value is present for Reservations, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


