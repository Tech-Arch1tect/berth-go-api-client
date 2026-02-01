# DirectoryListing

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Entries** | [**[]FileEntry**](FileEntry.md) |  | 
**Path** | **string** |  | 

## Methods

### NewDirectoryListing

`func NewDirectoryListing(entries []FileEntry, path string, ) *DirectoryListing`

NewDirectoryListing instantiates a new DirectoryListing object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDirectoryListingWithDefaults

`func NewDirectoryListingWithDefaults() *DirectoryListing`

NewDirectoryListingWithDefaults instantiates a new DirectoryListing object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEntries

`func (o *DirectoryListing) GetEntries() []FileEntry`

GetEntries returns the Entries field if non-nil, zero value otherwise.

### GetEntriesOk

`func (o *DirectoryListing) GetEntriesOk() (*[]FileEntry, bool)`

GetEntriesOk returns a tuple with the Entries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntries

`func (o *DirectoryListing) SetEntries(v []FileEntry)`

SetEntries sets Entries field to given value.


### GetPath

`func (o *DirectoryListing) GetPath() string`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *DirectoryListing) GetPathOk() (*string, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *DirectoryListing) SetPath(v string)`

SetPath sets Path field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


