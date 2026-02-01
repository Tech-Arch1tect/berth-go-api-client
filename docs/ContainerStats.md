# ContainerStats

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BlockReadBytes** | **int32** |  | 
**BlockReadOps** | **int32** |  | 
**BlockWriteBytes** | **int32** |  | 
**BlockWriteOps** | **int32** |  | 
**CpuPercent** | **float32** |  | 
**CpuSystemTime** | **int32** |  | 
**CpuUserTime** | **int32** |  | 
**MemoryCache** | **int32** |  | 
**MemoryLimit** | **int32** |  | 
**MemoryPercent** | **float32** |  | 
**MemoryRss** | **int32** |  | 
**MemorySwap** | **int32** |  | 
**MemoryUsage** | **int32** |  | 
**Name** | **string** |  | 
**NetworkRxBytes** | **int32** |  | 
**NetworkRxPackets** | **int32** |  | 
**NetworkTxBytes** | **int32** |  | 
**NetworkTxPackets** | **int32** |  | 
**PageFaults** | **int32** |  | 
**PageMajorFaults** | **int32** |  | 
**ServiceName** | **string** |  | 

## Methods

### NewContainerStats

`func NewContainerStats(blockReadBytes int32, blockReadOps int32, blockWriteBytes int32, blockWriteOps int32, cpuPercent float32, cpuSystemTime int32, cpuUserTime int32, memoryCache int32, memoryLimit int32, memoryPercent float32, memoryRss int32, memorySwap int32, memoryUsage int32, name string, networkRxBytes int32, networkRxPackets int32, networkTxBytes int32, networkTxPackets int32, pageFaults int32, pageMajorFaults int32, serviceName string, ) *ContainerStats`

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


### GetCpuPercent

`func (o *ContainerStats) GetCpuPercent() float32`

GetCpuPercent returns the CpuPercent field if non-nil, zero value otherwise.

### GetCpuPercentOk

`func (o *ContainerStats) GetCpuPercentOk() (*float32, bool)`

GetCpuPercentOk returns a tuple with the CpuPercent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCpuPercent

`func (o *ContainerStats) SetCpuPercent(v float32)`

SetCpuPercent sets CpuPercent field to given value.


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


### GetMemoryCache

`func (o *ContainerStats) GetMemoryCache() int32`

GetMemoryCache returns the MemoryCache field if non-nil, zero value otherwise.

### GetMemoryCacheOk

`func (o *ContainerStats) GetMemoryCacheOk() (*int32, bool)`

GetMemoryCacheOk returns a tuple with the MemoryCache field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemoryCache

`func (o *ContainerStats) SetMemoryCache(v int32)`

SetMemoryCache sets MemoryCache field to given value.


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


### GetMemoryPercent

`func (o *ContainerStats) GetMemoryPercent() float32`

GetMemoryPercent returns the MemoryPercent field if non-nil, zero value otherwise.

### GetMemoryPercentOk

`func (o *ContainerStats) GetMemoryPercentOk() (*float32, bool)`

GetMemoryPercentOk returns a tuple with the MemoryPercent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemoryPercent

`func (o *ContainerStats) SetMemoryPercent(v float32)`

SetMemoryPercent sets MemoryPercent field to given value.


### GetMemoryRss

`func (o *ContainerStats) GetMemoryRss() int32`

GetMemoryRss returns the MemoryRss field if non-nil, zero value otherwise.

### GetMemoryRssOk

`func (o *ContainerStats) GetMemoryRssOk() (*int32, bool)`

GetMemoryRssOk returns a tuple with the MemoryRss field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemoryRss

`func (o *ContainerStats) SetMemoryRss(v int32)`

SetMemoryRss sets MemoryRss field to given value.


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


### GetMemoryUsage

`func (o *ContainerStats) GetMemoryUsage() int32`

GetMemoryUsage returns the MemoryUsage field if non-nil, zero value otherwise.

### GetMemoryUsageOk

`func (o *ContainerStats) GetMemoryUsageOk() (*int32, bool)`

GetMemoryUsageOk returns a tuple with the MemoryUsage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemoryUsage

`func (o *ContainerStats) SetMemoryUsage(v int32)`

SetMemoryUsage sets MemoryUsage field to given value.


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



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


