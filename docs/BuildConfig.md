# BuildConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Args** | Pointer to **map[string]string** |  | [optional] 
**CacheFrom** | Pointer to **[]string** |  | [optional] 
**CacheTo** | Pointer to **[]string** |  | [optional] 
**Context** | Pointer to **string** |  | [optional] 
**Dockerfile** | Pointer to **string** |  | [optional] 
**Platforms** | Pointer to **[]string** |  | [optional] 
**Target** | Pointer to **string** |  | [optional] 

## Methods

### NewBuildConfig

`func NewBuildConfig() *BuildConfig`

NewBuildConfig instantiates a new BuildConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBuildConfigWithDefaults

`func NewBuildConfigWithDefaults() *BuildConfig`

NewBuildConfigWithDefaults instantiates a new BuildConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetArgs

`func (o *BuildConfig) GetArgs() map[string]string`

GetArgs returns the Args field if non-nil, zero value otherwise.

### GetArgsOk

`func (o *BuildConfig) GetArgsOk() (*map[string]string, bool)`

GetArgsOk returns a tuple with the Args field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArgs

`func (o *BuildConfig) SetArgs(v map[string]string)`

SetArgs sets Args field to given value.

### HasArgs

`func (o *BuildConfig) HasArgs() bool`

HasArgs returns a boolean if a field has been set.

### GetCacheFrom

`func (o *BuildConfig) GetCacheFrom() []string`

GetCacheFrom returns the CacheFrom field if non-nil, zero value otherwise.

### GetCacheFromOk

`func (o *BuildConfig) GetCacheFromOk() (*[]string, bool)`

GetCacheFromOk returns a tuple with the CacheFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCacheFrom

`func (o *BuildConfig) SetCacheFrom(v []string)`

SetCacheFrom sets CacheFrom field to given value.

### HasCacheFrom

`func (o *BuildConfig) HasCacheFrom() bool`

HasCacheFrom returns a boolean if a field has been set.

### GetCacheTo

`func (o *BuildConfig) GetCacheTo() []string`

GetCacheTo returns the CacheTo field if non-nil, zero value otherwise.

### GetCacheToOk

`func (o *BuildConfig) GetCacheToOk() (*[]string, bool)`

GetCacheToOk returns a tuple with the CacheTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCacheTo

`func (o *BuildConfig) SetCacheTo(v []string)`

SetCacheTo sets CacheTo field to given value.

### HasCacheTo

`func (o *BuildConfig) HasCacheTo() bool`

HasCacheTo returns a boolean if a field has been set.

### GetContext

`func (o *BuildConfig) GetContext() string`

GetContext returns the Context field if non-nil, zero value otherwise.

### GetContextOk

`func (o *BuildConfig) GetContextOk() (*string, bool)`

GetContextOk returns a tuple with the Context field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContext

`func (o *BuildConfig) SetContext(v string)`

SetContext sets Context field to given value.

### HasContext

`func (o *BuildConfig) HasContext() bool`

HasContext returns a boolean if a field has been set.

### GetDockerfile

`func (o *BuildConfig) GetDockerfile() string`

GetDockerfile returns the Dockerfile field if non-nil, zero value otherwise.

### GetDockerfileOk

`func (o *BuildConfig) GetDockerfileOk() (*string, bool)`

GetDockerfileOk returns a tuple with the Dockerfile field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDockerfile

`func (o *BuildConfig) SetDockerfile(v string)`

SetDockerfile sets Dockerfile field to given value.

### HasDockerfile

`func (o *BuildConfig) HasDockerfile() bool`

HasDockerfile returns a boolean if a field has been set.

### GetPlatforms

`func (o *BuildConfig) GetPlatforms() []string`

GetPlatforms returns the Platforms field if non-nil, zero value otherwise.

### GetPlatformsOk

`func (o *BuildConfig) GetPlatformsOk() (*[]string, bool)`

GetPlatformsOk returns a tuple with the Platforms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatforms

`func (o *BuildConfig) SetPlatforms(v []string)`

SetPlatforms sets Platforms field to given value.

### HasPlatforms

`func (o *BuildConfig) HasPlatforms() bool`

HasPlatforms returns a boolean if a field has been set.

### GetTarget

`func (o *BuildConfig) GetTarget() string`

GetTarget returns the Target field if non-nil, zero value otherwise.

### GetTargetOk

`func (o *BuildConfig) GetTargetOk() (*string, bool)`

GetTargetOk returns a tuple with the Target field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTarget

`func (o *BuildConfig) SetTarget(v string)`

SetTarget sets Target field to given value.

### HasTarget

`func (o *BuildConfig) HasTarget() bool`

HasTarget returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


