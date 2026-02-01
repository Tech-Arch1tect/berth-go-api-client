# VolumeMount

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BindOptions** | Pointer to **map[string]string** |  | [optional] 
**ReadOnly** | Pointer to **bool** |  | [optional] 
**Source** | **string** |  | 
**Target** | **string** |  | 
**TmpfsOptions** | Pointer to **map[string]string** |  | [optional] 
**Type** | **string** |  | 

## Methods

### NewVolumeMount

`func NewVolumeMount(source string, target string, type_ string, ) *VolumeMount`

NewVolumeMount instantiates a new VolumeMount object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVolumeMountWithDefaults

`func NewVolumeMountWithDefaults() *VolumeMount`

NewVolumeMountWithDefaults instantiates a new VolumeMount object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBindOptions

`func (o *VolumeMount) GetBindOptions() map[string]string`

GetBindOptions returns the BindOptions field if non-nil, zero value otherwise.

### GetBindOptionsOk

`func (o *VolumeMount) GetBindOptionsOk() (*map[string]string, bool)`

GetBindOptionsOk returns a tuple with the BindOptions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBindOptions

`func (o *VolumeMount) SetBindOptions(v map[string]string)`

SetBindOptions sets BindOptions field to given value.

### HasBindOptions

`func (o *VolumeMount) HasBindOptions() bool`

HasBindOptions returns a boolean if a field has been set.

### GetReadOnly

`func (o *VolumeMount) GetReadOnly() bool`

GetReadOnly returns the ReadOnly field if non-nil, zero value otherwise.

### GetReadOnlyOk

`func (o *VolumeMount) GetReadOnlyOk() (*bool, bool)`

GetReadOnlyOk returns a tuple with the ReadOnly field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReadOnly

`func (o *VolumeMount) SetReadOnly(v bool)`

SetReadOnly sets ReadOnly field to given value.

### HasReadOnly

`func (o *VolumeMount) HasReadOnly() bool`

HasReadOnly returns a boolean if a field has been set.

### GetSource

`func (o *VolumeMount) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *VolumeMount) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *VolumeMount) SetSource(v string)`

SetSource sets Source field to given value.


### GetTarget

`func (o *VolumeMount) GetTarget() string`

GetTarget returns the Target field if non-nil, zero value otherwise.

### GetTargetOk

`func (o *VolumeMount) GetTargetOk() (*string, bool)`

GetTargetOk returns a tuple with the Target field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTarget

`func (o *VolumeMount) SetTarget(v string)`

SetTarget sets Target field to given value.


### GetTmpfsOptions

`func (o *VolumeMount) GetTmpfsOptions() map[string]string`

GetTmpfsOptions returns the TmpfsOptions field if non-nil, zero value otherwise.

### GetTmpfsOptionsOk

`func (o *VolumeMount) GetTmpfsOptionsOk() (*map[string]string, bool)`

GetTmpfsOptionsOk returns a tuple with the TmpfsOptions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTmpfsOptions

`func (o *VolumeMount) SetTmpfsOptions(v map[string]string)`

SetTmpfsOptions sets TmpfsOptions field to given value.

### HasTmpfsOptions

`func (o *VolumeMount) HasTmpfsOptions() bool`

HasTmpfsOptions returns a boolean if a field has been set.

### GetType

`func (o *VolumeMount) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *VolumeMount) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *VolumeMount) SetType(v string)`

SetType sets Type field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


