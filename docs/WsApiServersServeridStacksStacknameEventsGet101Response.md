# WsApiServersServeridStacksStacknameEventsGet101Response

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
**Running** | **int32** |  | 
**Services** | **int32** |  | 
**Stopped** | **int32** |  | 

## Methods

### NewWsApiServersServeridStacksStacknameEventsGet101Response

`func NewWsApiServersServeridStacksStacknameEventsGet101Response(containerId string, containerName string, image string, serverId int32, serviceName string, stackName string, status string, timestamp string, type_ string, running int32, services int32, stopped int32, ) *WsApiServersServeridStacksStacknameEventsGet101Response`

NewWsApiServersServeridStacksStacknameEventsGet101Response instantiates a new WsApiServersServeridStacksStacknameEventsGet101Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWsApiServersServeridStacksStacknameEventsGet101ResponseWithDefaults

`func NewWsApiServersServeridStacksStacknameEventsGet101ResponseWithDefaults() *WsApiServersServeridStacksStacknameEventsGet101Response`

NewWsApiServersServeridStacksStacknameEventsGet101ResponseWithDefaults instantiates a new WsApiServersServeridStacksStacknameEventsGet101Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContainerId

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) GetContainerId() string`

GetContainerId returns the ContainerId field if non-nil, zero value otherwise.

### GetContainerIdOk

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) GetContainerIdOk() (*string, bool)`

GetContainerIdOk returns a tuple with the ContainerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainerId

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) SetContainerId(v string)`

SetContainerId sets ContainerId field to given value.


### GetContainerName

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) GetContainerName() string`

GetContainerName returns the ContainerName field if non-nil, zero value otherwise.

### GetContainerNameOk

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) GetContainerNameOk() (*string, bool)`

GetContainerNameOk returns a tuple with the ContainerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainerName

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) SetContainerName(v string)`

SetContainerName sets ContainerName field to given value.


### GetHealth

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) GetHealth() string`

GetHealth returns the Health field if non-nil, zero value otherwise.

### GetHealthOk

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) GetHealthOk() (*string, bool)`

GetHealthOk returns a tuple with the Health field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHealth

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) SetHealth(v string)`

SetHealth sets Health field to given value.

### HasHealth

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) HasHealth() bool`

HasHealth returns a boolean if a field has been set.

### GetImage

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) GetImage() string`

GetImage returns the Image field if non-nil, zero value otherwise.

### GetImageOk

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) GetImageOk() (*string, bool)`

GetImageOk returns a tuple with the Image field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImage

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) SetImage(v string)`

SetImage sets Image field to given value.


### GetPorts

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) GetPorts() []Port`

GetPorts returns the Ports field if non-nil, zero value otherwise.

### GetPortsOk

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) GetPortsOk() (*[]Port, bool)`

GetPortsOk returns a tuple with the Ports field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPorts

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) SetPorts(v []Port)`

SetPorts sets Ports field to given value.

### HasPorts

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) HasPorts() bool`

HasPorts returns a boolean if a field has been set.

### GetServerId

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) GetServerId() int32`

GetServerId returns the ServerId field if non-nil, zero value otherwise.

### GetServerIdOk

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) GetServerIdOk() (*int32, bool)`

GetServerIdOk returns a tuple with the ServerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerId

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) SetServerId(v int32)`

SetServerId sets ServerId field to given value.


### GetServiceName

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) GetServiceName() string`

GetServiceName returns the ServiceName field if non-nil, zero value otherwise.

### GetServiceNameOk

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) GetServiceNameOk() (*string, bool)`

GetServiceNameOk returns a tuple with the ServiceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceName

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) SetServiceName(v string)`

SetServiceName sets ServiceName field to given value.


### GetStackName

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) GetStackName() string`

GetStackName returns the StackName field if non-nil, zero value otherwise.

### GetStackNameOk

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) GetStackNameOk() (*string, bool)`

GetStackNameOk returns a tuple with the StackName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStackName

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) SetStackName(v string)`

SetStackName sets StackName field to given value.


### GetStatus

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetTimestamp

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) GetTimestamp() string`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) GetTimestampOk() (*string, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) SetTimestamp(v string)`

SetTimestamp sets Timestamp field to given value.


### GetType

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) SetType(v string)`

SetType sets Type field to given value.


### GetRunning

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) GetRunning() int32`

GetRunning returns the Running field if non-nil, zero value otherwise.

### GetRunningOk

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) GetRunningOk() (*int32, bool)`

GetRunningOk returns a tuple with the Running field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunning

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) SetRunning(v int32)`

SetRunning sets Running field to given value.


### GetServices

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) GetServices() int32`

GetServices returns the Services field if non-nil, zero value otherwise.

### GetServicesOk

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) GetServicesOk() (*int32, bool)`

GetServicesOk returns a tuple with the Services field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServices

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) SetServices(v int32)`

SetServices sets Services field to given value.


### GetStopped

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) GetStopped() int32`

GetStopped returns the Stopped field if non-nil, zero value otherwise.

### GetStoppedOk

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) GetStoppedOk() (*int32, bool)`

GetStoppedOk returns a tuple with the Stopped field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStopped

`func (o *WsApiServersServeridStacksStacknameEventsGet101Response) SetStopped(v int32)`

SetStopped sets Stopped field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


