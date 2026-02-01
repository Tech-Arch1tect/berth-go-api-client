# ScanComparison

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BaseOnlyImages** | **[]string** |  | 
**BaseScan** | [**NullableImageScan**](ImageScan.md) |  | 
**CommonImages** | **[]string** |  | 
**CompareOnlyImages** | **[]string** |  | 
**CompareScan** | [**NullableImageScan**](ImageScan.md) |  | 
**FixedVulnerabilities** | [**[]ImageVulnerability**](ImageVulnerability.md) |  | 
**NewVulnerabilities** | [**[]ImageVulnerability**](ImageVulnerability.md) |  | 
**SameScope** | **bool** |  | 
**UnchangedCount** | **int32** |  | 

## Methods

### NewScanComparison

`func NewScanComparison(baseOnlyImages []string, baseScan NullableImageScan, commonImages []string, compareOnlyImages []string, compareScan NullableImageScan, fixedVulnerabilities []ImageVulnerability, newVulnerabilities []ImageVulnerability, sameScope bool, unchangedCount int32, ) *ScanComparison`

NewScanComparison instantiates a new ScanComparison object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewScanComparisonWithDefaults

`func NewScanComparisonWithDefaults() *ScanComparison`

NewScanComparisonWithDefaults instantiates a new ScanComparison object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBaseOnlyImages

`func (o *ScanComparison) GetBaseOnlyImages() []string`

GetBaseOnlyImages returns the BaseOnlyImages field if non-nil, zero value otherwise.

### GetBaseOnlyImagesOk

`func (o *ScanComparison) GetBaseOnlyImagesOk() (*[]string, bool)`

GetBaseOnlyImagesOk returns a tuple with the BaseOnlyImages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseOnlyImages

`func (o *ScanComparison) SetBaseOnlyImages(v []string)`

SetBaseOnlyImages sets BaseOnlyImages field to given value.


### GetBaseScan

`func (o *ScanComparison) GetBaseScan() ImageScan`

GetBaseScan returns the BaseScan field if non-nil, zero value otherwise.

### GetBaseScanOk

`func (o *ScanComparison) GetBaseScanOk() (*ImageScan, bool)`

GetBaseScanOk returns a tuple with the BaseScan field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseScan

`func (o *ScanComparison) SetBaseScan(v ImageScan)`

SetBaseScan sets BaseScan field to given value.


### SetBaseScanNil

`func (o *ScanComparison) SetBaseScanNil(b bool)`

 SetBaseScanNil sets the value for BaseScan to be an explicit nil

### UnsetBaseScan
`func (o *ScanComparison) UnsetBaseScan()`

UnsetBaseScan ensures that no value is present for BaseScan, not even an explicit nil
### GetCommonImages

`func (o *ScanComparison) GetCommonImages() []string`

GetCommonImages returns the CommonImages field if non-nil, zero value otherwise.

### GetCommonImagesOk

`func (o *ScanComparison) GetCommonImagesOk() (*[]string, bool)`

GetCommonImagesOk returns a tuple with the CommonImages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommonImages

`func (o *ScanComparison) SetCommonImages(v []string)`

SetCommonImages sets CommonImages field to given value.


### GetCompareOnlyImages

`func (o *ScanComparison) GetCompareOnlyImages() []string`

GetCompareOnlyImages returns the CompareOnlyImages field if non-nil, zero value otherwise.

### GetCompareOnlyImagesOk

`func (o *ScanComparison) GetCompareOnlyImagesOk() (*[]string, bool)`

GetCompareOnlyImagesOk returns a tuple with the CompareOnlyImages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompareOnlyImages

`func (o *ScanComparison) SetCompareOnlyImages(v []string)`

SetCompareOnlyImages sets CompareOnlyImages field to given value.


### GetCompareScan

`func (o *ScanComparison) GetCompareScan() ImageScan`

GetCompareScan returns the CompareScan field if non-nil, zero value otherwise.

### GetCompareScanOk

`func (o *ScanComparison) GetCompareScanOk() (*ImageScan, bool)`

GetCompareScanOk returns a tuple with the CompareScan field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompareScan

`func (o *ScanComparison) SetCompareScan(v ImageScan)`

SetCompareScan sets CompareScan field to given value.


### SetCompareScanNil

`func (o *ScanComparison) SetCompareScanNil(b bool)`

 SetCompareScanNil sets the value for CompareScan to be an explicit nil

### UnsetCompareScan
`func (o *ScanComparison) UnsetCompareScan()`

UnsetCompareScan ensures that no value is present for CompareScan, not even an explicit nil
### GetFixedVulnerabilities

`func (o *ScanComparison) GetFixedVulnerabilities() []ImageVulnerability`

GetFixedVulnerabilities returns the FixedVulnerabilities field if non-nil, zero value otherwise.

### GetFixedVulnerabilitiesOk

`func (o *ScanComparison) GetFixedVulnerabilitiesOk() (*[]ImageVulnerability, bool)`

GetFixedVulnerabilitiesOk returns a tuple with the FixedVulnerabilities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFixedVulnerabilities

`func (o *ScanComparison) SetFixedVulnerabilities(v []ImageVulnerability)`

SetFixedVulnerabilities sets FixedVulnerabilities field to given value.


### GetNewVulnerabilities

`func (o *ScanComparison) GetNewVulnerabilities() []ImageVulnerability`

GetNewVulnerabilities returns the NewVulnerabilities field if non-nil, zero value otherwise.

### GetNewVulnerabilitiesOk

`func (o *ScanComparison) GetNewVulnerabilitiesOk() (*[]ImageVulnerability, bool)`

GetNewVulnerabilitiesOk returns a tuple with the NewVulnerabilities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewVulnerabilities

`func (o *ScanComparison) SetNewVulnerabilities(v []ImageVulnerability)`

SetNewVulnerabilities sets NewVulnerabilities field to given value.


### GetSameScope

`func (o *ScanComparison) GetSameScope() bool`

GetSameScope returns the SameScope field if non-nil, zero value otherwise.

### GetSameScopeOk

`func (o *ScanComparison) GetSameScopeOk() (*bool, bool)`

GetSameScopeOk returns a tuple with the SameScope field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSameScope

`func (o *ScanComparison) SetSameScope(v bool)`

SetSameScope sets SameScope field to given value.


### GetUnchangedCount

`func (o *ScanComparison) GetUnchangedCount() int32`

GetUnchangedCount returns the UnchangedCount field if non-nil, zero value otherwise.

### GetUnchangedCountOk

`func (o *ScanComparison) GetUnchangedCountOk() (*int32, bool)`

GetUnchangedCountOk returns a tuple with the UnchangedCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnchangedCount

`func (o *ScanComparison) SetUnchangedCount(v int32)`

SetUnchangedCount sets UnchangedCount field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


