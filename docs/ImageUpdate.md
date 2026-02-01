# ImageUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CheckError** | **string** |  | 
**ContainerName** | **string** |  | 
**CreatedAt** | **time.Time** |  | 
**CurrentImageName** | **string** |  | 
**CurrentRepoDigest** | **string** |  | 
**Id** | **int32** |  | 
**LastCheckedAt** | **NullableTime** |  | 
**LatestRepoDigest** | **string** |  | 
**ServerId** | **int32** |  | 
**StackName** | **string** |  | 
**UpdateAvailable** | **bool** |  | 
**UpdatedAt** | **time.Time** |  | 

## Methods

### NewImageUpdate

`func NewImageUpdate(checkError string, containerName string, createdAt time.Time, currentImageName string, currentRepoDigest string, id int32, lastCheckedAt NullableTime, latestRepoDigest string, serverId int32, stackName string, updateAvailable bool, updatedAt time.Time, ) *ImageUpdate`

NewImageUpdate instantiates a new ImageUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImageUpdateWithDefaults

`func NewImageUpdateWithDefaults() *ImageUpdate`

NewImageUpdateWithDefaults instantiates a new ImageUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCheckError

`func (o *ImageUpdate) GetCheckError() string`

GetCheckError returns the CheckError field if non-nil, zero value otherwise.

### GetCheckErrorOk

`func (o *ImageUpdate) GetCheckErrorOk() (*string, bool)`

GetCheckErrorOk returns a tuple with the CheckError field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckError

`func (o *ImageUpdate) SetCheckError(v string)`

SetCheckError sets CheckError field to given value.


### GetContainerName

`func (o *ImageUpdate) GetContainerName() string`

GetContainerName returns the ContainerName field if non-nil, zero value otherwise.

### GetContainerNameOk

`func (o *ImageUpdate) GetContainerNameOk() (*string, bool)`

GetContainerNameOk returns a tuple with the ContainerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainerName

`func (o *ImageUpdate) SetContainerName(v string)`

SetContainerName sets ContainerName field to given value.


### GetCreatedAt

`func (o *ImageUpdate) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ImageUpdate) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ImageUpdate) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetCurrentImageName

`func (o *ImageUpdate) GetCurrentImageName() string`

GetCurrentImageName returns the CurrentImageName field if non-nil, zero value otherwise.

### GetCurrentImageNameOk

`func (o *ImageUpdate) GetCurrentImageNameOk() (*string, bool)`

GetCurrentImageNameOk returns a tuple with the CurrentImageName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentImageName

`func (o *ImageUpdate) SetCurrentImageName(v string)`

SetCurrentImageName sets CurrentImageName field to given value.


### GetCurrentRepoDigest

`func (o *ImageUpdate) GetCurrentRepoDigest() string`

GetCurrentRepoDigest returns the CurrentRepoDigest field if non-nil, zero value otherwise.

### GetCurrentRepoDigestOk

`func (o *ImageUpdate) GetCurrentRepoDigestOk() (*string, bool)`

GetCurrentRepoDigestOk returns a tuple with the CurrentRepoDigest field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentRepoDigest

`func (o *ImageUpdate) SetCurrentRepoDigest(v string)`

SetCurrentRepoDigest sets CurrentRepoDigest field to given value.


### GetId

`func (o *ImageUpdate) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ImageUpdate) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ImageUpdate) SetId(v int32)`

SetId sets Id field to given value.


### GetLastCheckedAt

`func (o *ImageUpdate) GetLastCheckedAt() time.Time`

GetLastCheckedAt returns the LastCheckedAt field if non-nil, zero value otherwise.

### GetLastCheckedAtOk

`func (o *ImageUpdate) GetLastCheckedAtOk() (*time.Time, bool)`

GetLastCheckedAtOk returns a tuple with the LastCheckedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastCheckedAt

`func (o *ImageUpdate) SetLastCheckedAt(v time.Time)`

SetLastCheckedAt sets LastCheckedAt field to given value.


### SetLastCheckedAtNil

`func (o *ImageUpdate) SetLastCheckedAtNil(b bool)`

 SetLastCheckedAtNil sets the value for LastCheckedAt to be an explicit nil

### UnsetLastCheckedAt
`func (o *ImageUpdate) UnsetLastCheckedAt()`

UnsetLastCheckedAt ensures that no value is present for LastCheckedAt, not even an explicit nil
### GetLatestRepoDigest

`func (o *ImageUpdate) GetLatestRepoDigest() string`

GetLatestRepoDigest returns the LatestRepoDigest field if non-nil, zero value otherwise.

### GetLatestRepoDigestOk

`func (o *ImageUpdate) GetLatestRepoDigestOk() (*string, bool)`

GetLatestRepoDigestOk returns a tuple with the LatestRepoDigest field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatestRepoDigest

`func (o *ImageUpdate) SetLatestRepoDigest(v string)`

SetLatestRepoDigest sets LatestRepoDigest field to given value.


### GetServerId

`func (o *ImageUpdate) GetServerId() int32`

GetServerId returns the ServerId field if non-nil, zero value otherwise.

### GetServerIdOk

`func (o *ImageUpdate) GetServerIdOk() (*int32, bool)`

GetServerIdOk returns a tuple with the ServerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerId

`func (o *ImageUpdate) SetServerId(v int32)`

SetServerId sets ServerId field to given value.


### GetStackName

`func (o *ImageUpdate) GetStackName() string`

GetStackName returns the StackName field if non-nil, zero value otherwise.

### GetStackNameOk

`func (o *ImageUpdate) GetStackNameOk() (*string, bool)`

GetStackNameOk returns a tuple with the StackName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStackName

`func (o *ImageUpdate) SetStackName(v string)`

SetStackName sets StackName field to given value.


### GetUpdateAvailable

`func (o *ImageUpdate) GetUpdateAvailable() bool`

GetUpdateAvailable returns the UpdateAvailable field if non-nil, zero value otherwise.

### GetUpdateAvailableOk

`func (o *ImageUpdate) GetUpdateAvailableOk() (*bool, bool)`

GetUpdateAvailableOk returns a tuple with the UpdateAvailable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdateAvailable

`func (o *ImageUpdate) SetUpdateAvailable(v bool)`

SetUpdateAvailable sets UpdateAvailable field to given value.


### GetUpdatedAt

`func (o *ImageUpdate) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ImageUpdate) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ImageUpdate) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


