# BuildCacheInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Created** | **time.Time** |  | 
**Description** | **string** |  | 
**Id** | **string** |  | 
**InUse** | **bool** |  | 
**LastUsed** | **time.Time** |  | 
**Parent** | Pointer to **string** |  | [optional] 
**Shared** | **bool** |  | 
**Size** | **int32** |  | 
**Type** | **string** |  | 
**UsageCount** | **int32** |  | 

## Methods

### NewBuildCacheInfo

`func NewBuildCacheInfo(created time.Time, description string, id string, inUse bool, lastUsed time.Time, shared bool, size int32, type_ string, usageCount int32, ) *BuildCacheInfo`

NewBuildCacheInfo instantiates a new BuildCacheInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBuildCacheInfoWithDefaults

`func NewBuildCacheInfoWithDefaults() *BuildCacheInfo`

NewBuildCacheInfoWithDefaults instantiates a new BuildCacheInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreated

`func (o *BuildCacheInfo) GetCreated() time.Time`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *BuildCacheInfo) GetCreatedOk() (*time.Time, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *BuildCacheInfo) SetCreated(v time.Time)`

SetCreated sets Created field to given value.


### GetDescription

`func (o *BuildCacheInfo) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *BuildCacheInfo) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *BuildCacheInfo) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetId

`func (o *BuildCacheInfo) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *BuildCacheInfo) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *BuildCacheInfo) SetId(v string)`

SetId sets Id field to given value.


### GetInUse

`func (o *BuildCacheInfo) GetInUse() bool`

GetInUse returns the InUse field if non-nil, zero value otherwise.

### GetInUseOk

`func (o *BuildCacheInfo) GetInUseOk() (*bool, bool)`

GetInUseOk returns a tuple with the InUse field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInUse

`func (o *BuildCacheInfo) SetInUse(v bool)`

SetInUse sets InUse field to given value.


### GetLastUsed

`func (o *BuildCacheInfo) GetLastUsed() time.Time`

GetLastUsed returns the LastUsed field if non-nil, zero value otherwise.

### GetLastUsedOk

`func (o *BuildCacheInfo) GetLastUsedOk() (*time.Time, bool)`

GetLastUsedOk returns a tuple with the LastUsed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastUsed

`func (o *BuildCacheInfo) SetLastUsed(v time.Time)`

SetLastUsed sets LastUsed field to given value.


### GetParent

`func (o *BuildCacheInfo) GetParent() string`

GetParent returns the Parent field if non-nil, zero value otherwise.

### GetParentOk

`func (o *BuildCacheInfo) GetParentOk() (*string, bool)`

GetParentOk returns a tuple with the Parent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParent

`func (o *BuildCacheInfo) SetParent(v string)`

SetParent sets Parent field to given value.

### HasParent

`func (o *BuildCacheInfo) HasParent() bool`

HasParent returns a boolean if a field has been set.

### GetShared

`func (o *BuildCacheInfo) GetShared() bool`

GetShared returns the Shared field if non-nil, zero value otherwise.

### GetSharedOk

`func (o *BuildCacheInfo) GetSharedOk() (*bool, bool)`

GetSharedOk returns a tuple with the Shared field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShared

`func (o *BuildCacheInfo) SetShared(v bool)`

SetShared sets Shared field to given value.


### GetSize

`func (o *BuildCacheInfo) GetSize() int32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *BuildCacheInfo) GetSizeOk() (*int32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *BuildCacheInfo) SetSize(v int32)`

SetSize sets Size field to given value.


### GetType

`func (o *BuildCacheInfo) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *BuildCacheInfo) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *BuildCacheInfo) SetType(v string)`

SetType sets Type field to given value.


### GetUsageCount

`func (o *BuildCacheInfo) GetUsageCount() int32`

GetUsageCount returns the UsageCount field if non-nil, zero value otherwise.

### GetUsageCountOk

`func (o *BuildCacheInfo) GetUsageCountOk() (*int32, bool)`

GetUsageCountOk returns a tuple with the UsageCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsageCount

`func (o *BuildCacheInfo) SetUsageCount(v int32)`

SetUsageCount sets UsageCount field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


