# SkippedMount

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Kind** | **string** |  | 
**Reason** | **string** |  | 
**Service** | Pointer to **string** |  | [optional] 
**Target** | Pointer to **string** |  | [optional] 

## Methods

### NewSkippedMount

`func NewSkippedMount(kind string, reason string, ) *SkippedMount`

NewSkippedMount instantiates a new SkippedMount object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSkippedMountWithDefaults

`func NewSkippedMountWithDefaults() *SkippedMount`

NewSkippedMountWithDefaults instantiates a new SkippedMount object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKind

`func (o *SkippedMount) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *SkippedMount) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *SkippedMount) SetKind(v string)`

SetKind sets Kind field to given value.


### GetReason

`func (o *SkippedMount) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *SkippedMount) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *SkippedMount) SetReason(v string)`

SetReason sets Reason field to given value.


### GetService

`func (o *SkippedMount) GetService() string`

GetService returns the Service field if non-nil, zero value otherwise.

### GetServiceOk

`func (o *SkippedMount) GetServiceOk() (*string, bool)`

GetServiceOk returns a tuple with the Service field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetService

`func (o *SkippedMount) SetService(v string)`

SetService sets Service field to given value.

### HasService

`func (o *SkippedMount) HasService() bool`

HasService returns a boolean if a field has been set.

### GetTarget

`func (o *SkippedMount) GetTarget() string`

GetTarget returns the Target field if non-nil, zero value otherwise.

### GetTargetOk

`func (o *SkippedMount) GetTargetOk() (*string, bool)`

GetTargetOk returns a tuple with the Target field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTarget

`func (o *SkippedMount) SetTarget(v string)`

SetTarget sets Target field to given value.

### HasTarget

`func (o *SkippedMount) HasTarget() bool`

HasTarget returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


