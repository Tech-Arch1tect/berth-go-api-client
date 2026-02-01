# WriteFileRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Content** | **string** |  | 
**Encoding** | Pointer to **string** |  | [optional] 
**GroupId** | Pointer to **NullableInt32** |  | [optional] 
**Mode** | Pointer to **NullableString** |  | [optional] 
**OwnerId** | Pointer to **NullableInt32** |  | [optional] 
**Path** | **string** |  | 

## Methods

### NewWriteFileRequest

`func NewWriteFileRequest(content string, path string, ) *WriteFileRequest`

NewWriteFileRequest instantiates a new WriteFileRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWriteFileRequestWithDefaults

`func NewWriteFileRequestWithDefaults() *WriteFileRequest`

NewWriteFileRequestWithDefaults instantiates a new WriteFileRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContent

`func (o *WriteFileRequest) GetContent() string`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *WriteFileRequest) GetContentOk() (*string, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *WriteFileRequest) SetContent(v string)`

SetContent sets Content field to given value.


### GetEncoding

`func (o *WriteFileRequest) GetEncoding() string`

GetEncoding returns the Encoding field if non-nil, zero value otherwise.

### GetEncodingOk

`func (o *WriteFileRequest) GetEncodingOk() (*string, bool)`

GetEncodingOk returns a tuple with the Encoding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEncoding

`func (o *WriteFileRequest) SetEncoding(v string)`

SetEncoding sets Encoding field to given value.

### HasEncoding

`func (o *WriteFileRequest) HasEncoding() bool`

HasEncoding returns a boolean if a field has been set.

### GetGroupId

`func (o *WriteFileRequest) GetGroupId() int32`

GetGroupId returns the GroupId field if non-nil, zero value otherwise.

### GetGroupIdOk

`func (o *WriteFileRequest) GetGroupIdOk() (*int32, bool)`

GetGroupIdOk returns a tuple with the GroupId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupId

`func (o *WriteFileRequest) SetGroupId(v int32)`

SetGroupId sets GroupId field to given value.

### HasGroupId

`func (o *WriteFileRequest) HasGroupId() bool`

HasGroupId returns a boolean if a field has been set.

### SetGroupIdNil

`func (o *WriteFileRequest) SetGroupIdNil(b bool)`

 SetGroupIdNil sets the value for GroupId to be an explicit nil

### UnsetGroupId
`func (o *WriteFileRequest) UnsetGroupId()`

UnsetGroupId ensures that no value is present for GroupId, not even an explicit nil
### GetMode

`func (o *WriteFileRequest) GetMode() string`

GetMode returns the Mode field if non-nil, zero value otherwise.

### GetModeOk

`func (o *WriteFileRequest) GetModeOk() (*string, bool)`

GetModeOk returns a tuple with the Mode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMode

`func (o *WriteFileRequest) SetMode(v string)`

SetMode sets Mode field to given value.

### HasMode

`func (o *WriteFileRequest) HasMode() bool`

HasMode returns a boolean if a field has been set.

### SetModeNil

`func (o *WriteFileRequest) SetModeNil(b bool)`

 SetModeNil sets the value for Mode to be an explicit nil

### UnsetMode
`func (o *WriteFileRequest) UnsetMode()`

UnsetMode ensures that no value is present for Mode, not even an explicit nil
### GetOwnerId

`func (o *WriteFileRequest) GetOwnerId() int32`

GetOwnerId returns the OwnerId field if non-nil, zero value otherwise.

### GetOwnerIdOk

`func (o *WriteFileRequest) GetOwnerIdOk() (*int32, bool)`

GetOwnerIdOk returns a tuple with the OwnerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnerId

`func (o *WriteFileRequest) SetOwnerId(v int32)`

SetOwnerId sets OwnerId field to given value.

### HasOwnerId

`func (o *WriteFileRequest) HasOwnerId() bool`

HasOwnerId returns a boolean if a field has been set.

### SetOwnerIdNil

`func (o *WriteFileRequest) SetOwnerIdNil(b bool)`

 SetOwnerIdNil sets the value for OwnerId to be an explicit nil

### UnsetOwnerId
`func (o *WriteFileRequest) UnsetOwnerId()`

UnsetOwnerId ensures that no value is present for OwnerId, not even an explicit nil
### GetPath

`func (o *WriteFileRequest) GetPath() string`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *WriteFileRequest) GetPathOk() (*string, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *WriteFileRequest) SetPath(v string)`

SetPath sets Path field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


