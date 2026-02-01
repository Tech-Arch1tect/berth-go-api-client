# StackStatsData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Containers** | [**[]ContainerStats**](ContainerStats.md) |  | 
**StackName** | **string** |  | 

## Methods

### NewStackStatsData

`func NewStackStatsData(containers []ContainerStats, stackName string, ) *StackStatsData`

NewStackStatsData instantiates a new StackStatsData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStackStatsDataWithDefaults

`func NewStackStatsDataWithDefaults() *StackStatsData`

NewStackStatsDataWithDefaults instantiates a new StackStatsData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContainers

`func (o *StackStatsData) GetContainers() []ContainerStats`

GetContainers returns the Containers field if non-nil, zero value otherwise.

### GetContainersOk

`func (o *StackStatsData) GetContainersOk() (*[]ContainerStats, bool)`

GetContainersOk returns a tuple with the Containers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainers

`func (o *StackStatsData) SetContainers(v []ContainerStats)`

SetContainers sets Containers field to given value.


### GetStackName

`func (o *StackStatsData) GetStackName() string`

GetStackName returns the StackName field if non-nil, zero value otherwise.

### GetStackNameOk

`func (o *StackStatsData) GetStackNameOk() (*string, bool)`

GetStackNameOk returns a tuple with the StackName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStackName

`func (o *StackStatsData) SetStackName(v string)`

SetStackName sets StackName field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


