# StackStatusEvent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Running** | **int32** |  | 
**ServerId** | **int32** |  | 
**Services** | **int32** |  | 
**StackName** | **string** |  | 
**Status** | **string** |  | 
**Stopped** | **int32** |  | 
**Timestamp** | **string** |  | 
**Type** | **string** |  | 

## Methods

### NewStackStatusEvent

`func NewStackStatusEvent(running int32, serverId int32, services int32, stackName string, status string, stopped int32, timestamp string, type_ string, ) *StackStatusEvent`

NewStackStatusEvent instantiates a new StackStatusEvent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStackStatusEventWithDefaults

`func NewStackStatusEventWithDefaults() *StackStatusEvent`

NewStackStatusEventWithDefaults instantiates a new StackStatusEvent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRunning

`func (o *StackStatusEvent) GetRunning() int32`

GetRunning returns the Running field if non-nil, zero value otherwise.

### GetRunningOk

`func (o *StackStatusEvent) GetRunningOk() (*int32, bool)`

GetRunningOk returns a tuple with the Running field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunning

`func (o *StackStatusEvent) SetRunning(v int32)`

SetRunning sets Running field to given value.


### GetServerId

`func (o *StackStatusEvent) GetServerId() int32`

GetServerId returns the ServerId field if non-nil, zero value otherwise.

### GetServerIdOk

`func (o *StackStatusEvent) GetServerIdOk() (*int32, bool)`

GetServerIdOk returns a tuple with the ServerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerId

`func (o *StackStatusEvent) SetServerId(v int32)`

SetServerId sets ServerId field to given value.


### GetServices

`func (o *StackStatusEvent) GetServices() int32`

GetServices returns the Services field if non-nil, zero value otherwise.

### GetServicesOk

`func (o *StackStatusEvent) GetServicesOk() (*int32, bool)`

GetServicesOk returns a tuple with the Services field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServices

`func (o *StackStatusEvent) SetServices(v int32)`

SetServices sets Services field to given value.


### GetStackName

`func (o *StackStatusEvent) GetStackName() string`

GetStackName returns the StackName field if non-nil, zero value otherwise.

### GetStackNameOk

`func (o *StackStatusEvent) GetStackNameOk() (*string, bool)`

GetStackNameOk returns a tuple with the StackName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStackName

`func (o *StackStatusEvent) SetStackName(v string)`

SetStackName sets StackName field to given value.


### GetStatus

`func (o *StackStatusEvent) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *StackStatusEvent) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *StackStatusEvent) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetStopped

`func (o *StackStatusEvent) GetStopped() int32`

GetStopped returns the Stopped field if non-nil, zero value otherwise.

### GetStoppedOk

`func (o *StackStatusEvent) GetStoppedOk() (*int32, bool)`

GetStoppedOk returns a tuple with the Stopped field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStopped

`func (o *StackStatusEvent) SetStopped(v int32)`

SetStopped sets Stopped field to given value.


### GetTimestamp

`func (o *StackStatusEvent) GetTimestamp() string`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *StackStatusEvent) GetTimestampOk() (*string, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *StackStatusEvent) SetTimestamp(v string)`

SetTimestamp sets Timestamp field to given value.


### GetType

`func (o *StackStatusEvent) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *StackStatusEvent) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *StackStatusEvent) SetType(v string)`

SetType sets Type field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


