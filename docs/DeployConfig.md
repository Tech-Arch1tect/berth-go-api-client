# DeployConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Mode** | Pointer to **NullableString** |  | [optional] 
**Placement** | Pointer to [**NullablePlacementConfig**](PlacementConfig.md) |  | [optional] 
**Replicas** | Pointer to **NullableInt32** |  | [optional] 
**Resources** | Pointer to [**NullableResourcesConfig**](ResourcesConfig.md) |  | [optional] 
**RestartPolicy** | Pointer to [**NullableRestartPolicyConfig**](RestartPolicyConfig.md) |  | [optional] 
**RollbackConfig** | Pointer to [**NullableUpdateRollbackConfig**](UpdateRollbackConfig.md) |  | [optional] 
**UpdateConfig** | Pointer to [**NullableUpdateRollbackConfig**](UpdateRollbackConfig.md) |  | [optional] 

## Methods

### NewDeployConfig

`func NewDeployConfig() *DeployConfig`

NewDeployConfig instantiates a new DeployConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeployConfigWithDefaults

`func NewDeployConfigWithDefaults() *DeployConfig`

NewDeployConfigWithDefaults instantiates a new DeployConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMode

`func (o *DeployConfig) GetMode() string`

GetMode returns the Mode field if non-nil, zero value otherwise.

### GetModeOk

`func (o *DeployConfig) GetModeOk() (*string, bool)`

GetModeOk returns a tuple with the Mode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMode

`func (o *DeployConfig) SetMode(v string)`

SetMode sets Mode field to given value.

### HasMode

`func (o *DeployConfig) HasMode() bool`

HasMode returns a boolean if a field has been set.

### SetModeNil

`func (o *DeployConfig) SetModeNil(b bool)`

 SetModeNil sets the value for Mode to be an explicit nil

### UnsetMode
`func (o *DeployConfig) UnsetMode()`

UnsetMode ensures that no value is present for Mode, not even an explicit nil
### GetPlacement

`func (o *DeployConfig) GetPlacement() PlacementConfig`

GetPlacement returns the Placement field if non-nil, zero value otherwise.

### GetPlacementOk

`func (o *DeployConfig) GetPlacementOk() (*PlacementConfig, bool)`

GetPlacementOk returns a tuple with the Placement field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlacement

`func (o *DeployConfig) SetPlacement(v PlacementConfig)`

SetPlacement sets Placement field to given value.

### HasPlacement

`func (o *DeployConfig) HasPlacement() bool`

HasPlacement returns a boolean if a field has been set.

### SetPlacementNil

`func (o *DeployConfig) SetPlacementNil(b bool)`

 SetPlacementNil sets the value for Placement to be an explicit nil

### UnsetPlacement
`func (o *DeployConfig) UnsetPlacement()`

UnsetPlacement ensures that no value is present for Placement, not even an explicit nil
### GetReplicas

`func (o *DeployConfig) GetReplicas() int32`

GetReplicas returns the Replicas field if non-nil, zero value otherwise.

### GetReplicasOk

`func (o *DeployConfig) GetReplicasOk() (*int32, bool)`

GetReplicasOk returns a tuple with the Replicas field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplicas

`func (o *DeployConfig) SetReplicas(v int32)`

SetReplicas sets Replicas field to given value.

### HasReplicas

`func (o *DeployConfig) HasReplicas() bool`

HasReplicas returns a boolean if a field has been set.

### SetReplicasNil

`func (o *DeployConfig) SetReplicasNil(b bool)`

 SetReplicasNil sets the value for Replicas to be an explicit nil

### UnsetReplicas
`func (o *DeployConfig) UnsetReplicas()`

UnsetReplicas ensures that no value is present for Replicas, not even an explicit nil
### GetResources

`func (o *DeployConfig) GetResources() ResourcesConfig`

GetResources returns the Resources field if non-nil, zero value otherwise.

### GetResourcesOk

`func (o *DeployConfig) GetResourcesOk() (*ResourcesConfig, bool)`

