# ResourceLimits

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CpuCores** | Pointer to **float32** |  | [optional] 
**Memory** | Pointer to **int32** |  | [optional] 
**MemoryReservation** | Pointer to **int32** |  | [optional] 
**MemorySwap** | Pointer to **int32** |  | [optional] 

## Methods

### NewResourceLimits

`func NewResourceLimits() *ResourceLimits`

NewResourceLimits instantiates a new ResourceLimits object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResourceLimitsWithDefaults

`func NewResourceLimitsWithDefaults() *ResourceLimits`

NewResourceLimitsWithDefaults instantiates a new ResourceLimits object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCpuCores

`func (o *ResourceLimits) GetCpuCores() float32`

GetCpuCores returns the CpuCores field if non-nil, zero value otherwise.

### GetCpuCoresOk

`func (o *ResourceLimits) GetCpuCoresOk() (*float32, bool)`

GetCpuCoresOk returns a tuple with the CpuCores field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCpuCores

`func (o *ResourceLimits) SetCpuCores(v float32)`

SetCpuCores sets CpuCores field to given value.

### HasCpuCores

`func (o *ResourceLimits) HasCpuCores() bool`

HasCpuCores returns a boolean if a field has been set.

### GetMemory

`func (o *ResourceLimits) GetMemory() int32`

GetMemory returns the Memory field if non-nil, zero value otherwise.

### GetMemoryOk

`func (o *ResourceLimits) GetMemoryOk() (*int32, bool)`

GetMemoryOk returns a tuple with the Memory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemory

`func (o *ResourceLimits) SetMemory(v int32)`

SetMemory sets Memory field to given value.

### HasMemory

`func (o *ResourceLimits) HasMemory() bool`

HasMemory returns a boolean if a field has been set.

### GetMemoryReservation

`func (o *ResourceLimits) GetMemoryReservation() int32`

GetMemoryReservation returns the MemoryReservation field if non-nil, zero value otherwise.

### GetMemoryReservationOk

`func (o *ResourceLimits) GetMemoryReservationOk() (*int32, bool)`

GetMemoryReservationOk returns a tuple with the MemoryReservation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemoryReservation

`func (o *ResourceLimits) SetMemoryReservation(v int32)`

SetMemoryReservation sets MemoryReservation field to given value.

### HasMemoryReservation

`func (o *ResourceLimits) HasMemoryReservation() bool`

HasMemoryReservation returns a boolean if a field has been set.

### GetMemorySwap

`func (o *ResourceLimits) GetMemorySwap() int32`

GetMemorySwap returns the MemorySwap field if non-nil, zero value otherwise.

### GetMemorySwapOk

`func (o *ResourceLimits) GetMemorySwapOk() (*int32, bool)`

GetMemorySwapOk returns a tuple with the MemorySwap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemorySwap

`func (o *ResourceLimits) SetMemorySwap(v int32)`

SetMemorySwap sets MemorySwap field to given value.

### HasMemorySwap

`func (o *ResourceLimits) HasMemorySwap() bool`

HasMemorySwap returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


