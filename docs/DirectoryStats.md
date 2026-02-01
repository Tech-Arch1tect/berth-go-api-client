# DirectoryStats

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**GroupName** | Pointer to **string** |  | [optional] 
**MostCommonGroup** | **int32** |  | 
**MostCommonMode** | **string** |  | 
**MostCommonOwner** | **int32** |  | 
**OwnerName** | Pointer to **string** |  | [optional] 
**Path** | **string** |  | 

## Methods

### NewDirectoryStats

`func NewDirectoryStats(mostCommonGroup int32, mostCommonMode string, mostCommonOwner int32, path string, ) *DirectoryStats`

NewDirectoryStats instantiates a new DirectoryStats object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDirectoryStatsWithDefaults

`func NewDirectoryStatsWithDefaults() *DirectoryStats`

NewDirectoryStatsWithDefaults instantiates a new DirectoryStats object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGroupName

`func (o *DirectoryStats) GetGroupName() string`

GetGroupName returns the GroupName field if non-nil, zero value otherwise.

### GetGroupNameOk

`func (o *DirectoryStats) GetGroupNameOk() (*string, bool)`

GetGroupNameOk returns a tuple with the GroupName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupName

`func (o *DirectoryStats) SetGroupName(v string)`

SetGroupName sets GroupName field to given value.

### HasGroupName

`func (o *DirectoryStats) HasGroupName() bool`

HasGroupName returns a boolean if a field has been set.

### GetMostCommonGroup

`func (o *DirectoryStats) GetMostCommonGroup() int32`

GetMostCommonGroup returns the MostCommonGroup field if non-nil, zero value otherwise.

### GetMostCommonGroupOk

`func (o *DirectoryStats) GetMostCommonGroupOk() (*int32, bool)`

GetMostCommonGroupOk returns a tuple with the MostCommonGroup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMostCommonGroup

`func (o *DirectoryStats) SetMostCommonGroup(v int32)`

SetMostCommonGroup sets MostCommonGroup field to given value.


### GetMostCommonMode

`func (o *DirectoryStats) GetMostCommonMode() string`

GetMostCommonMode returns the MostCommonMode field if non-nil, zero value otherwise.

### GetMostCommonModeOk

`func (o *DirectoryStats) GetMostCommonModeOk() (*string, bool)`

GetMostCommonModeOk returns a tuple with the MostCommonMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMostCommonMode

`func (o *DirectoryStats) SetMostCommonMode(v string)`

SetMostCommonMode sets MostCommonMode field to given value.


### GetMostCommonOwner

`func (o *DirectoryStats) GetMostCommonOwner() int32`

GetMostCommonOwner returns the MostCommonOwner field if non-nil, zero value otherwise.

### GetMostCommonOwnerOk

`func (o *DirectoryStats) GetMostCommonOwnerOk() (*int32, bool)`

GetMostCommonOwnerOk returns a tuple with the MostCommonOwner field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMostCommonOwner

`func (o *DirectoryStats) SetMostCommonOwner(v int32)`

SetMostCommonOwner sets MostCommonOwner field to given value.


### GetOwnerName

`func (o *DirectoryStats) GetOwnerName() string`

GetOwnerName returns the OwnerName field if non-nil, zero value otherwise.

### GetOwnerNameOk

`func (o *DirectoryStats) GetOwnerNameOk() (*string, bool)`

GetOwnerNameOk returns a tuple with the OwnerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnerName

`func (o *DirectoryStats) SetOwnerName(v string)`

SetOwnerName sets OwnerName field to given value.

### HasOwnerName

`func (o *DirectoryStats) HasOwnerName() bool`

HasOwnerName returns a boolean if a field has been set.

### GetPath

`func (o *DirectoryStats) GetPath() string`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *DirectoryStats) GetPathOk() (*string, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *DirectoryStats) SetPath(v string)`

SetPath sets Path field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


