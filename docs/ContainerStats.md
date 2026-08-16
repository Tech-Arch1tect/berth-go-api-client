# ContainerStats

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BlockReadBytes** | **int32** |  | 
**BlockReadBytesPerSecond** | **NullableFloat32** |  | 
**BlockReadOps** | **int32** |  | 
**BlockWriteBytes** | **int32** |  | 
**BlockWriteBytesPerSecond** | **NullableFloat32** |  | 
**BlockWriteOps** | **int32** |  | 
**CpuPercentOfHost** | **NullableFloat32** |  | 
**CpuPercentOfQuota** | **NullableFloat32** |  | 
**CpuQuotaCores** | **float32** |  | 
**CpuSystemTime** | **int32** |  | 
**CpuThrottledPercent** | **NullableFloat32** |  | 
**CpuUsageCores** | **NullableFloat32** |  | 
**CpuUserTime** | **int32** |  | 
**MemoryAnon** | **int32** |  | 
**MemoryCurrent** | **int32** |  | 
**MemoryFile** | **int32** |  | 
**MemoryInactiveFile** | **int32** |  | 
**MemoryLimit** | **int32** |  | 
**MemoryLimitHits** | **int32** |  | 
**MemoryPeak** | **int32** |  | 
**MemoryPercentOfHost** | **NullableFloat32** |  | 
**MemoryPercentOfLimit** | **NullableFloat32** |  | 
**MemorySwap** | **int32** |  | 
**MemoryWorkingSet** | **int32** |  | 
**Name** | **string** |  | 
**NetworkRxBytes** | **int32** |  | 
**NetworkRxBytesPerSecond** | **NullableFloat32** |  | 
**NetworkRxPackets** | **int32** |  | 
**NetworkTxBytes** | **int32** |  | 
**NetworkTxBytesPerSecond** | **NullableFloat32** |  | 
**NetworkTxPackets** | **int32** |  | 
**OomKills** | **int32** |  | 
**PageFaults** | **int32** |  | 
**PageMajorFaults** | **int32** |  | 
**ServiceName** | **string** |  | 
**State** | **string** |  | 

## Methods

### NewContainerStats

`func NewContainerStats(blockReadBytes int32, blockReadBytesPerSecond NullableFloat32, blockReadOps int32, blockWriteBytes int32, blockWriteBytesPerSecond NullableFloat32, blockWriteOps int32, cpuPercentOfHost NullableFloat32, cpuPercentOfQuota NullableFloat32, cpuQuotaCores float32, cpuSystemTime int32, cpuThrottledPercent NullableFloat32, cpuUsageCores NullableFloat32, cpuUserTime int32, memoryAnon int32, memoryCurrent int32, memoryFile int32, memoryInactiveFile int32, memoryLimit int32, memoryLimitHits int32, memoryPeak int32, memoryPercentOfHost NullableFloat32, memoryPercentOfLimit NullableFloat32, memorySwap int32, memoryWorkingSet int32, name string, networkRxBytes int32, networkRxBytesPerSecond NullableFloat32, networkRxPackets int32, networkTxBytes int32, networkTxBytesPerSecond NullableFloat32, networkTxPackets int32, oomKills int32, pageFaults int32, pageMajorFaults int32, serviceName string, state string, ) *ContainerStats`

NewContainerStats instantiates a new ContainerStats object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContainerStatsWithDefaults

`func NewContainerStatsWithDefaults() *ContainerStats`

NewContainerStatsWithDefaults instantiates a new ContainerStats object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBlockReadBytes

`func (o *ContainerStats) GetBlockReadBytes() int32`

GetBlockReadBytes returns the BlockReadBytes field if non-nil, zero value otherwise.

### GetBlockReadBytesOk

`func (o *ContainerStats) GetBlockReadBytesOk() (*int32, bool)`

GetBlockReadBytesOk returns a tuple with the BlockReadBytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlockReadBytes

`func (o *ContainerStats) SetBlockReadBytes(v int32)`

SetBlockReadBytes sets BlockReadBytes field to given value.


