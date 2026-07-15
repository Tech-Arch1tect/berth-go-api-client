# BackupFileEntry

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Mtime** | **time.Time** |  | 
**Name** | **string** |  | 
**Size** | **int32** |  | 
**Type** | **string** |  | 

## Methods

### NewBackupFileEntry

`func NewBackupFileEntry(mtime time.Time, name string, size int32, type_ string, ) *BackupFileEntry`

NewBackupFileEntry instantiates a new BackupFileEntry object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBackupFileEntryWithDefaults

`func NewBackupFileEntryWithDefaults() *BackupFileEntry`

NewBackupFileEntryWithDefaults instantiates a new BackupFileEntry object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMtime

`func (o *BackupFileEntry) GetMtime() time.Time`

GetMtime returns the Mtime field if non-nil, zero value otherwise.

### GetMtimeOk

`func (o *BackupFileEntry) GetMtimeOk() (*time.Time, bool)`

GetMtimeOk returns a tuple with the Mtime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMtime

`func (o *BackupFileEntry) SetMtime(v time.Time)`

SetMtime sets Mtime field to given value.


### GetName

`func (o *BackupFileEntry) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *BackupFileEntry) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *BackupFileEntry) SetName(v string)`

SetName sets Name field to given value.


### GetSize

`func (o *BackupFileEntry) GetSize() int32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *BackupFileEntry) GetSizeOk() (*int32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *BackupFileEntry) SetSize(v int32)`

SetSize sets Size field to given value.


### GetType

`func (o *BackupFileEntry) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *BackupFileEntry) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *BackupFileEntry) SetType(v string)`

SetType sets Type field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


