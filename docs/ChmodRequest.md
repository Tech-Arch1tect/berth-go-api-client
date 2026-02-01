# ChmodRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Mode** | **string** |  | 
**Path** | **string** |  | 
**Recursive** | Pointer to **bool** |  | [optional] 

## Methods

### NewChmodRequest

`func NewChmodRequest(mode string, path string, ) *ChmodRequest`

NewChmodRequest instantiates a new ChmodRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChmodRequestWithDefaults

`func NewChmodRequestWithDefaults() *ChmodRequest`

NewChmodRequestWithDefaults instantiates a new ChmodRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMode

`func (o *ChmodRequest) GetMode() string`

GetMode returns the Mode field if non-nil, zero value otherwise.

### GetModeOk

`func (o *ChmodRequest) GetModeOk() (*string, bool)`

GetModeOk returns a tuple with the Mode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMode

`func (o *ChmodRequest) SetMode(v string)`

SetMode sets Mode field to given value.


### GetPath

`func (o *ChmodRequest) GetPath() string`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *ChmodRequest) GetPathOk() (*string, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *ChmodRequest) SetPath(v string)`

SetPath sets Path field to given value.


### GetRecursive

`func (o *ChmodRequest) GetRecursive() bool`

GetRecursive returns the Recursive field if non-nil, zero value otherwise.

### GetRecursiveOk

`func (o *ChmodRequest) GetRecursiveOk() (*bool, bool)`

GetRecursiveOk returns a tuple with the Recursive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecursive

`func (o *ChmodRequest) SetRecursive(v bool)`

SetRecursive sets Recursive field to given value.

### HasRecursive

`func (o *ChmodRequest) HasRecursive() bool`

HasRecursive returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


