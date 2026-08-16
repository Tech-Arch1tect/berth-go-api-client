# BuildCacheSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Cache** | [**[]BuildCacheInfo**](BuildCacheInfo.md) |  | 
**Total** | [**Amount**](Amount.md) |  | 

## Methods

### NewBuildCacheSummary

`func NewBuildCacheSummary(cache []BuildCacheInfo, total Amount, ) *BuildCacheSummary`

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


### GetTotal

`func (o *BuildCacheSummary) GetTotal() Amount`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *BuildCacheSummary) GetTotalOk() (*Amount, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *BuildCacheSummary) SetTotal(v Amount)`

SetTotal sets Total field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


