# Container

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Command** | Pointer to **[]string** |  | [optional] 
**Created** | Pointer to **string** |  | [optional] 
**ExitCode** | Pointer to **NullableInt32** |  | [optional] 
**Finished** | Pointer to **string** |  | [optional] 
**Health** | Pointer to [**NullableHealthStatus**](HealthStatus.md) |  | [optional] 
**Image** | **string** |  | 
**Labels** | Pointer to **map[string]string** |  | [optional] 
**Mounts** | Pointer to [**[]ContainerMount**](ContainerMount.md) |  | [optional] 
**Name** | **string** |  | 
**Networks** | Pointer to [**[]ContainerNetwork**](ContainerNetwork.md) |  | [optional] 
**Ports** | Pointer to [**[]Port**](Port.md) |  | [optional] 
**ResourceLimits** | Pointer to [**NullableResourceLimits**](ResourceLimits.md) |  | [optional] 
**RestartPolicy** | Pointer to [**NullableRestartPolicy**](RestartPolicy.md) |  | [optional] 
**Started** | Pointer to **string** |  | [optional] 
**State** | **string** |  | 
**User** | Pointer to **string** |  | [optional] 
**WorkingDir** | Pointer to **string** |  | [optional] 

## Methods

### NewContainer

`func NewContainer(image string, name string, state string, ) *Container`

NewContainer instantiates a new Container object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContainerWithDefaults

`func NewContainerWithDefaults() *Container`

NewContainerWithDefaults instantiates a new Container object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCommand

`func (o *Container) GetCommand() []string`

GetCommand returns the Command field if non-nil, zero value otherwise.

### GetCommandOk

`func (o *Container) GetCommandOk() (*[]string, bool)`

GetCommandOk returns a tuple with the Command field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommand

`func (o *Container) SetCommand(v []string)`

SetCommand sets Command field to given value.

### HasCommand

`func (o *Container) HasCommand() bool`

HasCommand returns a boolean if a field has been set.

### GetCreated

