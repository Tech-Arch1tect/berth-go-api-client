# Stack

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ComposeFile** | **string** |  | 
**IsHealthy** | **bool** |  | 
**Name** | **string** |  | 
**Path** | **string** |  | 
**RunningContainers** | **int32** |  | 
**ServerId** | **int32** |  | 
**ServerName** | **string** |  | 
**TotalContainers** | **int32** |  | 

## Methods

### NewStack

`func NewStack(composeFile string, isHealthy bool, name string, path string, runningContainers int32, serverId int32, serverName string, totalContainers int32, ) *Stack`

NewStack instantiates a new Stack object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStackWithDefaults

`func NewStackWithDefaults() *Stack`

NewStackWithDefaults instantiates a new Stack object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetComposeFile

`func (o *Stack) GetComposeFile() string`

GetComposeFile returns the ComposeFile field if non-nil, zero value otherwise.

### GetComposeFileOk

`func (o *Stack) GetComposeFileOk() (*string, bool)`

GetComposeFileOk returns a tuple with the ComposeFile field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComposeFile

`func (o *Stack) SetComposeFile(v string)`

SetComposeFile sets ComposeFile field to given value.


### GetIsHealthy

`func (o *Stack) GetIsHealthy() bool`

GetIsHealthy returns the IsHealthy field if non-nil, zero value otherwise.

### GetIsHealthyOk

`func (o *Stack) GetIsHealthyOk() (*bool, bool)`

GetIsHealthyOk returns a tuple with the IsHealthy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsHealthy

`func (o *Stack) SetIsHealthy(v bool)`

SetIsHealthy sets IsHealthy field to given value.


### GetName

`func (o *Stack) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Stack) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Stack) SetName(v string)`

SetName sets Name field to given value.


### GetPath

`func (o *Stack) GetPath() string`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *Stack) GetPathOk() (*string, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *Stack) SetPath(v string)`

SetPath sets Path field to given value.


### GetRunningContainers

`func (o *Stack) GetRunningContainers() int32`

GetRunningContainers returns the RunningContainers field if non-nil, zero value otherwise.

### GetRunningContainersOk

`func (o *Stack) GetRunningContainersOk() (*int32, bool)`

GetRunningContainersOk returns a tuple with the RunningContainers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunningContainers

`func (o *Stack) SetRunningContainers(v int32)`

SetRunningContainers sets RunningContainers field to given value.


### GetServerId

`func (o *Stack) GetServerId() int32`

GetServerId returns the ServerId field if non-nil, zero value otherwise.

### GetServerIdOk

`func (o *Stack) GetServerIdOk() (*int32, bool)`

GetServerIdOk returns a tuple with the ServerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerId

`func (o *Stack) SetServerId(v int32)`

SetServerId sets ServerId field to given value.


### GetServerName

`func (o *Stack) GetServerName() string`

GetServerName returns the ServerName field if non-nil, zero value otherwise.

### GetServerNameOk

`func (o *Stack) GetServerNameOk() (*string, bool)`

GetServerNameOk returns a tuple with the ServerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerName

`func (o *Stack) SetServerName(v string)`

SetServerName sets ServerName field to given value.


### GetTotalContainers

`func (o *Stack) GetTotalContainers() int32`

GetTotalContainers returns the TotalContainers field if non-nil, zero value otherwise.

### GetTotalContainersOk

`func (o *Stack) GetTotalContainersOk() (*int32, bool)`

GetTotalContainersOk returns a tuple with the TotalContainers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalContainers

`func (o *Stack) SetTotalContainers(v int32)`

SetTotalContainers sets TotalContainers field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


