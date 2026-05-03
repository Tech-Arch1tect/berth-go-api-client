# ResponseDirectoryListing

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**DirectoryListing**](DirectoryListing.md) |  | 
**Error** | Pointer to [**NullableError**](Error.md) |  | [optional] 
**Meta** | Pointer to [**NullableMeta**](Meta.md) |  | [optional] 
**Success** | **bool** |  | 

## Methods

### NewResponseDirectoryListing

`func NewResponseDirectoryListing(data DirectoryListing, success bool, ) *ResponseDirectoryListing`

NewResponseDirectoryListing instantiates a new ResponseDirectoryListing object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResponseDirectoryListingWithDefaults

`func NewResponseDirectoryListingWithDefaults() *ResponseDirectoryListing`

NewResponseDirectoryListingWithDefaults instantiates a new ResponseDirectoryListing object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *ResponseDirectoryListing) GetData() DirectoryListing`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ResponseDirectoryListing) GetDataOk() (*DirectoryListing, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ResponseDirectoryListing) SetData(v DirectoryListing)`

SetData sets Data field to given value.


### GetError

`func (o *ResponseDirectoryListing) GetError() Error`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ResponseDirectoryListing) GetErrorOk() (*Error, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ResponseDirectoryListing) SetError(v Error)`

SetError sets Error field to given value.

### HasError

`func (o *ResponseDirectoryListing) HasError() bool`

HasError returns a boolean if a field has been set.

### SetErrorNil

`func (o *ResponseDirectoryListing) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *ResponseDirectoryListing) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetMeta

`func (o *ResponseDirectoryListing) GetMeta() Meta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *ResponseDirectoryListing) GetMetaOk() (*Meta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *ResponseDirectoryListing) SetMeta(v Meta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *ResponseDirectoryListing) HasMeta() bool`

HasMeta returns a boolean if a field has been set.

### SetMetaNil

`func (o *ResponseDirectoryListing) SetMetaNil(b bool)`

 SetMetaNil sets the value for Meta to be an explicit nil

### UnsetMeta
`func (o *ResponseDirectoryListing) UnsetMeta()`

UnsetMeta ensures that no value is present for Meta, not even an explicit nil
### GetSuccess

`func (o *ResponseDirectoryListing) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *ResponseDirectoryListing) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *ResponseDirectoryListing) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