GetResourcesOk returns a tuple with the Resources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResources

`func (o *DeployConfig) SetResources(v ResourcesConfig)`

SetResources sets Resources field to given value.

### HasResources

`func (o *DeployConfig) HasResources() bool`

HasResources returns a boolean if a field has been set.

### SetResourcesNil

`func (o *DeployConfig) SetResourcesNil(b bool)`

 SetResourcesNil sets the value for Resources to be an explicit nil

### UnsetResources
`func (o *DeployConfig) UnsetResources()`

UnsetResources ensures that no value is present for Resources, not even an explicit nil
### GetRestartPolicy

`func (o *DeployConfig) GetRestartPolicy() RestartPolicyConfig`

GetRestartPolicy returns the RestartPolicy field if non-nil, zero value otherwise.

### GetRestartPolicyOk

`func (o *DeployConfig) GetRestartPolicyOk() (*RestartPolicyConfig, bool)`

GetRestartPolicyOk returns a tuple with the RestartPolicy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRestartPolicy

`func (o *DeployConfig) SetRestartPolicy(v RestartPolicyConfig)`

SetRestartPolicy sets RestartPolicy field to given value.

### HasRestartPolicy

`func (o *DeployConfig) HasRestartPolicy() bool`

HasRestartPolicy returns a boolean if a field has been set.

### SetRestartPolicyNil

`func (o *DeployConfig) SetRestartPolicyNil(b bool)`

 SetRestartPolicyNil sets the value for RestartPolicy to be an explicit nil

### UnsetRestartPolicy
`func (o *DeployConfig) UnsetRestartPolicy()`

UnsetRestartPolicy ensures that no value is present for RestartPolicy, not even an explicit nil
### GetRollbackConfig

`func (o *DeployConfig) GetRollbackConfig() UpdateRollbackConfig`

GetRollbackConfig returns the RollbackConfig field if non-nil, zero value otherwise.

### GetRollbackConfigOk

`func (o *DeployConfig) GetRollbackConfigOk() (*UpdateRollbackConfig, bool)`

GetRollbackConfigOk returns a tuple with the RollbackConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRollbackConfig

`func (o *DeployConfig) SetRollbackConfig(v UpdateRollbackConfig)`

SetRollbackConfig sets RollbackConfig field to given value.

### HasRollbackConfig

`func (o *DeployConfig) HasRollbackConfig() bool`

HasRollbackConfig returns a boolean if a field has been set.

### SetRollbackConfigNil

`func (o *DeployConfig) SetRollbackConfigNil(b bool)`

 SetRollbackConfigNil sets the value for RollbackConfig to be an explicit nil

### UnsetRollbackConfig
`func (o *DeployConfig) UnsetRollbackConfig()`

UnsetRollbackConfig ensures that no value is present for RollbackConfig, not even an explicit nil
### GetUpdateConfig

`func (o *DeployConfig) GetUpdateConfig() UpdateRollbackConfig`

GetUpdateConfig returns the UpdateConfig field if non-nil, zero value otherwise.

### GetUpdateConfigOk

`func (o *DeployConfig) GetUpdateConfigOk() (*UpdateRollbackConfig, bool)`

GetUpdateConfigOk returns a tuple with the UpdateConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdateConfig

`func (o *DeployConfig) SetUpdateConfig(v UpdateRollbackConfig)`

SetUpdateConfig sets UpdateConfig field to given value.

### HasUpdateConfig

`func (o *DeployConfig) HasUpdateConfig() bool`

HasUpdateConfig returns a boolean if a field has been set.

### SetUpdateConfigNil

`func (o *DeployConfig) SetUpdateConfigNil(b bool)`

 SetUpdateConfigNil sets the value for UpdateConfig to be an explicit nil

### UnsetUpdateConfig
`func (o *DeployConfig) UnsetUpdateConfig()`

UnsetUpdateConfig ensures that no value is present for UpdateConfig, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


