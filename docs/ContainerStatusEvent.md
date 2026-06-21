# ContainerStatusEvent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ContainerId** | **string** |  | 
**ContainerName** | **string** |  | 
**Health** | Pointer to **string** |  | [optional] 
**Image** | **string** |  | 
**Ports** | Pointer to [**[]Port**](Port.md) |  | [optional] 
**ServerId** | **int32** |  | 
**ServiceName** | **string** |  | 
**StackName** | **string** |  | 
**Status** | **string** |  | 
**Timestamp** | **string** |  | 
**Type** | **string** |  | 

## Methods

### NewContainerStatusEvent

`func NewContainerStatusEvent(containerId string, containerName string, image string, serverId int32, serviceName string, stackName string, status string, timestamp string, type_ string, ) *ContainerStatusEvent`

NewContainerStatusEvent instantiates a new ContainerStatusEvent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContainerStatusEventWithDefaults

`func NewContainerStatusEventWithDefaults() *ContainerStatusEvent`

NewContainerStatusEventWithDefaults instantiates a new ContainerStatusEvent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContainerId

`func (o *ContainerStatusEvent) GetContainerId() string`

GetContainerId returns the ContainerId field if non-nil, zero value otherwise.

### GetContainerIdOk

`func (o *ContainerStatusEvent) GetContainerIdOk() (*string, bool)`

GetContainerIdOk returns a tuple with the ContainerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainerId

`func (o *ContainerStatusEvent) SetContainerId(v string)`

SetContainerId sets ContainerId field to given value.


### GetContainerName

`func (o *ContainerStatusEvent) GetContainerName() string`

GetContainerName returns the ContainerName field if non-nil, zero value otherwise.

### GetContainerNameOk

`func (o *ContainerStatusEvent) GetContainerNameOk() (*string, bool)`

GetContainerNameOk returns a tuple with the ContainerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainerName

`func (o *ContainerStatusEvent) SetContainerName(v string)`

SetContainerName sets ContainerName field to given value.


### GetHealth

`func (o *ContainerStatusEvent) GetHealth() string`

GetHealth returns the Health field if non-nil, zero value otherwise.

### GetHealthOk

`func (o *ContainerStatusEvent) GetHealthOk() (*string, bool)`

GetHealthOk returns a tuple with the Health field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHealth

`func (o *ContainerStatusEvent) SetHealth(v string)`

SetHealth sets Health field to given value.

### HasHealth

`func (o *ContainerStatusEvent) HasHealth() bool`

HasHealth returns a boolean if a field has been set.

### GetImage

`func (o *ContainerStatusEvent) GetImage() string`

GetImage returns the Image field if non-nil, zero value otherwise.

### GetImageOk

`func (o *ContainerStatusEvent) GetImageOk() (*string, bool)`

GetImageOk returns a tuple with the Image field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImage

`func (o *ContainerStatusEvent) SetImage(v string)`

SetImage sets Image field to given value.


### GetPorts

`func (o *ContainerStatusEvent) GetPorts() []Port`

GetPorts returns the Ports field if non-nil, zero value otherwise.

### GetPortsOk

`func (o *ContainerStatusEvent) GetPortsOk() (*[]Port, bool)`

GetPortsOk returns a tuple with the Ports field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPorts

`func (o *ContainerStatusEvent) SetPorts(v []Port)`

SetPorts sets Ports field to given value.

### HasPorts

`func (o *ContainerStatusEvent) HasPorts() bool`

HasPorts returns a boolean if a field has been set.

### GetServerId

`func (o *ContainerStatusEvent) GetServerId() int32`

GetServerId returns the ServerId field if non-nil, zero value otherwise.

### GetServerIdOk

`func (o *ContainerStatusEvent) GetServerIdOk() (*int32, bool)`

GetServerIdOk returns a tuple with the ServerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerId

`func (o *ContainerStatusEvent) SetServerId(v int32)`

SetServerId sets ServerId field to given value.


### GetServiceName

`func (o *ContainerStatusEvent) GetServiceName() string`

GetServiceName returns the ServiceName field if non-nil, zero value otherwise.

### GetServiceNameOk

`func (o *ContainerStatusEvent) GetServiceNameOk() (*string, bool)`

GetServiceNameOk returns a tuple with the ServiceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceName

`func (o *ContainerStatusEvent) SetServiceName(v string)`

SetServiceName sets ServiceName field to given value.


### GetStackName

`func (o *ContainerStatusEvent) GetStackName() string`

GetStackName returns the StackName field if non-nil, zero value otherwise.

### GetStackNameOk

`func (o *ContainerStatusEvent) GetStackNameOk() (*string, bool)`

GetStackNameOk returns a tuple with the StackName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStackName

`func (o *ContainerStatusEvent) SetStackName(v string)`

SetStackName sets StackName field to given value.


### GetStatus

`func (o *ContainerStatusEvent) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ContainerStatusEvent) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ContainerStatusEvent) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetTimestamp

`func (o *ContainerStatusEvent) GetTimestamp() string`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *ContainerStatusEvent) GetTimestampOk() (*string, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *ContainerStatusEvent) SetTimestamp(v string)`

SetTimestamp sets Timestamp field to given value.


### GetType

`func (o *ContainerStatusEvent) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ContainerStatusEvent) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ContainerStatusEvent) SetType(v string)`

SetType sets Type field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