### GetBlockReadBytesPerSecond

`func (o *ContainerStats) GetBlockReadBytesPerSecond() float32`

GetBlockReadBytesPerSecond returns the BlockReadBytesPerSecond field if non-nil, zero value otherwise.

### GetBlockReadBytesPerSecondOk

`func (o *ContainerStats) GetBlockReadBytesPerSecondOk() (*float32, bool)`

GetBlockReadBytesPerSecondOk returns a tuple with the BlockReadBytesPerSecond field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlockReadBytesPerSecond

`func (o *ContainerStats) SetBlockReadBytesPerSecond(v float32)`

SetBlockReadBytesPerSecond sets BlockReadBytesPerSecond field to given value.


### SetBlockReadBytesPerSecondNil

`func (o *ContainerStats) SetBlockReadBytesPerSecondNil(b bool)`

 SetBlockReadBytesPerSecondNil sets the value for BlockReadBytesPerSecond to be an explicit nil

### UnsetBlockReadBytesPerSecond
`func (o *ContainerStats) UnsetBlockReadBytesPerSecond()`

UnsetBlockReadBytesPerSecond ensures that no value is present for BlockReadBytesPerSecond, not even an explicit nil
### GetBlockReadOps

`func (o *ContainerStats) GetBlockReadOps() int32`

GetBlockReadOps returns the BlockReadOps field if non-nil, zero value otherwise.

### GetBlockReadOpsOk

`func (o *ContainerStats) GetBlockReadOpsOk() (*int32, bool)`

GetBlockReadOpsOk returns a tuple with the BlockReadOps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlockReadOps

`func (o *ContainerStats) SetBlockReadOps(v int32)`

SetBlockReadOps sets BlockReadOps field to given value.


### GetBlockWriteBytes

`func (o *ContainerStats) GetBlockWriteBytes() int32`

GetBlockWriteBytes returns the BlockWriteBytes field if non-nil, zero value otherwise.

### GetBlockWriteBytesOk

`func (o *ContainerStats) GetBlockWriteBytesOk() (*int32, bool)`

GetBlockWriteBytesOk returns a tuple with the BlockWriteBytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlockWriteBytes

`func (o *ContainerStats) SetBlockWriteBytes(v int32)`

SetBlockWriteBytes sets BlockWriteBytes field to given value.


### GetBlockWriteBytesPerSecond

`func (o *ContainerStats) GetBlockWriteBytesPerSecond() float32`

GetBlockWriteBytesPerSecond returns the BlockWriteBytesPerSecond field if non-nil, zero value otherwise.

### GetBlockWriteBytesPerSecondOk

`func (o *ContainerStats) GetBlockWriteBytesPerSecondOk() (*float32, bool)`

GetBlockWriteBytesPerSecondOk returns a tuple with the BlockWriteBytesPerSecond field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlockWriteBytesPerSecond

`func (o *ContainerStats) SetBlockWriteBytesPerSecond(v float32)`

SetBlockWriteBytesPerSecond sets BlockWriteBytesPerSecond field to given value.


### SetBlockWriteBytesPerSecondNil

`func (o *ContainerStats) SetBlockWriteBytesPerSecondNil(b bool)`

 SetBlockWriteBytesPerSecondNil sets the value for BlockWriteBytesPerSecond to be an explicit nil

### UnsetBlockWriteBytesPerSecond
`func (o *ContainerStats) UnsetBlockWriteBytesPerSecond()`

UnsetBlockWriteBytesPerSecond ensures that no value is present for BlockWriteBytesPerSecond, not even an explicit nil
### GetBlockWriteOps

`func (o *ContainerStats) GetBlockWriteOps() int32`

GetBlockWriteOps returns the BlockWriteOps field if non-nil, zero value otherwise.

### GetBlockWriteOpsOk

`func (o *ContainerStats) GetBlockWriteOpsOk() (*int32, bool)`

GetBlockWriteOpsOk returns a tuple with the BlockWriteOps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlockWriteOps

