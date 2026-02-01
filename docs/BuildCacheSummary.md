# BuildCacheSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Cache** | [**[]BuildCacheInfo**](BuildCacheInfo.md) |  | 
**TotalCount** | **int32** |  | 
**TotalSize** | **int32** |  | 

## Methods

### NewBuildCacheSummary

`func NewBuildCacheSummary(cache []BuildCacheInfo, totalCount int32, totalSize int32, ) *BuildCacheSummary`

NewBuildCacheSummary instantiates a new BuildCacheSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBuildCacheSummaryWithDefaults

`func NewBuildCacheSummaryWithDefaults() *BuildCacheSummary`

NewBuildCacheSummaryWithDefaults instantiates a new BuildCacheSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCache

`func (o *BuildCacheSummary) GetCache() []BuildCacheInfo`

GetCache returns the Cache field if non-nil, zero value otherwise.

### GetCacheOk

`func (o *BuildCacheSummary) GetCacheOk() (*[]BuildCacheInfo, bool)`

GetCacheOk returns a tuple with the Cache field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCache

`func (o *BuildCacheSummary) SetCache(v []BuildCacheInfo)`

SetCache sets Cache field to given value.


### GetTotalCount

`func (o *BuildCacheSummary) GetTotalCount() int32`

GetTotalCount returns the TotalCount field if non-nil, zero value otherwise.

### GetTotalCountOk

`func (o *BuildCacheSummary) GetTotalCountOk() (*int32, bool)`

GetTotalCountOk returns a tuple with the TotalCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCount

`func (o *BuildCacheSummary) SetTotalCount(v int32)`

SetTotalCount sets TotalCount field to given value.


### GetTotalSize

`func (o *BuildCacheSummary) GetTotalSize() int32`

GetTotalSize returns the TotalSize field if non-nil, zero value otherwise.

### GetTotalSizeOk

`func (o *BuildCacheSummary) GetTotalSizeOk() (*int32, bool)`

GetTotalSizeOk returns a tuple with the TotalSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalSize

`func (o *BuildCacheSummary) SetTotalSize(v int32)`

SetTotalSize sets TotalSize field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


