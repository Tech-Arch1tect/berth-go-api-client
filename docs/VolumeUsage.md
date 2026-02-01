# VolumeUsage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ContainerName** | **string** |  | 
**Mounts** | [**[]VolumeMount**](VolumeMount.md) |  | 
**ServiceName** | **string** |  | 

## Methods

### NewVolumeUsage

`func NewVolumeUsage(containerName string, mounts []VolumeMount, serviceName string, ) *VolumeUsage`

NewVolumeUsage instantiates a new VolumeUsage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVolumeUsageWithDefaults

`func NewVolumeUsageWithDefaults() *VolumeUsage`

NewVolumeUsageWithDefaults instantiates a new VolumeUsage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContainerName

`func (o *VolumeUsage) GetContainerName() string`

GetContainerName returns the ContainerName field if non-nil, zero value otherwise.

### GetContainerNameOk

`func (o *VolumeUsage) GetContainerNameOk() (*string, bool)`

GetContainerNameOk returns a tuple with the ContainerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainerName

`func (o *VolumeUsage) SetContainerName(v string)`

SetContainerName sets ContainerName field to given value.


### GetMounts

`func (o *VolumeUsage) GetMounts() []VolumeMount`

GetMounts returns the Mounts field if non-nil, zero value otherwise.

### GetMountsOk

`func (o *VolumeUsage) GetMountsOk() (*[]VolumeMount, bool)`

GetMountsOk returns a tuple with the Mounts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMounts

`func (o *VolumeUsage) SetMounts(v []VolumeMount)`

SetMounts sets Mounts field to given value.


### GetServiceName

`func (o *VolumeUsage) GetServiceName() string`

GetServiceName returns the ServiceName field if non-nil, zero value otherwise.

### GetServiceNameOk

`func (o *VolumeUsage) GetServiceNameOk() (*string, bool)`

GetServiceNameOk returns a tuple with the ServiceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceName

`func (o *VolumeUsage) SetServiceName(v string)`

SetServiceName sets ServiceName field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


