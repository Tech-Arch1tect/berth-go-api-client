# StackDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ComposeFile** | **string** |  | 
**Name** | **string** |  | 
**Path** | **string** |  | 
**ServerId** | **int32** |  | 
**ServerName** | **string** |  | 
**Services** | [**[]ComposeService**](ComposeService.md) |  | 

## Methods

### NewStackDetails

`func NewStackDetails(composeFile string, name string, path string, serverId int32, serverName string, services []ComposeService, ) *StackDetails`

NewStackDetails instantiates a new StackDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStackDetailsWithDefaults

`func NewStackDetailsWithDefaults() *StackDetails`

NewStackDetailsWithDefaults instantiates a new StackDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetComposeFile

`func (o *StackDetails) GetComposeFile() string`

GetComposeFile returns the ComposeFile field if non-nil, zero value otherwise.

### GetComposeFileOk

`func (o *StackDetails) GetComposeFileOk() (*string, bool)`

GetComposeFileOk returns a tuple with the ComposeFile field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComposeFile

`func (o *StackDetails) SetComposeFile(v string)`

SetComposeFile sets ComposeFile field to given value.


### GetName

`func (o *StackDetails) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *StackDetails) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *StackDetails) SetName(v string)`

SetName sets Name field to given value.


### GetPath

`func (o *StackDetails) GetPath() string`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *StackDetails) GetPathOk() (*string, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *StackDetails) SetPath(v string)`

SetPath sets Path field to given value.


### GetServerId

`func (o *StackDetails) GetServerId() int32`

GetServerId returns the ServerId field if non-nil, zero value otherwise.

### GetServerIdOk

`func (o *StackDetails) GetServerIdOk() (*int32, bool)`

GetServerIdOk returns a tuple with the ServerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerId

`func (o *StackDetails) SetServerId(v int32)`

SetServerId sets ServerId field to given value.


### GetServerName

`func (o *StackDetails) GetServerName() string`

GetServerName returns the ServerName field if non-nil, zero value otherwise.

### GetServerNameOk

`func (o *StackDetails) GetServerNameOk() (*string, bool)`

GetServerNameOk returns a tuple with the ServerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerName

`func (o *StackDetails) SetServerName(v string)`

SetServerName sets ServerName field to given value.


### GetServices

`func (o *StackDetails) GetServices() []ComposeService`

GetServices returns the Services field if non-nil, zero value otherwise.

### GetServicesOk

`func (o *StackDetails) GetServicesOk() (*[]ComposeService, bool)`

GetServicesOk returns a tuple with the Services field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServices

`func (o *StackDetails) SetServices(v []ComposeService)`

SetServices sets Services field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