`func (o *ContainerStats) SetBlockWriteOps(v int32)`

SetBlockWriteOps sets BlockWriteOps field to given value.


### GetCpuPercentOfHost

`func (o *ContainerStats) GetCpuPercentOfHost() float32`

GetCpuPercentOfHost returns the CpuPercentOfHost field if non-nil, zero value otherwise.

### GetCpuPercentOfHostOk

`func (o *ContainerStats) GetCpuPercentOfHostOk() (*float32, bool)`

GetCpuPercentOfHostOk returns a tuple with the CpuPercentOfHost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCpuPercentOfHost

`func (o *ContainerStats) SetCpuPercentOfHost(v float32)`

SetCpuPercentOfHost sets CpuPercentOfHost field to given value.


### SetCpuPercentOfHostNil

`func (o *ContainerStats) SetCpuPercentOfHostNil(b bool)`

 SetCpuPercentOfHostNil sets the value for CpuPercentOfHost to be an explicit nil

### UnsetCpuPercentOfHost
`func (o *ContainerStats) UnsetCpuPercentOfHost()`

UnsetCpuPercentOfHost ensures that no value is present for CpuPercentOfHost, not even an explicit nil
### GetCpuPercentOfQuota

`func (o *ContainerStats) GetCpuPercentOfQuota() float32`

GetCpuPercentOfQuota returns the CpuPercentOfQuota field if non-nil, zero value otherwise.

### GetCpuPercentOfQuotaOk

`func (o *ContainerStats) GetCpuPercentOfQuotaOk() (*float32, bool)`

GetCpuPercentOfQuotaOk returns a tuple with the CpuPercentOfQuota field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCpuPercentOfQuota

`func (o *ContainerStats) SetCpuPercentOfQuota(v float32)`

SetCpuPercentOfQuota sets CpuPercentOfQuota field to given value.


### SetCpuPercentOfQuotaNil

`func (o *ContainerStats) SetCpuPercentOfQuotaNil(b bool)`

 SetCpuPercentOfQuotaNil sets the value for CpuPercentOfQuota to be an explicit nil

### UnsetCpuPercentOfQuota
`func (o *ContainerStats) UnsetCpuPercentOfQuota()`

UnsetCpuPercentOfQuota ensures that no value is present for CpuPercentOfQuota, not even an explicit nil
### GetCpuQuotaCores

`func (o *ContainerStats) GetCpuQuotaCores() float32`

GetCpuQuotaCores returns the CpuQuotaCores field if non-nil, zero value otherwise.

### GetCpuQuotaCoresOk

`func (o *ContainerStats) GetCpuQuotaCoresOk() (*float32, bool)`

GetCpuQuotaCoresOk returns a tuple with the CpuQuotaCores field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCpuQuotaCores

`func (o *ContainerStats) SetCpuQuotaCores(v float32)`

SetCpuQuotaCores sets CpuQuotaCores field to given value.


### GetCpuSystemTime

`func (o *ContainerStats) GetCpuSystemTime() int32`

GetCpuSystemTime returns the CpuSystemTime field if non-nil, zero value otherwise.

### GetCpuSystemTimeOk

`func (o *ContainerStats) GetCpuSystemTimeOk() (*int32, bool)`

GetCpuSystemTimeOk returns a tuple with the CpuSystemTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCpuSystemTime

`func (o *ContainerStats) SetCpuSystemTime(v int32)`

SetCpuSystemTime sets CpuSystemTime field to given value.


### GetCpuThrottledPercent

`func (o *ContainerStats) GetCpuThrottledPercent() float32`

GetCpuThrottledPercent returns the CpuThrottledPercent field if non-nil, zero value otherwise.

### GetCpuThrottledPercentOk

`func (o *ContainerStats) GetCpuThrottledPercentOk() (*float32, bool)`

GetCpuThrottledPercentOk returns a tuple with the CpuThrottledPercent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCpuThrottledPercent

`func (o *ContainerStats) SetCpuThrottledPercent(v float32)`

SetCpuThrottledPercent sets CpuThrottledPercent field to given value.


