# ContainerSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Containers** | [**[]ContainerInfo**](ContainerInfo.md) |  | 
**RunningCount** | **int32** |  | 
**StoppedCount** | **int32** |  | 
**TotalCount** | **int32** |  | 
**TotalSize** | **int32** |  | 

## Methods

### NewContainerSummary

`func NewContainerSummary(containers []ContainerInfo, runningCount int32, stoppedCount int32, totalCount int32, totalSize int32, ) *ContainerSummary`

NewContainerSummary instantiates a new ContainerSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContainerSummaryWithDefaults

`func NewContainerSummaryWithDefaults() *ContainerSummary`

NewContainerSummaryWithDefaults instantiates a new ContainerSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContainers

`func (o *ContainerSummary) GetContainers() []ContainerInfo`

GetContainers returns the Containers field if non-nil, zero value otherwise.

### GetContainersOk

`func (o *ContainerSummary) GetContainersOk() (*[]ContainerInfo, bool)`

GetContainersOk returns a tuple with the Containers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainers

`func (o *ContainerSummary) SetContainers(v []ContainerInfo)`

SetContainers sets Containers field to given value.


### GetRunningCount

`func (o *ContainerSummary) GetRunningCount() int32`

GetRunningCount returns the RunningCount field if non-nil, zero value otherwise.

### GetRunningCountOk

`func (o *ContainerSummary) GetRunningCountOk() (*int32, bool)`

GetRunningCountOk returns a tuple with the RunningCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunningCount

`func (o *ContainerSummary) SetRunningCount(v int32)`

SetRunningCount sets RunningCount field to given value.


### GetStoppedCount

`func (o *ContainerSummary) GetStoppedCount() int32`

GetStoppedCount returns the StoppedCount field if non-nil, zero value otherwise.

### GetStoppedCountOk

`func (o *ContainerSummary) GetStoppedCountOk() (*int32, bool)`

GetStoppedCountOk returns a tuple with the StoppedCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStoppedCount

`func (o *ContainerSummary) SetStoppedCount(v int32)`

SetStoppedCount sets StoppedCount field to given value.


### GetTotalCount

`func (o *ContainerSummary) GetTotalCount() int32`

GetTotalCount returns the TotalCount field if non-nil, zero value otherwise.

### GetTotalCountOk

`func (o *ContainerSummary) GetTotalCountOk() (*int32, bool)`

GetTotalCountOk returns a tuple with the TotalCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCount

`func (o *ContainerSummary) SetTotalCount(v int32)`

SetTotalCount sets TotalCount field to given value.


### GetTotalSize

`func (o *ContainerSummary) GetTotalSize() int32`

GetTotalSize returns the TotalSize field if non-nil, zero value otherwise.

### GetTotalSizeOk

`func (o *ContainerSummary) GetTotalSizeOk() (*int32, bool)`

GetTotalSizeOk returns a tuple with the TotalSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalSize

`func (o *ContainerSummary) SetTotalSize(v int32)`

SetTotalSize sets TotalSize field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


