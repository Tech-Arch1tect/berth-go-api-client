# DeletedAt

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Time** | **time.Time** |  | 
**Valid** | **bool** |  | 

## Methods

### NewDeletedAt

`func NewDeletedAt(time time.Time, valid bool, ) *DeletedAt`

NewDeletedAt instantiates a new DeletedAt object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeletedAtWithDefaults

`func NewDeletedAtWithDefaults() *DeletedAt`

NewDeletedAtWithDefaults instantiates a new DeletedAt object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTime

`func (o *DeletedAt) GetTime() time.Time`

GetTime returns the Time field if non-nil, zero value otherwise.

### GetTimeOk

`func (o *DeletedAt) GetTimeOk() (*time.Time, bool)`

GetTimeOk returns a tuple with the Time field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTime

`func (o *DeletedAt) SetTime(v time.Time)`

SetTime sets Time field to given value.


### GetValid

`func (o *DeletedAt) GetValid() bool`

GetValid returns the Valid field if non-nil, zero value otherwise.

### GetValidOk

`func (o *DeletedAt) GetValidOk() (*bool, bool)`

GetValidOk returns a tuple with the Valid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValid

`func (o *DeletedAt) SetValid(v bool)`

SetValid sets Valid field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