### SetCpuThrottledPercentNil

`func (o *ContainerStats) SetCpuThrottledPercentNil(b bool)`

 SetCpuThrottledPercentNil sets the value for CpuThrottledPercent to be an explicit nil

### UnsetCpuThrottledPercent
`func (o *ContainerStats) UnsetCpuThrottledPercent()`

UnsetCpuThrottledPercent ensures that no value is present for CpuThrottledPercent, not even an explicit nil
### GetCpuUsageCores

`func (o *ContainerStats) GetCpuUsageCores() float32`

GetCpuUsageCores returns the CpuUsageCores field if non-nil, zero value otherwise.

### GetCpuUsageCoresOk

`func (o *ContainerStats) GetCpuUsageCoresOk() (*float32, bool)`

GetCpuUsageCoresOk returns a tuple with the CpuUsageCores field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCpuUsageCores

`func (o *ContainerStats) SetCpuUsageCores(v float32)`

SetCpuUsageCores sets CpuUsageCores field to given value.


### SetCpuUsageCoresNil

`func (o *ContainerStats) SetCpuUsageCoresNil(b bool)`

 SetCpuUsageCoresNil sets the value for CpuUsageCores to be an explicit nil

### UnsetCpuUsageCores
`func (o *ContainerStats) UnsetCpuUsageCores()`

UnsetCpuUsageCores ensures that no value is present for CpuUsageCores, not even an explicit nil
### GetCpuUserTime

`func (o *ContainerStats) GetCpuUserTime() int32`

GetCpuUserTime returns the CpuUserTime field if non-nil, zero value otherwise.

### GetCpuUserTimeOk

`func (o *ContainerStats) GetCpuUserTimeOk() (*int32, bool)`

GetCpuUserTimeOk returns a tuple with the CpuUserTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCpuUserTime

`func (o *ContainerStats) SetCpuUserTime(v int32)`

SetCpuUserTime sets CpuUserTime field to given value.


### GetMemoryAnon

`func (o *ContainerStats) GetMemoryAnon() int32`

GetMemoryAnon returns the MemoryAnon field if non-nil, zero value otherwise.

### GetMemoryAnonOk

`func (o *ContainerStats) GetMemoryAnonOk() (*int32, bool)`

GetMemoryAnonOk returns a tuple with the MemoryAnon field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemoryAnon

`func (o *ContainerStats) SetMemoryAnon(v int32)`

SetMemoryAnon sets MemoryAnon field to given value.


### GetMemoryCurrent

`func (o *ContainerStats) GetMemoryCurrent() int32`

GetMemoryCurrent returns the MemoryCurrent field if non-nil, zero value otherwise.

### GetMemoryCurrentOk

`func (o *ContainerStats) GetMemoryCurrentOk() (*int32, bool)`

GetMemoryCurrentOk returns a tuple with the MemoryCurrent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemoryCurrent

`func (o *ContainerStats) SetMemoryCurrent(v int32)`

SetMemoryCurrent sets MemoryCurrent field to given value.


### GetMemoryFile

`func (o *ContainerStats) GetMemoryFile() int32`

GetMemoryFile returns the MemoryFile field if non-nil, zero value otherwise.

### GetMemoryFileOk

`func (o *ContainerStats) GetMemoryFileOk() (*int32, bool)`

GetMemoryFileOk returns a tuple with the MemoryFile field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemoryFile

`func (o *ContainerStats) SetMemoryFile(v int32)`

SetMemoryFile sets MemoryFile field to given value.


### GetMemoryInactiveFile

`func (o *ContainerStats) GetMemoryInactiveFile() int32`

GetMemoryInactiveFile returns the MemoryInactiveFile field if non-nil, zero value otherwise.

### GetMemoryInactiveFileOk

`func (o *ContainerStats) GetMemoryInactiveFileOk() (*int32, bool)`

GetMemoryInactiveFileOk returns a tuple with the MemoryInactiveFile field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemoryInactiveFile

