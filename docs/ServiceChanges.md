# ServiceChanges

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Build** | Pointer to [**NullableBuildConfig**](BuildConfig.md) |  | [optional] 
**Command** | Pointer to [**NullableCommandConfig**](CommandConfig.md) |  | [optional] 
**DependsOn** | Pointer to [**map[string]DependsOnConfig**](DependsOnConfig.md) |  | [optional] 
**Deploy** | Pointer to [**NullableDeployConfig**](DeployConfig.md) |  | [optional] 
**Entrypoint** | Pointer to [**NullableCommandConfig**](CommandConfig.md) |  | [optional] 
**Environment** | Pointer to **map[string]string** |  | [optional] 
**Healthcheck** | Pointer to [**NullableHealthcheckConfig**](HealthcheckConfig.md) |  | [optional] 
**Image** | Pointer to **NullableString** |  | [optional] 
**Labels** | Pointer to **map[string]string** |  | [optional] 
**Networks** | Pointer to [**map[string]ServiceNetworkConfig**](ServiceNetworkConfig.md) |  | [optional] 
**Ports** | Pointer to [**[]PortMapping**](PortMapping.md) |  | [optional] 
**Restart** | Pointer to **NullableString** |  | [optional] 
**Volumes** | Pointer to [**[]VolumeMount2**](VolumeMount2.md) |  | [optional] 

## Methods

### NewServiceChanges

`func NewServiceChanges() *ServiceChanges`

NewServiceChanges instantiates a new ServiceChanges object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewServiceChangesWithDefaults

`func NewServiceChangesWithDefaults() *ServiceChanges`

NewServiceChangesWithDefaults instantiates a new ServiceChanges object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBuild

`func (o *ServiceChanges) GetBuild() BuildConfig`

GetBuild returns the Build field if non-nil, zero value otherwise.

### GetBuildOk

`func (o *ServiceChanges) GetBuildOk() (*BuildConfig, bool)`

GetBuildOk returns a tuple with the Build field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuild

`func (o *ServiceChanges) SetBuild(v BuildConfig)`

SetBuild sets Build field to given value.

### HasBuild

`func (o *ServiceChanges) HasBuild() bool`

HasBuild returns a boolean if a field has been set.

### SetBuildNil

`func (o *ServiceChanges) SetBuildNil(b bool)`

 SetBuildNil sets the value for Build to be an explicit nil

### UnsetBuild
`func (o *ServiceChanges) UnsetBuild()`

UnsetBuild ensures that no value is present for Build, not even an explicit nil
### GetCommand

`func (o *ServiceChanges) GetCommand() CommandConfig`

GetCommand returns the Command field if non-nil, zero value otherwise.

### GetCommandOk

`func (o *ServiceChanges) GetCommandOk() (*CommandConfig, bool)`

GetCommandOk returns a tuple with the Command field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommand

`func (o *ServiceChanges) SetCommand(v CommandConfig)`

SetCommand sets Command field to given value.

### HasCommand

`func (o *ServiceChanges) HasCommand() bool`

HasCommand returns a boolean if a field has been set.

### SetCommandNil

`func (o *ServiceChanges) SetCommandNil(b bool)`

 SetCommandNil sets the value for Command to be an explicit nil

### UnsetCommand
`func (o *ServiceChanges) UnsetCommand()`

UnsetCommand ensures that no value is present for Command, not even an explicit nil
### GetDependsOn

`func (o *ServiceChanges) GetDependsOn() map[string]DependsOnConfig`

GetDependsOn returns the DependsOn field if non-nil, zero value otherwise.

### GetDependsOnOk

`func (o *ServiceChanges) GetDependsOnOk() (*map[string]DependsOnConfig, bool)`

GetDependsOnOk returns a tuple with the DependsOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDependsOn

`func (o *ServiceChanges) SetDependsOn(v map[string]DependsOnConfig)`

