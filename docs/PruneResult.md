# PruneResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | Pointer to **string** |  | [optional] 
**ItemsDeleted** | **[]string** |  | 
**SpaceReclaimed** | **int32** |  | 
**Type** | **string** |  | 

## Methods

### NewPruneResult

`func NewPruneResult(itemsDeleted []string, spaceReclaimed int32, type_ string, ) *PruneResult`

NewPruneResult instantiates a new PruneResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPruneResultWithDefaults

`func NewPruneResultWithDefaults() *PruneResult`

NewPruneResultWithDefaults instantiates a new PruneResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *PruneResult) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *PruneResult) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *PruneResult) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *PruneResult) HasError() bool`

HasError returns a boolean if a field has been set.

### GetItemsDeleted

`func (o *PruneResult) GetItemsDeleted() []string`

GetItemsDeleted returns the ItemsDeleted field if non-nil, zero value otherwise.

### GetItemsDeletedOk

`func (o *PruneResult) GetItemsDeletedOk() (*[]string, bool)`

GetItemsDeletedOk returns a tuple with the ItemsDeleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemsDeleted

`func (o *PruneResult) SetItemsDeleted(v []string)`

SetItemsDeleted sets ItemsDeleted field to given value.


### GetSpaceReclaimed

`func (o *PruneResult) GetSpaceReclaimed() int32`

GetSpaceReclaimed returns the SpaceReclaimed field if non-nil, zero value otherwise.

### GetSpaceReclaimedOk

`func (o *PruneResult) GetSpaceReclaimedOk() (*int32, bool)`

GetSpaceReclaimedOk returns a tuple with the SpaceReclaimed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpaceReclaimed

`func (o *PruneResult) SetSpaceReclaimed(v int32)`

SetSpaceReclaimed sets SpaceReclaimed field to given value.


### GetType

`func (o *PruneResult) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *PruneResult) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *PruneResult) SetType(v string)`

SetType sets Type field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