`func (o *Container) GetCreated() string`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *Container) GetCreatedOk() (*string, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *Container) SetCreated(v string)`

SetCreated sets Created field to given value.

### HasCreated

`func (o *Container) HasCreated() bool`

HasCreated returns a boolean if a field has been set.

### GetExitCode

`func (o *Container) GetExitCode() int32`

GetExitCode returns the ExitCode field if non-nil, zero value otherwise.

### GetExitCodeOk

`func (o *Container) GetExitCodeOk() (*int32, bool)`

GetExitCodeOk returns a tuple with the ExitCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExitCode

`func (o *Container) SetExitCode(v int32)`

SetExitCode sets ExitCode field to given value.

### HasExitCode

`func (o *Container) HasExitCode() bool`

HasExitCode returns a boolean if a field has been set.

### SetExitCodeNil

`func (o *Container) SetExitCodeNil(b bool)`

 SetExitCodeNil sets the value for ExitCode to be an explicit nil

### UnsetExitCode
`func (o *Container) UnsetExitCode()`

UnsetExitCode ensures that no value is present for ExitCode, not even an explicit nil
### GetFinished

`func (o *Container) GetFinished() string`

GetFinished returns the Finished field if non-nil, zero value otherwise.

### GetFinishedOk

`func (o *Container) GetFinishedOk() (*string, bool)`

GetFinishedOk returns a tuple with the Finished field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinished

`func (o *Container) SetFinished(v string)`

SetFinished sets Finished field to given value.

### HasFinished

`func (o *Container) HasFinished() bool`

HasFinished returns a boolean if a field has been set.

### GetHealth

`func (o *Container) GetHealth() HealthStatus`

GetHealth returns the Health field if non-nil, zero value otherwise.

### GetHealthOk

`func (o *Container) GetHealthOk() (*HealthStatus, bool)`

GetHealthOk returns a tuple with the Health field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHealth

`func (o *Container) SetHealth(v HealthStatus)`

SetHealth sets Health field to given value.

### HasHealth

`func (o *Container) HasHealth() bool`

HasHealth returns a boolean if a field has been set.

### SetHealthNil

`func (o *Container) SetHealthNil(b bool)`

 SetHealthNil sets the value for Health to be an explicit nil

### UnsetHealth
`func (o *Container) UnsetHealth()`

UnsetHealth ensures that no value is present for Health, not even an explicit nil
### GetImage

`func (o *Container) GetImage() string`

GetImage returns the Image field if non-nil, zero value otherwise.

### GetImageOk

`func (o *Container) GetImageOk() (*string, bool)`

GetImageOk returns a tuple with the Image field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImage

`func (o *Container) SetImage(v string)`

SetImage sets Image field to given value.


### GetLabels

`func (o *Container) GetLabels() map[string]string`

GetLabels returns the Labels field if non-nil, zero value otherwise.

### GetLabelsOk

`func (o *Container) GetLabelsOk() (*map[string]string, bool)`

GetLabelsOk returns a tuple with the Labels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabels

`func (o *Container) SetLabels(v map[string]string)`

SetLabels sets Labels field to given value.

### HasLabels

`func (o *Container) HasLabels() bool`

HasLabels returns a boolean if a field has been set.

### GetMounts

`func (o *Container) GetMounts() []ContainerMount`

GetMounts returns the Mounts field if non-nil, zero value otherwise.

### GetMountsOk

`func (o *Container) GetMountsOk() (*[]ContainerMount, bool)`

GetMountsOk returns a tuple with the Mounts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMounts

`func (o *Container) SetMounts(v []ContainerMount)`

SetMounts sets Mounts field to given value.

### HasMounts

`func (o *Container) HasMounts() bool`

HasMounts returns a boolean if a field has been set.

### GetName

`func (o *Container) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Container) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Container) SetName(v string)`

SetName sets Name field to given value.


### GetNetworks

`func (o *Container) GetNetworks() []ContainerNetwork`

GetNetworks returns the Networks field if non-nil, zero value otherwise.

### GetNetworksOk

`func (o *Container) GetNetworksOk() (*[]ContainerNetwork, bool)`

GetNetworksOk returns a tuple with the Networks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworks

`func (o *Container) SetNetworks(v []ContainerNetwork)`

SetNetworks sets Networks field to given value.

### HasNetworks

`func (o *Container) HasNetworks() bool`

HasNetworks returns a boolean if a field has been set.

### GetPorts

`func (o *Container) GetPorts() []Port`

GetPorts returns the Ports field if non-nil, zero value otherwise.

### GetPortsOk

`func (o *Container) GetPortsOk() (*[]Port, bool)`

GetPortsOk returns a tuple with the Ports field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPorts

`func (o *Container) SetPorts(v []Port)`

SetPorts sets Ports field to given value.

### HasPorts

`func (o *Container) HasPorts() bool`

HasPorts returns a boolean if a field has been set.

### GetResourceLimits

`func (o *Container) GetResourceLimits() ResourceLimits`

GetResourceLimits returns the ResourceLimits field if non-nil, zero value otherwise.

### GetResourceLimitsOk

`func (o *Container) GetResourceLimitsOk() (*ResourceLimits, bool)`

GetResourceLimitsOk returns a tuple with the ResourceLimits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResourceLimits

`func (o *Container) SetResourceLimits(v ResourceLimits)`

SetResourceLimits sets ResourceLimits field to given value.

### HasResourceLimits

`func (o *Container) HasResourceLimits() bool`

HasResourceLimits returns a boolean if a field has been set.

### SetResourceLimitsNil

`func (o *Container) SetResourceLimitsNil(b bool)`

 SetResourceLimitsNil sets the value for ResourceLimits to be an explicit nil

### UnsetResourceLimits
`func (o *Container) UnsetResourceLimits()`

UnsetResourceLimits ensures that no value is present for ResourceLimits, not even an explicit nil
### GetRestartPolicy

`func (o *Container) GetRestartPolicy() RestartPolicy`

GetRestartPolicy returns the RestartPolicy field if non-nil, zero value otherwise.

### GetRestartPolicyOk

`func (o *Container) GetRestartPolicyOk() (*RestartPolicy, bool)`

GetRestartPolicyOk returns a tuple with the RestartPolicy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRestartPolicy

`func (o *Container) SetRestartPolicy(v RestartPolicy)`

SetRestartPolicy sets RestartPolicy field to given value.

### HasRestartPolicy

`func (o *Container) HasRestartPolicy() bool`

HasRestartPolicy returns a boolean if a field has been set.

### SetRestartPolicyNil

`func (o *Container) SetRestartPolicyNil(b bool)`

 SetRestartPolicyNil sets the value for RestartPolicy to be an explicit nil

### UnsetRestartPolicy
`func (o *Container) UnsetRestartPolicy()`

UnsetRestartPolicy ensures that no value is present for RestartPolicy, not even an explicit nil
### GetStarted

`func (o *Container) GetStarted() string`

GetStarted returns the Started field if non-nil, zero value otherwise.

### GetStartedOk

`func (o *Container) GetStartedOk() (*string, bool)`

GetStartedOk returns a tuple with the Started field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStarted

`func (o *Container) SetStarted(v string)`

SetStarted sets Started field to given value.

### HasStarted

`func (o *Container) HasStarted() bool`

HasStarted returns a boolean if a field has been set.

### GetState

`func (o *Container) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *Container) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *Container) SetState(v string)`

SetState sets State field to given value.


### GetUser

`func (o *Container) GetUser() string`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *Container) GetUserOk() (*string, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *Container) SetUser(v string)`

SetUser sets User field to given value.

### HasUser

`func (o *Container) HasUser() bool`

HasUser returns a boolean if a field has been set.

### GetWorkingDir

`func (o *Container) GetWorkingDir() string`

GetWorkingDir returns the WorkingDir field if non-nil, zero value otherwise.

### GetWorkingDirOk

`func (o *Container) GetWorkingDirOk() (*string, bool)`

GetWorkingDirOk returns a tuple with the WorkingDir field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkingDir

`func (o *Container) SetWorkingDir(v string)`

SetWorkingDir sets WorkingDir field to given value.

### HasWorkingDir

`func (o *Container) HasWorkingDir() bool`

HasWorkingDir returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