SetDependsOn sets DependsOn field to given value.

### HasDependsOn

`func (o *ServiceChanges) HasDependsOn() bool`

HasDependsOn returns a boolean if a field has been set.

### GetDeploy

`func (o *ServiceChanges) GetDeploy() DeployConfig`

GetDeploy returns the Deploy field if non-nil, zero value otherwise.

### GetDeployOk

`func (o *ServiceChanges) GetDeployOk() (*DeployConfig, bool)`

GetDeployOk returns a tuple with the Deploy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeploy

`func (o *ServiceChanges) SetDeploy(v DeployConfig)`

SetDeploy sets Deploy field to given value.

### HasDeploy

`func (o *ServiceChanges) HasDeploy() bool`

HasDeploy returns a boolean if a field has been set.

### SetDeployNil

`func (o *ServiceChanges) SetDeployNil(b bool)`

 SetDeployNil sets the value for Deploy to be an explicit nil

### UnsetDeploy
`func (o *ServiceChanges) UnsetDeploy()`

UnsetDeploy ensures that no value is present for Deploy, not even an explicit nil
### GetEntrypoint

`func (o *ServiceChanges) GetEntrypoint() CommandConfig`

GetEntrypoint returns the Entrypoint field if non-nil, zero value otherwise.

### GetEntrypointOk

`func (o *ServiceChanges) GetEntrypointOk() (*CommandConfig, bool)`

GetEntrypointOk returns a tuple with the Entrypoint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntrypoint

`func (o *ServiceChanges) SetEntrypoint(v CommandConfig)`

SetEntrypoint sets Entrypoint field to given value.

### HasEntrypoint

`func (o *ServiceChanges) HasEntrypoint() bool`

HasEntrypoint returns a boolean if a field has been set.

### SetEntrypointNil

`func (o *ServiceChanges) SetEntrypointNil(b bool)`

 SetEntrypointNil sets the value for Entrypoint to be an explicit nil

### UnsetEntrypoint
`func (o *ServiceChanges) UnsetEntrypoint()`

UnsetEntrypoint ensures that no value is present for Entrypoint, not even an explicit nil
### GetEnvironment

`func (o *ServiceChanges) GetEnvironment() map[string]string`

GetEnvironment returns the Environment field if non-nil, zero value otherwise.

### GetEnvironmentOk

`func (o *ServiceChanges) GetEnvironmentOk() (*map[string]string, bool)`

GetEnvironmentOk returns a tuple with the Environment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnvironment

`func (o *ServiceChanges) SetEnvironment(v map[string]string)`

SetEnvironment sets Environment field to given value.

### HasEnvironment

`func (o *ServiceChanges) HasEnvironment() bool`

HasEnvironment returns a boolean if a field has been set.

### GetHealthcheck

`func (o *ServiceChanges) GetHealthcheck() HealthcheckConfig`

GetHealthcheck returns the Healthcheck field if non-nil, zero value otherwise.

### GetHealthcheckOk

`func (o *ServiceChanges) GetHealthcheckOk() (*HealthcheckConfig, bool)`

GetHealthcheckOk returns a tuple with the Healthcheck field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHealthcheck

`func (o *ServiceChanges) SetHealthcheck(v HealthcheckConfig)`

SetHealthcheck sets Healthcheck field to given value.

### HasHealthcheck

`func (o *ServiceChanges) HasHealthcheck() bool`

HasHealthcheck returns a boolean if a field has been set.

### SetHealthcheckNil

`func (o *ServiceChanges) SetHealthcheckNil(b bool)`

 SetHealthcheckNil sets the value for Healthcheck to be an explicit nil

### UnsetHealthcheck
`func (o *ServiceChanges) UnsetHealthcheck()`

UnsetHealthcheck ensures that no value is present for Healthcheck, not even an explicit nil
### GetImage

`func (o *ServiceChanges) GetImage() string`

