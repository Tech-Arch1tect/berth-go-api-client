# RegistryCredentialInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CreatedAt** | **time.Time** |  | 
**Id** | **int32** |  | 
**ImagePattern** | Pointer to **string** |  | [optional] 
**RegistryUrl** | **string** |  | 
**ServerId** | **int32** |  | 
**StackPattern** | **string** |  | 
**UpdatedAt** | **time.Time** |  | 
**Username** | **string** |  | 

## Methods

### NewRegistryCredentialInfo

`func NewRegistryCredentialInfo(createdAt time.Time, id int32, registryUrl string, serverId int32, stackPattern string, updatedAt time.Time, username string, ) *RegistryCredentialInfo`

NewRegistryCredentialInfo instantiates a new RegistryCredentialInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRegistryCredentialInfoWithDefaults

`func NewRegistryCredentialInfoWithDefaults() *RegistryCredentialInfo`

NewRegistryCredentialInfoWithDefaults instantiates a new RegistryCredentialInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreatedAt

`func (o *RegistryCredentialInfo) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *RegistryCredentialInfo) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *RegistryCredentialInfo) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetId

`func (o *RegistryCredentialInfo) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RegistryCredentialInfo) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RegistryCredentialInfo) SetId(v int32)`

SetId sets Id field to given value.


### GetImagePattern

`func (o *RegistryCredentialInfo) GetImagePattern() string`

GetImagePattern returns the ImagePattern field if non-nil, zero value otherwise.

### GetImagePatternOk

`func (o *RegistryCredentialInfo) GetImagePatternOk() (*string, bool)`

GetImagePatternOk returns a tuple with the ImagePattern field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImagePattern

`func (o *RegistryCredentialInfo) SetImagePattern(v string)`

SetImagePattern sets ImagePattern field to given value.

### HasImagePattern

`func (o *RegistryCredentialInfo) HasImagePattern() bool`

HasImagePattern returns a boolean if a field has been set.

### GetRegistryUrl

`func (o *RegistryCredentialInfo) GetRegistryUrl() string`

GetRegistryUrl returns the RegistryUrl field if non-nil, zero value otherwise.

### GetRegistryUrlOk

`func (o *RegistryCredentialInfo) GetRegistryUrlOk() (*string, bool)`

GetRegistryUrlOk returns a tuple with the RegistryUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegistryUrl

`func (o *RegistryCredentialInfo) SetRegistryUrl(v string)`

SetRegistryUrl sets RegistryUrl field to given value.


### GetServerId

`func (o *RegistryCredentialInfo) GetServerId() int32`

GetServerId returns the ServerId field if non-nil, zero value otherwise.

### GetServerIdOk

`func (o *RegistryCredentialInfo) GetServerIdOk() (*int32, bool)`

GetServerIdOk returns a tuple with the ServerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerId

`func (o *RegistryCredentialInfo) SetServerId(v int32)`

SetServerId sets ServerId field to given value.


### GetStackPattern

`func (o *RegistryCredentialInfo) GetStackPattern() string`

GetStackPattern returns the StackPattern field if non-nil, zero value otherwise.

### GetStackPatternOk

`func (o *RegistryCredentialInfo) GetStackPatternOk() (*string, bool)`

GetStackPatternOk returns a tuple with the StackPattern field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStackPattern

`func (o *RegistryCredentialInfo) SetStackPattern(v string)`

SetStackPattern sets StackPattern field to given value.


### GetUpdatedAt

`func (o *RegistryCredentialInfo) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *RegistryCredentialInfo) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *RegistryCredentialInfo) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetUsername

`func (o *RegistryCredentialInfo) GetUsername() string`

GetUsername returns the Username field if non-nil, zero value otherwise.

### GetUsernameOk

`func (o *RegistryCredentialInfo) GetUsernameOk() (*string, bool)`

GetUsernameOk returns a tuple with the Username field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsername

`func (o *RegistryCredentialInfo) SetUsername(v string)`

SetUsername sets Username field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


