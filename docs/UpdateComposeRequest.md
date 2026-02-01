# UpdateComposeRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Changes** | [**ComposeChanges**](ComposeChanges.md) |  | 
**Preview** | Pointer to **bool** |  | [optional] 

## Methods

### NewUpdateComposeRequest

`func NewUpdateComposeRequest(changes ComposeChanges, ) *UpdateComposeRequest`

NewUpdateComposeRequest instantiates a new UpdateComposeRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateComposeRequestWithDefaults

`func NewUpdateComposeRequestWithDefaults() *UpdateComposeRequest`

NewUpdateComposeRequestWithDefaults instantiates a new UpdateComposeRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetChanges

`func (o *UpdateComposeRequest) GetChanges() ComposeChanges`

GetChanges returns the Changes field if non-nil, zero value otherwise.

### GetChangesOk

`func (o *UpdateComposeRequest) GetChangesOk() (*ComposeChanges, bool)`

GetChangesOk returns a tuple with the Changes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChanges

`func (o *UpdateComposeRequest) SetChanges(v ComposeChanges)`

SetChanges sets Changes field to given value.


### GetPreview

`func (o *UpdateComposeRequest) GetPreview() bool`

GetPreview returns the Preview field if non-nil, zero value otherwise.

### GetPreviewOk

`func (o *UpdateComposeRequest) GetPreviewOk() (*bool, bool)`

GetPreviewOk returns a tuple with the Preview field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreview

`func (o *UpdateComposeRequest) SetPreview(v bool)`

SetPreview sets Preview field to given value.

### HasPreview

`func (o *UpdateComposeRequest) HasPreview() bool`

HasPreview returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


