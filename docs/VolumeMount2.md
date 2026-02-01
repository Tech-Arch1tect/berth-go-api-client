# VolumeMount2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ReadOnly** | Pointer to **bool** |  | [optional] 
**Source** | **string** |  | 
**Target** | **string** |  | 
**Type** | **string** |  | 

## Methods

### NewVolumeMount2

`func NewVolumeMount2(source string, target string, type_ string, ) *VolumeMount2`

NewVolumeMount2 instantiates a new VolumeMount2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVolumeMount2WithDefaults

`func NewVolumeMount2WithDefaults() *VolumeMount2`

NewVolumeMount2WithDefaults instantiates a new VolumeMount2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetReadOnly

`func (o *VolumeMount2) GetReadOnly() bool`

GetReadOnly returns the ReadOnly field if non-nil, zero value otherwise.

### GetReadOnlyOk

`func (o *VolumeMount2) GetReadOnlyOk() (*bool, bool)`

GetReadOnlyOk returns a tuple with the ReadOnly field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReadOnly

`func (o *VolumeMount2) SetReadOnly(v bool)`

SetReadOnly sets ReadOnly field to given value.

### HasReadOnly

`func (o *VolumeMount2) HasReadOnly() bool`

HasReadOnly returns a boolean if a field has been set.

### GetSource

`func (o *VolumeMount2) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *VolumeMount2) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *VolumeMount2) SetSource(v string)`

SetSource sets Source field to given value.


### GetTarget

`func (o *VolumeMount2) GetTarget() string`

GetTarget returns the Target field if non-nil, zero value otherwise.

### GetTargetOk

`func (o *VolumeMount2) GetTargetOk() (*string, bool)`

GetTargetOk returns a tuple with the Target field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTarget

`func (o *VolumeMount2) SetTarget(v string)`

SetTarget sets Target field to given value.


### GetType

`func (o *VolumeMount2) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *VolumeMount2) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *VolumeMount2) SetType(v string)`

SetType sets Type field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


