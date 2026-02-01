# ResourceLimits

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CpuPeriod** | Pointer to **int32** |  | [optional] 
**CpuQuota** | Pointer to **int32** |  | [optional] 
**CpuShares** | Pointer to **int32** |  | [optional] 
**Memory** | Pointer to **int32** |  | [optional] 
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

### GetCpuPeriod

`func (o *ResourceLimits) GetCpuPeriod() int32`

GetCpuPeriod returns the CpuPeriod field if non-nil, zero value otherwise.

### GetCpuPeriodOk

`func (o *ResourceLimits) GetCpuPeriodOk() (*int32, bool)`

GetCpuPeriodOk returns a tuple with the CpuPeriod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCpuPeriod

`func (o *ResourceLimits) SetCpuPeriod(v int32)`

SetCpuPeriod sets CpuPeriod field to given value.

### HasCpuPeriod

`func (o *ResourceLimits) HasCpuPeriod() bool`

HasCpuPeriod returns a boolean if a field has been set.

### GetCpuQuota

`func (o *ResourceLimits) GetCpuQuota() int32`

GetCpuQuota returns the CpuQuota field if non-nil, zero value otherwise.

### GetCpuQuotaOk

`func (o *ResourceLimits) GetCpuQuotaOk() (*int32, bool)`

GetCpuQuotaOk returns a tuple with the CpuQuota field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCpuQuota

`func (o *ResourceLimits) SetCpuQuota(v int32)`

SetCpuQuota sets CpuQuota field to given value.

### HasCpuQuota

`func (o *ResourceLimits) HasCpuQuota() bool`

HasCpuQuota returns a boolean if a field has been set.

### GetCpuShares

`func (o *ResourceLimits) GetCpuShares() int32`

GetCpuShares returns the CpuShares field if non-nil, zero value otherwise.

### GetCpuSharesOk

`func (o *ResourceLimits) GetCpuSharesOk() (*int32, bool)`

GetCpuSharesOk returns a tuple with the CpuShares field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCpuShares

`func (o *ResourceLimits) SetCpuShares(v int32)`

SetCpuShares sets CpuShares field to given value.

### HasCpuShares

`func (o *ResourceLimits) HasCpuShares() bool`

HasCpuShares returns a boolean if a field has been set.

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


