# RenameRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**NewPath** | **string** |  | 
**OldPath** | **string** |  | 

## Methods

### NewRenameRequest

`func NewRenameRequest(newPath string, oldPath string, ) *RenameRequest`

NewRenameRequest instantiates a new RenameRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRenameRequestWithDefaults

`func NewRenameRequestWithDefaults() *RenameRequest`

NewRenameRequestWithDefaults instantiates a new RenameRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNewPath

`func (o *RenameRequest) GetNewPath() string`

GetNewPath returns the NewPath field if non-nil, zero value otherwise.

### GetNewPathOk

`func (o *RenameRequest) GetNewPathOk() (*string, bool)`

GetNewPathOk returns a tuple with the NewPath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewPath

`func (o *RenameRequest) SetNewPath(v string)`

SetNewPath sets NewPath field to given value.


### GetOldPath

`func (o *RenameRequest) GetOldPath() string`

GetOldPath returns the OldPath field if non-nil, zero value otherwise.

### GetOldPathOk

`func (o *RenameRequest) GetOldPathOk() (*string, bool)`

GetOldPathOk returns a tuple with the OldPath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOldPath

`func (o *RenameRequest) SetOldPath(v string)`

SetOldPath sets OldPath field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


