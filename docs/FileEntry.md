# FileEntry

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Extension** | Pointer to **string** |  | [optional] 
**Group** | Pointer to **string** |  | [optional] 
**GroupId** | Pointer to **int32** |  | [optional] 
**IsDirectory** | **bool** |  | 
**ModTime** | **time.Time** |  | 
**Mode** | **string** |  | 
**Name** | **string** |  | 
**Owner** | Pointer to **string** |  | [optional] 
**OwnerId** | Pointer to **int32** |  | [optional] 
**Path** | **string** |  | 
**Size** | **int32** |  | 

## Methods

### NewFileEntry

`func NewFileEntry(isDirectory bool, modTime time.Time, mode string, name string, path string, size int32, ) *FileEntry`

NewFileEntry instantiates a new FileEntry object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFileEntryWithDefaults

`func NewFileEntryWithDefaults() *FileEntry`

NewFileEntryWithDefaults instantiates a new FileEntry object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExtension

`func (o *FileEntry) GetExtension() string`

GetExtension returns the Extension field if non-nil, zero value otherwise.

### GetExtensionOk

`func (o *FileEntry) GetExtensionOk() (*string, bool)`

GetExtensionOk returns a tuple with the Extension field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtension

`func (o *FileEntry) SetExtension(v string)`

SetExtension sets Extension field to given value.

### HasExtension

`func (o *FileEntry) HasExtension() bool`

HasExtension returns a boolean if a field has been set.

### GetGroup

`func (o *FileEntry) GetGroup() string`

GetGroup returns the Group field if non-nil, zero value otherwise.

### GetGroupOk

`func (o *FileEntry) GetGroupOk() (*string, bool)`

GetGroupOk returns a tuple with the Group field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroup

`func (o *FileEntry) SetGroup(v string)`

SetGroup sets Group field to given value.

### HasGroup

`func (o *FileEntry) HasGroup() bool`

HasGroup returns a boolean if a field has been set.

### GetGroupId

`func (o *FileEntry) GetGroupId() int32`

GetGroupId returns the GroupId field if non-nil, zero value otherwise.

### GetGroupIdOk

`func (o *FileEntry) GetGroupIdOk() (*int32, bool)`

GetGroupIdOk returns a tuple with the GroupId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupId

`func (o *FileEntry) SetGroupId(v int32)`

SetGroupId sets GroupId field to given value.

### HasGroupId

`func (o *FileEntry) HasGroupId() bool`

HasGroupId returns a boolean if a field has been set.

### GetIsDirectory

`func (o *FileEntry) GetIsDirectory() bool`

GetIsDirectory returns the IsDirectory field if non-nil, zero value otherwise.

### GetIsDirectoryOk

`func (o *FileEntry) GetIsDirectoryOk() (*bool, bool)`

GetIsDirectoryOk returns a tuple with the IsDirectory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDirectory

`func (o *FileEntry) SetIsDirectory(v bool)`

SetIsDirectory sets IsDirectory field to given value.


### GetModTime

`func (o *FileEntry) GetModTime() time.Time`

GetModTime returns the ModTime field if non-nil, zero value otherwise.

### GetModTimeOk

`func (o *FileEntry) GetModTimeOk() (*time.Time, bool)`

GetModTimeOk returns a tuple with the ModTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModTime

`func (o *FileEntry) SetModTime(v time.Time)`

SetModTime sets ModTime field to given value.


### GetMode

`func (o *FileEntry) GetMode() string`

GetMode returns the Mode field if non-nil, zero value otherwise.

### GetModeOk

`func (o *FileEntry) GetModeOk() (*string, bool)`

GetModeOk returns a tuple with the Mode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMode

`func (o *FileEntry) SetMode(v string)`

SetMode sets Mode field to given value.


### GetName

`func (o *FileEntry) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *FileEntry) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *FileEntry) SetName(v string)`

SetName sets Name field to given value.


### GetOwner

`func (o *FileEntry) GetOwner() string`

GetOwner returns the Owner field if non-nil, zero value otherwise.

### GetOwnerOk

`func (o *FileEntry) GetOwnerOk() (*string, bool)`

GetOwnerOk returns a tuple with the Owner field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwner

`func (o *FileEntry) SetOwner(v string)`

SetOwner sets Owner field to given value.

### HasOwner

`func (o *FileEntry) HasOwner() bool`

HasOwner returns a boolean if a field has been set.

### GetOwnerId

`func (o *FileEntry) GetOwnerId() int32`

GetOwnerId returns the OwnerId field if non-nil, zero value otherwise.

### GetOwnerIdOk

`func (o *FileEntry) GetOwnerIdOk() (*int32, bool)`

GetOwnerIdOk returns a tuple with the OwnerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnerId

`func (o *FileEntry) SetOwnerId(v int32)`

SetOwnerId sets OwnerId field to given value.

### HasOwnerId

`func (o *FileEntry) HasOwnerId() bool`

HasOwnerId returns a boolean if a field has been set.

### GetPath

`func (o *FileEntry) GetPath() string`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *FileEntry) GetPathOk() (*string, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *FileEntry) SetPath(v string)`

SetPath sets Path field to given value.


### GetSize

`func (o *FileEntry) GetSize() int32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *FileEntry) GetSizeOk() (*int32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *FileEntry) SetSize(v int32)`

SetSize sets Size field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


