# StackStats

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CollectedAt** | **time.Time** |  | 
**Containers** | [**[]ContainerStats**](ContainerStats.md) |  | 
**Host** | [**HostStats**](HostStats.md) |  | 
**SampleWindowSeconds** | **NullableFloat32** |  | 
**StackName** | **string** |  | 

## Methods

### NewStackStats

`func NewStackStats(collectedAt time.Time, containers []ContainerStats, host HostStats, sampleWindowSeconds NullableFloat32, stackName string, ) *StackStats`

NewStackStats instantiates a new StackStats object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStackStatsWithDefaults

`func NewStackStatsWithDefaults() *StackStats`

NewStackStatsWithDefaults instantiates a new StackStats object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCollectedAt

`func (o *StackStats) GetCollectedAt() time.Time`

GetCollectedAt returns the CollectedAt field if non-nil, zero value otherwise.

### GetCollectedAtOk

`func (o *StackStats) GetCollectedAtOk() (*time.Time, bool)`

GetCollectedAtOk returns a tuple with the CollectedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCollectedAt

`func (o *StackStats) SetCollectedAt(v time.Time)`

SetCollectedAt sets CollectedAt field to given value.


### GetContainers

`func (o *StackStats) GetContainers() []ContainerStats`

GetContainers returns the Containers field if non-nil, zero value otherwise.

### GetContainersOk

`func (o *StackStats) GetContainersOk() (*[]ContainerStats, bool)`

GetContainersOk returns a tuple with the Containers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainers

`func (o *StackStats) SetContainers(v []ContainerStats)`

SetContainers sets Containers field to given value.


### GetHost

`func (o *StackStats) GetHost() HostStats`

GetHost returns the Host field if non-nil, zero value otherwise.

### GetHostOk

`func (o *StackStats) GetHostOk() (*HostStats, bool)`

GetHostOk returns a tuple with the Host field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHost

`func (o *StackStats) SetHost(v HostStats)`

SetHost sets Host field to given value.


### GetSampleWindowSeconds

`func (o *StackStats) GetSampleWindowSeconds() float32`

GetSampleWindowSeconds returns the SampleWindowSeconds field if non-nil, zero value otherwise.

### GetSampleWindowSecondsOk

`func (o *StackStats) GetSampleWindowSecondsOk() (*float32, bool)`

GetSampleWindowSecondsOk returns a tuple with the SampleWindowSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSampleWindowSeconds

`func (o *StackStats) SetSampleWindowSeconds(v float32)`

SetSampleWindowSeconds sets SampleWindowSeconds field to given value.


### SetSampleWindowSecondsNil

`func (o *StackStats) SetSampleWindowSecondsNil(b bool)`

 SetSampleWindowSecondsNil sets the value for SampleWindowSeconds to be an explicit nil

### UnsetSampleWindowSeconds
`func (o *StackStats) UnsetSampleWindowSeconds()`

UnsetSampleWindowSeconds ensures that no value is present for SampleWindowSeconds, not even an explicit nil
### GetStackName

`func (o *StackStats) GetStackName() string`

GetStackName returns the StackName field if non-nil, zero value otherwise.

### GetStackNameOk

`func (o *StackStats) GetStackNameOk() (*string, bool)`

GetStackNameOk returns a tuple with the StackName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStackName

`func (o *StackStats) SetStackName(v string)`

SetStackName sets StackName field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