`func (o *ContainerStats) SetMemoryInactiveFile(v int32)`

SetMemoryInactiveFile sets MemoryInactiveFile field to given value.


### GetMemoryLimit

`func (o *ContainerStats) GetMemoryLimit() int32`

GetMemoryLimit returns the MemoryLimit field if non-nil, zero value otherwise.

### GetMemoryLimitOk

`func (o *ContainerStats) GetMemoryLimitOk() (*int32, bool)`

GetMemoryLimitOk returns a tuple with the MemoryLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemoryLimit

`func (o *ContainerStats) SetMemoryLimit(v int32)`

SetMemoryLimit sets MemoryLimit field to given value.


### GetMemoryLimitHits

`func (o *ContainerStats) GetMemoryLimitHits() int32`

GetMemoryLimitHits returns the MemoryLimitHits field if non-nil, zero value otherwise.

### GetMemoryLimitHitsOk

`func (o *ContainerStats) GetMemoryLimitHitsOk() (*int32, bool)`

GetMemoryLimitHitsOk returns a tuple with the MemoryLimitHits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemoryLimitHits

`func (o *ContainerStats) SetMemoryLimitHits(v int32)`

SetMemoryLimitHits sets MemoryLimitHits field to given value.


### GetMemoryPeak

`func (o *ContainerStats) GetMemoryPeak() int32`

GetMemoryPeak returns the MemoryPeak field if non-nil, zero value otherwise.

### GetMemoryPeakOk

`func (o *ContainerStats) GetMemoryPeakOk() (*int32, bool)`

GetMemoryPeakOk returns a tuple with the MemoryPeak field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemoryPeak

`func (o *ContainerStats) SetMemoryPeak(v int32)`

SetMemoryPeak sets MemoryPeak field to given value.


### GetMemoryPercentOfHost

`func (o *ContainerStats) GetMemoryPercentOfHost() float32`

GetMemoryPercentOfHost returns the MemoryPercentOfHost field if non-nil, zero value otherwise.

### GetMemoryPercentOfHostOk

`func (o *ContainerStats) GetMemoryPercentOfHostOk() (*float32, bool)`

GetMemoryPercentOfHostOk returns a tuple with the MemoryPercentOfHost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemoryPercentOfHost

`func (o *ContainerStats) SetMemoryPercentOfHost(v float32)`

SetMemoryPercentOfHost sets MemoryPercentOfHost field to given value.


### SetMemoryPercentOfHostNil

`func (o *ContainerStats) SetMemoryPercentOfHostNil(b bool)`

 SetMemoryPercentOfHostNil sets the value for MemoryPercentOfHost to be an explicit nil

### UnsetMemoryPercentOfHost
`func (o *ContainerStats) UnsetMemoryPercentOfHost()`

UnsetMemoryPercentOfHost ensures that no value is present for MemoryPercentOfHost, not even an explicit nil
### GetMemoryPercentOfLimit

`func (o *ContainerStats) GetMemoryPercentOfLimit() float32`

GetMemoryPercentOfLimit returns the MemoryPercentOfLimit field if non-nil, zero value otherwise.

### GetMemoryPercentOfLimitOk

`func (o *ContainerStats) GetMemoryPercentOfLimitOk() (*float32, bool)`

GetMemoryPercentOfLimitOk returns a tuple with the MemoryPercentOfLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemoryPercentOfLimit

`func (o *ContainerStats) SetMemoryPercentOfLimit(v float32)`

SetMemoryPercentOfLimit sets MemoryPercentOfLimit field to given value.


### SetMemoryPercentOfLimitNil

`func (o *ContainerStats) SetMemoryPercentOfLimitNil(b bool)`

 SetMemoryPercentOfLimitNil sets the value for MemoryPercentOfLimit to be an explicit nil

### UnsetMemoryPercentOfLimit
`func (o *ContainerStats) UnsetMemoryPercentOfLimit()`

UnsetMemoryPercentOfLimit ensures that no value is present for MemoryPercentOfLimit, not even an explicit nil
### GetMemorySwap

