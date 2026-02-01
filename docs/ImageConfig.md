# ImageConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Cmd** | Pointer to **[]string** |  | [optional] 
**Entrypoint** | Pointer to **[]string** |  | [optional] 
**Env** | Pointer to **[]string** |  | [optional] 
**ExposedPorts** | Pointer to **map[string]map[string]interface{}** |  | [optional] 
**Labels** | Pointer to **map[string]string** |  | [optional] 
**User** | Pointer to **string** |  | [optional] 
**WorkingDir** | Pointer to **string** |  | [optional] 

## Methods

### NewImageConfig

`func NewImageConfig() *ImageConfig`

NewImageConfig instantiates a new ImageConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImageConfigWithDefaults

`func NewImageConfigWithDefaults() *ImageConfig`

NewImageConfigWithDefaults instantiates a new ImageConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCmd

`func (o *ImageConfig) GetCmd() []string`

GetCmd returns the Cmd field if non-nil, zero value otherwise.

### GetCmdOk

`func (o *ImageConfig) GetCmdOk() (*[]string, bool)`

GetCmdOk returns a tuple with the Cmd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCmd

`func (o *ImageConfig) SetCmd(v []string)`

SetCmd sets Cmd field to given value.

### HasCmd

`func (o *ImageConfig) HasCmd() bool`

HasCmd returns a boolean if a field has been set.

### GetEntrypoint

`func (o *ImageConfig) GetEntrypoint() []string`

GetEntrypoint returns the Entrypoint field if non-nil, zero value otherwise.

### GetEntrypointOk

`func (o *ImageConfig) GetEntrypointOk() (*[]string, bool)`

GetEntrypointOk returns a tuple with the Entrypoint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntrypoint

`func (o *ImageConfig) SetEntrypoint(v []string)`

SetEntrypoint sets Entrypoint field to given value.

### HasEntrypoint

`func (o *ImageConfig) HasEntrypoint() bool`

HasEntrypoint returns a boolean if a field has been set.

### GetEnv

`func (o *ImageConfig) GetEnv() []string`

GetEnv returns the Env field if non-nil, zero value otherwise.

### GetEnvOk

`func (o *ImageConfig) GetEnvOk() (*[]string, bool)`

GetEnvOk returns a tuple with the Env field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnv

`func (o *ImageConfig) SetEnv(v []string)`

SetEnv sets Env field to given value.

### HasEnv

`func (o *ImageConfig) HasEnv() bool`

HasEnv returns a boolean if a field has been set.

### GetExposedPorts

`func (o *ImageConfig) GetExposedPorts() map[string]map[string]interface{}`

GetExposedPorts returns the ExposedPorts field if non-nil, zero value otherwise.

### GetExposedPortsOk

`func (o *ImageConfig) GetExposedPortsOk() (*map[string]map[string]interface{}, bool)`

GetExposedPortsOk returns a tuple with the ExposedPorts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExposedPorts

`func (o *ImageConfig) SetExposedPorts(v map[string]map[string]interface{})`

SetExposedPorts sets ExposedPorts field to given value.

### HasExposedPorts

`func (o *ImageConfig) HasExposedPorts() bool`

HasExposedPorts returns a boolean if a field has been set.

### GetLabels

`func (o *ImageConfig) GetLabels() map[string]string`

GetLabels returns the Labels field if non-nil, zero value otherwise.

### GetLabelsOk

`func (o *ImageConfig) GetLabelsOk() (*map[string]string, bool)`

GetLabelsOk returns a tuple with the Labels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabels

`func (o *ImageConfig) SetLabels(v map[string]string)`

SetLabels sets Labels field to given value.

### HasLabels

`func (o *ImageConfig) HasLabels() bool`

HasLabels returns a boolean if a field has been set.

### GetUser

`func (o *ImageConfig) GetUser() string`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *ImageConfig) GetUserOk() (*string, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *ImageConfig) SetUser(v string)`

SetUser sets User field to given value.

### HasUser

`func (o *ImageConfig) HasUser() bool`

HasUser returns a boolean if a field has been set.

### GetWorkingDir

`func (o *ImageConfig) GetWorkingDir() string`

GetWorkingDir returns the WorkingDir field if non-nil, zero value otherwise.

### GetWorkingDirOk

`func (o *ImageConfig) GetWorkingDirOk() (*string, bool)`

GetWorkingDirOk returns a tuple with the WorkingDir field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkingDir

`func (o *ImageConfig) SetWorkingDir(v string)`

SetWorkingDir sets WorkingDir field to given value.

### HasWorkingDir

`func (o *ImageConfig) HasWorkingDir() bool`

HasWorkingDir returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