GetImage returns the Image field if non-nil, zero value otherwise.

### GetImageOk

`func (o *ServiceChanges) GetImageOk() (*string, bool)`

GetImageOk returns a tuple with the Image field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImage

`func (o *ServiceChanges) SetImage(v string)`

SetImage sets Image field to given value.

### HasImage

`func (o *ServiceChanges) HasImage() bool`

HasImage returns a boolean if a field has been set.

### SetImageNil

`func (o *ServiceChanges) SetImageNil(b bool)`

 SetImageNil sets the value for Image to be an explicit nil

### UnsetImage
`func (o *ServiceChanges) UnsetImage()`

UnsetImage ensures that no value is present for Image, not even an explicit nil
### GetLabels

`func (o *ServiceChanges) GetLabels() map[string]string`

GetLabels returns the Labels field if non-nil, zero value otherwise.

### GetLabelsOk

`func (o *ServiceChanges) GetLabelsOk() (*map[string]string, bool)`

GetLabelsOk returns a tuple with the Labels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabels

`func (o *ServiceChanges) SetLabels(v map[string]string)`

SetLabels sets Labels field to given value.

### HasLabels

`func (o *ServiceChanges) HasLabels() bool`

HasLabels returns a boolean if a field has been set.

### GetNetworks

`func (o *ServiceChanges) GetNetworks() map[string]ServiceNetworkConfig`

GetNetworks returns the Networks field if non-nil, zero value otherwise.

### GetNetworksOk

`func (o *ServiceChanges) GetNetworksOk() (*map[string]ServiceNetworkConfig, bool)`

GetNetworksOk returns a tuple with the Networks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworks

`func (o *ServiceChanges) SetNetworks(v map[string]ServiceNetworkConfig)`

SetNetworks sets Networks field to given value.

### HasNetworks

`func (o *ServiceChanges) HasNetworks() bool`

HasNetworks returns a boolean if a field has been set.

### GetPorts

`func (o *ServiceChanges) GetPorts() []PortMapping`

GetPorts returns the Ports field if non-nil, zero value otherwise.

### GetPortsOk

`func (o *ServiceChanges) GetPortsOk() (*[]PortMapping, bool)`

GetPortsOk returns a tuple with the Ports field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPorts

`func (o *ServiceChanges) SetPorts(v []PortMapping)`

SetPorts sets Ports field to given value.

### HasPorts

`func (o *ServiceChanges) HasPorts() bool`

HasPorts returns a boolean if a field has been set.

### GetRestart

`func (o *ServiceChanges) GetRestart() string`

GetRestart returns the Restart field if non-nil, zero value otherwise.

### GetRestartOk

`func (o *ServiceChanges) GetRestartOk() (*string, bool)`

GetRestartOk returns a tuple with the Restart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRestart

`func (o *ServiceChanges) SetRestart(v string)`

SetRestart sets Restart field to given value.

### HasRestart

`func (o *ServiceChanges) HasRestart() bool`

HasRestart returns a boolean if a field has been set.

### SetRestartNil

`func (o *ServiceChanges) SetRestartNil(b bool)`

 SetRestartNil sets the value for Restart to be an explicit nil

### UnsetRestart
`func (o *ServiceChanges) UnsetRestart()`

UnsetRestart ensures that no value is present for Restart, not even an explicit nil
### GetVolumes

`func (o *ServiceChanges) GetVolumes() []VolumeMount2`

GetVolumes returns the Volumes field if non-nil, zero value otherwise.

### GetVolumesOk

`func (o *ServiceChanges) GetVolumesOk() (*[]VolumeMount2, bool)`

GetVolumesOk returns a tuple with the Volumes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVolumes

`func (o *ServiceChanges) SetVolumes(v []VolumeMount2)`

SetVolumes sets Volumes field to given value.

### HasVolumes

`func (o *ServiceChanges) HasVolumes() bool`

HasVolumes returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


