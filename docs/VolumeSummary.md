# VolumeSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Total** | [**Amount**](Amount.md) |  | 
**Unused** | [**Amount**](Amount.md) |  | 
**Volumes** | [**[]VolumeInfo**](VolumeInfo.md) |  | 

## Methods

### NewVolumeSummary

`func NewVolumeSummary(total Amount, unused Amount, volumes []VolumeInfo, ) *VolumeSummary`

NewVolumeSummary instantiates a new VolumeSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVolumeSummaryWithDefaults

`func NewVolumeSummaryWithDefaults() *VolumeSummary`

NewVolumeSummaryWithDefaults instantiates a new VolumeSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTotal

`func (o *VolumeSummary) GetTotal() Amount`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *VolumeSummary) GetTotalOk() (*Amount, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *VolumeSummary) SetTotal(v Amount)`

SetTotal sets Total field to given value.


### GetUnused

`func (o *VolumeSummary) GetUnused() Amount`

GetUnused returns the Unused field if non-nil, zero value otherwise.

### GetUnusedOk

`func (o *VolumeSummary) GetUnusedOk() (*Amount, bool)`

GetUnusedOk returns a tuple with the Unused field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnused

`func (o *VolumeSummary) SetUnused(v Amount)`

SetUnused sets Unused field to given value.


### GetVolumes

`func (o *VolumeSummary) GetVolumes() []VolumeInfo`

GetVolumes returns the Volumes field if non-nil, zero value otherwise.

### GetVolumesOk

`func (o *VolumeSummary) GetVolumesOk() (*[]VolumeInfo, bool)`

GetVolumesOk returns a tuple with the Volumes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVolumes

`func (o *VolumeSummary) SetVolumes(v []VolumeInfo)`

SetVolumes sets Volumes field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


