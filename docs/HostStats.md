# HostStats

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CpuCores** | **int32** |  | 
**Load1** | **float32** |  | 
**Load15** | **float32** |  | 
**Load5** | **float32** |  | 
**MemoryAvailable** | **int32** |  | 
**MemoryTotal** | **int32** |  | 

## Methods

### NewHostStats

`func NewHostStats(cpuCores int32, load1 float32, load15 float32, load5 float32, memoryAvailable int32, memoryTotal int32, ) *HostStats`

NewHostStats instantiates a new HostStats object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHostStatsWithDefaults

`func NewHostStatsWithDefaults() *HostStats`

NewHostStatsWithDefaults instantiates a new HostStats object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCpuCores

`func (o *HostStats) GetCpuCores() int32`

GetCpuCores returns the CpuCores field if non-nil, zero value otherwise.

### GetCpuCoresOk

`func (o *HostStats) GetCpuCoresOk() (*int32, bool)`

GetCpuCoresOk returns a tuple with the CpuCores field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCpuCores

`func (o *HostStats) SetCpuCores(v int32)`

SetCpuCores sets CpuCores field to given value.


### GetLoad1

`func (o *HostStats) GetLoad1() float32`

GetLoad1 returns the Load1 field if non-nil, zero value otherwise.

### GetLoad1Ok

`func (o *HostStats) GetLoad1Ok() (*float32, bool)`

GetLoad1Ok returns a tuple with the Load1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoad1

`func (o *HostStats) SetLoad1(v float32)`

SetLoad1 sets Load1 field to given value.


### GetLoad15

`func (o *HostStats) GetLoad15() float32`

GetLoad15 returns the Load15 field if non-nil, zero value otherwise.

### GetLoad15Ok

`func (o *HostStats) GetLoad15Ok() (*float32, bool)`

GetLoad15Ok returns a tuple with the Load15 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoad15

`func (o *HostStats) SetLoad15(v float32)`

SetLoad15 sets Load15 field to given value.


### GetLoad5

`func (o *HostStats) GetLoad5() float32`

GetLoad5 returns the Load5 field if non-nil, zero value otherwise.

### GetLoad5Ok

`func (o *HostStats) GetLoad5Ok() (*float32, bool)`

GetLoad5Ok returns a tuple with the Load5 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoad5

`func (o *HostStats) SetLoad5(v float32)`

SetLoad5 sets Load5 field to given value.


### GetMemoryAvailable

`func (o *HostStats) GetMemoryAvailable() int32`

GetMemoryAvailable returns the MemoryAvailable field if non-nil, zero value otherwise.

### GetMemoryAvailableOk

`func (o *HostStats) GetMemoryAvailableOk() (*int32, bool)`

GetMemoryAvailableOk returns a tuple with the MemoryAvailable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemoryAvailable

`func (o *HostStats) SetMemoryAvailable(v int32)`

SetMemoryAvailable sets MemoryAvailable field to given value.


### GetMemoryTotal

`func (o *HostStats) GetMemoryTotal() int32`

GetMemoryTotal returns the MemoryTotal field if non-nil, zero value otherwise.

### GetMemoryTotalOk

`func (o *HostStats) GetMemoryTotalOk() (*int32, bool)`

GetMemoryTotalOk returns a tuple with the MemoryTotal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemoryTotal

`func (o *HostStats) SetMemoryTotal(v int32)`

SetMemoryTotal sets MemoryTotal field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


