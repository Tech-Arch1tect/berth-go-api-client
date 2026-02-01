# ImageInspectInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Architecture** | **string** |  | 
**Author** | **string** |  | 
**Config** | [**ImageConfig**](ImageConfig.md) |  | 
**Created** | **string** |  | 
**DockerVersion** | **string** |  | 
**Os** | **string** |  | 
**Parent** | Pointer to **string** |  | [optional] 
**RepoDigests** | Pointer to **[]string** |  | [optional] 
**RepoTags** | Pointer to **[]string** |  | [optional] 
**Rootfs** | [**RootFS**](RootFS.md) |  | 
**Size** | **int32** |  | 
**VirtualSize** | **int32** |  | 

## Methods

### NewImageInspectInfo

`func NewImageInspectInfo(architecture string, author string, config ImageConfig, created string, dockerVersion string, os string, rootfs RootFS, size int32, virtualSize int32, ) *ImageInspectInfo`

NewImageInspectInfo instantiates a new ImageInspectInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImageInspectInfoWithDefaults

`func NewImageInspectInfoWithDefaults() *ImageInspectInfo`

NewImageInspectInfoWithDefaults instantiates a new ImageInspectInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetArchitecture

`func (o *ImageInspectInfo) GetArchitecture() string`

GetArchitecture returns the Architecture field if non-nil, zero value otherwise.

### GetArchitectureOk

`func (o *ImageInspectInfo) GetArchitectureOk() (*string, bool)`

GetArchitectureOk returns a tuple with the Architecture field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchitecture

`func (o *ImageInspectInfo) SetArchitecture(v string)`

SetArchitecture sets Architecture field to given value.


### GetAuthor

`func (o *ImageInspectInfo) GetAuthor() string`

GetAuthor returns the Author field if non-nil, zero value otherwise.

### GetAuthorOk

`func (o *ImageInspectInfo) GetAuthorOk() (*string, bool)`

GetAuthorOk returns a tuple with the Author field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthor

`func (o *ImageInspectInfo) SetAuthor(v string)`

SetAuthor sets Author field to given value.


### GetConfig

`func (o *ImageInspectInfo) GetConfig() ImageConfig`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *ImageInspectInfo) GetConfigOk() (*ImageConfig, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *ImageInspectInfo) SetConfig(v ImageConfig)`

SetConfig sets Config field to given value.


### GetCreated

`func (o *ImageInspectInfo) GetCreated() string`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *ImageInspectInfo) GetCreatedOk() (*string, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *ImageInspectInfo) SetCreated(v string)`

SetCreated sets Created field to given value.


### GetDockerVersion

`func (o *ImageInspectInfo) GetDockerVersion() string`

GetDockerVersion returns the DockerVersion field if non-nil, zero value otherwise.

### GetDockerVersionOk

`func (o *ImageInspectInfo) GetDockerVersionOk() (*string, bool)`

GetDockerVersionOk returns a tuple with the DockerVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDockerVersion

`func (o *ImageInspectInfo) SetDockerVersion(v string)`

SetDockerVersion sets DockerVersion field to given value.


### GetOs

`func (o *ImageInspectInfo) GetOs() string`

GetOs returns the Os field if non-nil, zero value otherwise.

### GetOsOk

`func (o *ImageInspectInfo) GetOsOk() (*string, bool)`

GetOsOk returns a tuple with the Os field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOs

`func (o *ImageInspectInfo) SetOs(v string)`

SetOs sets Os field to given value.


### GetParent

`func (o *ImageInspectInfo) GetParent() string`

GetParent returns the Parent field if non-nil, zero value otherwise.

### GetParentOk

`func (o *ImageInspectInfo) GetParentOk() (*string, bool)`

GetParentOk returns a tuple with the Parent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParent

`func (o *ImageInspectInfo) SetParent(v string)`

SetParent sets Parent field to given value.

### HasParent

`func (o *ImageInspectInfo) HasParent() bool`

HasParent returns a boolean if a field has been set.

### GetRepoDigests

`func (o *ImageInspectInfo) GetRepoDigests() []string`

GetRepoDigests returns the RepoDigests field if non-nil, zero value otherwise.

### GetRepoDigestsOk

`func (o *ImageInspectInfo) GetRepoDigestsOk() (*[]string, bool)`

GetRepoDigestsOk returns a tuple with the RepoDigests field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepoDigests

`func (o *ImageInspectInfo) SetRepoDigests(v []string)`

SetRepoDigests sets RepoDigests field to given value.

### HasRepoDigests

`func (o *ImageInspectInfo) HasRepoDigests() bool`

HasRepoDigests returns a boolean if a field has been set.

### GetRepoTags

`func (o *ImageInspectInfo) GetRepoTags() []string`

GetRepoTags returns the RepoTags field if non-nil, zero value otherwise.

### GetRepoTagsOk

`func (o *ImageInspectInfo) GetRepoTagsOk() (*[]string, bool)`

GetRepoTagsOk returns a tuple with the RepoTags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepoTags

`func (o *ImageInspectInfo) SetRepoTags(v []string)`

SetRepoTags sets RepoTags field to given value.

### HasRepoTags

`func (o *ImageInspectInfo) HasRepoTags() bool`

HasRepoTags returns a boolean if a field has been set.

### GetRootfs

`func (o *ImageInspectInfo) GetRootfs() RootFS`

GetRootfs returns the Rootfs field if non-nil, zero value otherwise.

### GetRootfsOk

`func (o *ImageInspectInfo) GetRootfsOk() (*RootFS, bool)`

GetRootfsOk returns a tuple with the Rootfs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRootfs

`func (o *ImageInspectInfo) SetRootfs(v RootFS)`

SetRootfs sets Rootfs field to given value.


### GetSize

`func (o *ImageInspectInfo) GetSize() int32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *ImageInspectInfo) GetSizeOk() (*int32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *ImageInspectInfo) SetSize(v int32)`

SetSize sets Size field to given value.


### GetVirtualSize

`func (o *ImageInspectInfo) GetVirtualSize() int32`

GetVirtualSize returns the VirtualSize field if non-nil, zero value otherwise.

### GetVirtualSizeOk

`func (o *ImageInspectInfo) GetVirtualSizeOk() (*int32, bool)`

GetVirtualSizeOk returns a tuple with the VirtualSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVirtualSize

`func (o *ImageInspectInfo) SetVirtualSize(v int32)`

SetVirtualSize sets VirtualSize field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


