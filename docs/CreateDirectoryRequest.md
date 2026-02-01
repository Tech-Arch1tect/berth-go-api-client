# CreateDirectoryRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**GroupId** | Pointer to **NullableInt32** |  | [optional] 
**Mode** | Pointer to **NullableString** |  | [optional] 
**OwnerId** | Pointer to **NullableInt32** |  | [optional] 
**Path** | **string** |  | 

## Methods

### NewCreateDirectoryRequest

`func NewCreateDirectoryRequest(path string, ) *CreateDirectoryRequest`

NewCreateDirectoryRequest instantiates a new CreateDirectoryRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateDirectoryRequestWithDefaults

`func NewCreateDirectoryRequestWithDefaults() *CreateDirectoryRequest`

NewCreateDirectoryRequestWithDefaults instantiates a new CreateDirectoryRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGroupId

`func (o *CreateDirectoryRequest) GetGroupId() int32`

GetGroupId returns the GroupId field if non-nil, zero value otherwise.

### GetGroupIdOk

`func (o *CreateDirectoryRequest) GetGroupIdOk() (*int32, bool)`

GetGroupIdOk returns a tuple with the GroupId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupId

`func (o *CreateDirectoryRequest) SetGroupId(v int32)`

SetGroupId sets GroupId field to given value.

### HasGroupId

`func (o *CreateDirectoryRequest) HasGroupId() bool`

HasGroupId returns a boolean if a field has been set.

### SetGroupIdNil

`func (o *CreateDirectoryRequest) SetGroupIdNil(b bool)`

 SetGroupIdNil sets the value for GroupId to be an explicit nil

### UnsetGroupId
`func (o *CreateDirectoryRequest) UnsetGroupId()`

UnsetGroupId ensures that no value is present for GroupId, not even an explicit nil
### GetMode

`func (o *CreateDirectoryRequest) GetMode() string`

GetMode returns the Mode field if non-nil, zero value otherwise.

### GetModeOk

`func (o *CreateDirectoryRequest) GetModeOk() (*string, bool)`

GetModeOk returns a tuple with the Mode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMode

`func (o *CreateDirectoryRequest) SetMode(v string)`

SetMode sets Mode field to given value.

### HasMode

`func (o *CreateDirectoryRequest) HasMode() bool`

HasMode returns a boolean if a field has been set.

### SetModeNil

`func (o *CreateDirectoryRequest) SetModeNil(b bool)`

 SetModeNil sets the value for Mode to be an explicit nil

### UnsetMode
`func (o *CreateDirectoryRequest) UnsetMode()`

UnsetMode ensures that no value is present for Mode, not even an explicit nil
### GetOwnerId

`func (o *CreateDirectoryRequest) GetOwnerId() int32`

GetOwnerId returns the OwnerId field if non-nil, zero value otherwise.

### GetOwnerIdOk

`func (o *CreateDirectoryRequest) GetOwnerIdOk() (*int32, bool)`

GetOwnerIdOk returns a tuple with the OwnerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnerId

`func (o *CreateDirectoryRequest) SetOwnerId(v int32)`

SetOwnerId sets OwnerId field to given value.

### HasOwnerId

`func (o *CreateDirectoryRequest) HasOwnerId() bool`

HasOwnerId returns a boolean if a field has been set.

### SetOwnerIdNil

`func (o *CreateDirectoryRequest) SetOwnerIdNil(b bool)`

 SetOwnerIdNil sets the value for OwnerId to be an explicit nil

### UnsetOwnerId
`func (o *CreateDirectoryRequest) UnsetOwnerId()`

UnsetOwnerId ensures that no value is present for OwnerId, not even an explicit nil
### GetPath

`func (o *CreateDirectoryRequest) GetPath() string`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *CreateDirectoryRequest) GetPathOk() (*string, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *CreateDirectoryRequest) SetPath(v string)`

SetPath sets Path field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


