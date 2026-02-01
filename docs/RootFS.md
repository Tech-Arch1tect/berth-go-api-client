# RootFS

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Layers** | Pointer to **[]string** |  | [optional] 
**Type** | **string** |  | 

## Methods

### NewRootFS

`func NewRootFS(type_ string, ) *RootFS`

NewRootFS instantiates a new RootFS object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRootFSWithDefaults

`func NewRootFSWithDefaults() *RootFS`

NewRootFSWithDefaults instantiates a new RootFS object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLayers

`func (o *RootFS) GetLayers() []string`

GetLayers returns the Layers field if non-nil, zero value otherwise.

### GetLayersOk

`func (o *RootFS) GetLayersOk() (*[]string, bool)`

GetLayersOk returns a tuple with the Layers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLayers

`func (o *RootFS) SetLayers(v []string)`

SetLayers sets Layers field to given value.

### HasLayers

`func (o *RootFS) HasLayers() bool`

HasLayers returns a boolean if a field has been set.

### GetType

`func (o *RootFS) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *RootFS) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *RootFS) SetType(v string)`

SetType sets Type field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


