# VolumeSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TotalCount** | **int32** |  | 
**TotalSize** | **int32** |  | 
**UnusedCount** | **int32** |  | 
**UnusedSize** | **int32** |  | 
**Volumes** | [**[]VolumeInfo**](VolumeInfo.md) |  | 

## Methods

### NewVolumeSummary

`func NewVolumeSummary(totalCount int32, totalSize int32, unusedCount int32, unusedSize int32, volumes []VolumeInfo, ) *VolumeSummary`

NewVolumeSummary instantiates a new VolumeSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVolumeSummaryWithDefaults

`func NewVolumeSummaryWithDefaults() *VolumeSummary`

NewVolumeSummaryWithDefaults instantiates a new VolumeSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTotalCount

`func (o *VolumeSummary) GetTotalCount() int32`

GetTotalCount returns the TotalCount field if non-nil, zero value otherwise.

### GetTotalCountOk

`func (o *VolumeSummary) GetTotalCountOk() (*int32, bool)`

GetTotalCountOk returns a tuple with the TotalCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCount

`func (o *VolumeSummary) SetTotalCount(v int32)`

SetTotalCount sets TotalCount field to given value.


### GetTotalSize

`func (o *VolumeSummary) GetTotalSize() int32`

GetTotalSize returns the TotalSize field if non-nil, zero value otherwise.

### GetTotalSizeOk

`func (o *VolumeSummary) GetTotalSizeOk() (*int32, bool)`

GetTotalSizeOk returns a tuple with the TotalSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalSize

`func (o *VolumeSummary) SetTotalSize(v int32)`

SetTotalSize sets TotalSize field to given value.


### GetUnusedCount

`func (o *VolumeSummary) GetUnusedCount() int32`

GetUnusedCount returns the UnusedCount field if non-nil, zero value otherwise.

### GetUnusedCountOk

`func (o *VolumeSummary) GetUnusedCountOk() (*int32, bool)`

GetUnusedCountOk returns a tuple with the UnusedCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnusedCount

`func (o *VolumeSummary) SetUnusedCount(v int32)`

SetUnusedCount sets UnusedCount field to given value.


### GetUnusedSize

`func (o *VolumeSummary) GetUnusedSize() int32`

GetUnusedSize returns the UnusedSize field if non-nil, zero value otherwise.

### GetUnusedSizeOk

`func (o *VolumeSummary) GetUnusedSizeOk() (*int32, bool)`

GetUnusedSizeOk returns a tuple with the UnusedSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnusedSize

`func (o *VolumeSummary) SetUnusedSize(v int32)`

SetUnusedSize sets UnusedSize field to given value.


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