`func (o *ContainerStats) GetMemorySwap() int32`

GetMemorySwap returns the MemorySwap field if non-nil, zero value otherwise.

### GetMemorySwapOk

`func (o *ContainerStats) GetMemorySwapOk() (*int32, bool)`

GetMemorySwapOk returns a tuple with the MemorySwap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemorySwap

`func (o *ContainerStats) SetMemorySwap(v int32)`

SetMemorySwap sets MemorySwap field to given value.


### GetMemoryWorkingSet

`func (o *ContainerStats) GetMemoryWorkingSet() int32`

GetMemoryWorkingSet returns the MemoryWorkingSet field if non-nil, zero value otherwise.

### GetMemoryWorkingSetOk

`func (o *ContainerStats) GetMemoryWorkingSetOk() (*int32, bool)`

GetMemoryWorkingSetOk returns a tuple with the MemoryWorkingSet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemoryWorkingSet

`func (o *ContainerStats) SetMemoryWorkingSet(v int32)`

SetMemoryWorkingSet sets MemoryWorkingSet field to given value.


### GetName

`func (o *ContainerStats) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ContainerStats) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ContainerStats) SetName(v string)`

SetName sets Name field to given value.


### GetNetworkRxBytes

`func (o *ContainerStats) GetNetworkRxBytes() int32`

GetNetworkRxBytes returns the NetworkRxBytes field if non-nil, zero value otherwise.

### GetNetworkRxBytesOk

`func (o *ContainerStats) GetNetworkRxBytesOk() (*int32, bool)`

GetNetworkRxBytesOk returns a tuple with the NetworkRxBytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworkRxBytes

`func (o *ContainerStats) SetNetworkRxBytes(v int32)`

SetNetworkRxBytes sets NetworkRxBytes field to given value.


### GetNetworkRxBytesPerSecond

`func (o *ContainerStats) GetNetworkRxBytesPerSecond() float32`

GetNetworkRxBytesPerSecond returns the NetworkRxBytesPerSecond field if non-nil, zero value otherwise.

### GetNetworkRxBytesPerSecondOk

`func (o *ContainerStats) GetNetworkRxBytesPerSecondOk() (*float32, bool)`

GetNetworkRxBytesPerSecondOk returns a tuple with the NetworkRxBytesPerSecond field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworkRxBytesPerSecond

`func (o *ContainerStats) SetNetworkRxBytesPerSecond(v float32)`

SetNetworkRxBytesPerSecond sets NetworkRxBytesPerSecond field to given value.


### SetNetworkRxBytesPerSecondNil

`func (o *ContainerStats) SetNetworkRxBytesPerSecondNil(b bool)`

 SetNetworkRxBytesPerSecondNil sets the value for NetworkRxBytesPerSecond to be an explicit nil

### UnsetNetworkRxBytesPerSecond
`func (o *ContainerStats) UnsetNetworkRxBytesPerSecond()`

UnsetNetworkRxBytesPerSecond ensures that no value is present for NetworkRxBytesPerSecond, not even an explicit nil
### GetNetworkRxPackets

`func (o *ContainerStats) GetNetworkRxPackets() int32`

GetNetworkRxPackets returns the NetworkRxPackets field if non-nil, zero value otherwise.

### GetNetworkRxPacketsOk

`func (o *ContainerStats) GetNetworkRxPacketsOk() (*int32, bool)`

GetNetworkRxPacketsOk returns a tuple with the NetworkRxPackets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworkRxPackets

`func (o *ContainerStats) SetNetworkRxPackets(v int32)`

SetNetworkRxPackets sets NetworkRxPackets field to given value.


### GetNetworkTxBytes

`func (o *ContainerStats) GetNetworkTxBytes() int32`

GetNetworkTxBytes returns the NetworkTxBytes field if non-nil, zero value otherwise.

### GetNetworkTxBytesOk

`func (o *ContainerStats) GetNetworkTxBytesOk() (*int32, bool)`

GetNetworkTxBytesOk returns a tuple with the NetworkTxBytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworkTxBytes

`func (o *ContainerStats) SetNetworkTxBytes(v int32)`

SetNetworkTxBytes sets NetworkTxBytes field to given value.


### GetNetworkTxBytesPerSecond

`func (o *ContainerStats) GetNetworkTxBytesPerSecond() float32`

GetNetworkTxBytesPerSecond returns the NetworkTxBytesPerSecond field if non-nil, zero value otherwise.

### GetNetworkTxBytesPerSecondOk

`func (o *ContainerStats) GetNetworkTxBytesPerSecondOk() (*float32, bool)`

GetNetworkTxBytesPerSecondOk returns a tuple with the NetworkTxBytesPerSecond field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworkTxBytesPerSecond

`func (o *ContainerStats) SetNetworkTxBytesPerSecond(v float32)`

SetNetworkTxBytesPerSecond sets NetworkTxBytesPerSecond field to given value.


### SetNetworkTxBytesPerSecondNil

`func (o *ContainerStats) SetNetworkTxBytesPerSecondNil(b bool)`

 SetNetworkTxBytesPerSecondNil sets the value for NetworkTxBytesPerSecond to be an explicit nil

### UnsetNetworkTxBytesPerSecond
`func (o *ContainerStats) UnsetNetworkTxBytesPerSecond()`

UnsetNetworkTxBytesPerSecond ensures that no value is present for NetworkTxBytesPerSecond, not even an explicit nil
### GetNetworkTxPackets

`func (o *ContainerStats) GetNetworkTxPackets() int32`

GetNetworkTxPackets returns the NetworkTxPackets field if non-nil, zero value otherwise.

### GetNetworkTxPacketsOk

`func (o *ContainerStats) GetNetworkTxPacketsOk() (*int32, bool)`

GetNetworkTxPacketsOk returns a tuple with the NetworkTxPackets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworkTxPackets

`func (o *ContainerStats) SetNetworkTxPackets(v int32)`

SetNetworkTxPackets sets NetworkTxPackets field to given value.


### GetOomKills

`func (o *ContainerStats) GetOomKills() int32`

GetOomKills returns the OomKills field if non-nil, zero value otherwise.

### GetOomKillsOk

`func (o *ContainerStats) GetOomKillsOk() (*int32, bool)`

GetOomKillsOk returns a tuple with the OomKills field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOomKills

`func (o *ContainerStats) SetOomKills(v int32)`

SetOomKills sets OomKills field to given value.


### GetPageFaults

`func (o *ContainerStats) GetPageFaults() int32`

GetPageFaults returns the PageFaults field if non-nil, zero value otherwise.

### GetPageFaultsOk

`func (o *ContainerStats) GetPageFaultsOk() (*int32, bool)`

GetPageFaultsOk returns a tuple with the PageFaults field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageFaults

`func (o *ContainerStats) SetPageFaults(v int32)`

SetPageFaults sets PageFaults field to given value.


### GetPageMajorFaults

`func (o *ContainerStats) GetPageMajorFaults() int32`

GetPageMajorFaults returns the PageMajorFaults field if non-nil, zero value otherwise.

### GetPageMajorFaultsOk

`func (o *ContainerStats) GetPageMajorFaultsOk() (*int32, bool)`

GetPageMajorFaultsOk returns a tuple with the PageMajorFaults field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageMajorFaults

`func (o *ContainerStats) SetPageMajorFaults(v int32)`

SetPageMajorFaults sets PageMajorFaults field to given value.


### GetServiceName

`func (o *ContainerStats) GetServiceName() string`

GetServiceName returns the ServiceName field if non-nil, zero value otherwise.

### GetServiceNameOk

`func (o *ContainerStats) GetServiceNameOk() (*string, bool)`

GetServiceNameOk returns a tuple with the ServiceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceName

`func (o *ContainerStats) SetServiceName(v string)`

SetServiceName sets ServiceName field to given value.


### GetState

`func (o *ContainerStats) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *ContainerStats) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *ContainerStats) SetState(v string)`

SetState sets State field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


