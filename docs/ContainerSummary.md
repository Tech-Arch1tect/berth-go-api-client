# ContainerSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Containers** | [**[]ContainerInfo**](ContainerInfo.md) |  | 
**RunningCount** | **int32** |  | 
**Total** | [**Amount**](Amount.md) |  | 

## Methods

### NewContainerSummary

`func NewContainerSummary(containers []ContainerInfo, runningCount int32, total Amount, ) *ContainerSummary`

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


### GetTotal

`func (o *ContainerSummary) GetTotal() Amount`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *ContainerSummary) GetTotalOk() (*Amount, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *ContainerSummary) SetTotal(v Amount)`

SetTotal sets Total field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


