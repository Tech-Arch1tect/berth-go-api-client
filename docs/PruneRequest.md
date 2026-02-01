# PruneRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**All** | **bool** |  | 
**Filters** | **string** |  | 
**Force** | **bool** |  | 
**Type** | **string** |  | 

## Methods

### NewPruneRequest

`func NewPruneRequest(all bool, filters string, force bool, type_ string, ) *PruneRequest`

NewPruneRequest instantiates a new PruneRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPruneRequestWithDefaults

`func NewPruneRequestWithDefaults() *PruneRequest`

NewPruneRequestWithDefaults instantiates a new PruneRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAll

`func (o *PruneRequest) GetAll() bool`

GetAll returns the All field if non-nil, zero value otherwise.

### GetAllOk

`func (o *PruneRequest) GetAllOk() (*bool, bool)`

GetAllOk returns a tuple with the All field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAll

`func (o *PruneRequest) SetAll(v bool)`

SetAll sets All field to given value.


### GetFilters

`func (o *PruneRequest) GetFilters() string`

GetFilters returns the Filters field if non-nil, zero value otherwise.

### GetFiltersOk

`func (o *PruneRequest) GetFiltersOk() (*string, bool)`

GetFiltersOk returns a tuple with the Filters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilters

`func (o *PruneRequest) SetFilters(v string)`

SetFilters sets Filters field to given value.


### GetForce

`func (o *PruneRequest) GetForce() bool`

GetForce returns the Force field if non-nil, zero value otherwise.

### GetForceOk

`func (o *PruneRequest) GetForceOk() (*bool, bool)`

GetForceOk returns a tuple with the Force field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForce

`func (o *PruneRequest) SetForce(v bool)`

SetForce sets Force field to given value.


### GetType

`func (o *PruneRequest) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *PruneRequest) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *PruneRequest) SetType(v string)`

SetType sets Type field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


