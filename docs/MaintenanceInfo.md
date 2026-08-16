# MaintenanceInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BuildCacheSummary** | [**BuildCacheSummary**](BuildCacheSummary.md) |  | 
**ContainerSummary** | [**ContainerSummary**](ContainerSummary.md) |  | 
**ImageSummary** | [**ImageSummary**](ImageSummary.md) |  | 
**LastUpdated** | **time.Time** |  | 
**NetworkSummary** | [**NetworkSummary**](NetworkSummary.md) |  | 
**SystemCleanupCovers** | **[]string** |  | 
**SystemInfo** | [**SystemInfo**](SystemInfo.md) |  | 
**VolumeSummary** | [**VolumeSummary**](VolumeSummary.md) |  | 

## Methods

### NewMaintenanceInfo

`func NewMaintenanceInfo(buildCacheSummary BuildCacheSummary, containerSummary ContainerSummary, imageSummary ImageSummary, lastUpdated time.Time, networkSummary NetworkSummary, systemCleanupCovers []string, systemInfo SystemInfo, volumeSummary VolumeSummary, ) *MaintenanceInfo`

NewMaintenanceInfo instantiates a new MaintenanceInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMaintenanceInfoWithDefaults

`func NewMaintenanceInfoWithDefaults() *MaintenanceInfo`

NewMaintenanceInfoWithDefaults instantiates a new MaintenanceInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBuildCacheSummary

`func (o *MaintenanceInfo) GetBuildCacheSummary() BuildCacheSummary`

GetBuildCacheSummary returns the BuildCacheSummary field if non-nil, zero value otherwise.

### GetBuildCacheSummaryOk

`func (o *MaintenanceInfo) GetBuildCacheSummaryOk() (*BuildCacheSummary, bool)`

GetBuildCacheSummaryOk returns a tuple with the BuildCacheSummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildCacheSummary

`func (o *MaintenanceInfo) SetBuildCacheSummary(v BuildCacheSummary)`

SetBuildCacheSummary sets BuildCacheSummary field to given value.


### GetContainerSummary

`func (o *MaintenanceInfo) GetContainerSummary() ContainerSummary`

GetContainerSummary returns the ContainerSummary field if non-nil, zero value otherwise.

### GetContainerSummaryOk

`func (o *MaintenanceInfo) GetContainerSummaryOk() (*ContainerSummary, bool)`

GetContainerSummaryOk returns a tuple with the ContainerSummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainerSummary

`func (o *MaintenanceInfo) SetContainerSummary(v ContainerSummary)`

SetContainerSummary sets ContainerSummary field to given value.


### GetImageSummary

`func (o *MaintenanceInfo) GetImageSummary() ImageSummary`

GetImageSummary returns the ImageSummary field if non-nil, zero value otherwise.

### GetImageSummaryOk

`func (o *MaintenanceInfo) GetImageSummaryOk() (*ImageSummary, bool)`

GetImageSummaryOk returns a tuple with the ImageSummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageSummary

`func (o *MaintenanceInfo) SetImageSummary(v ImageSummary)`

SetImageSummary sets ImageSummary field to given value.


### GetLastUpdated

`func (o *MaintenanceInfo) GetLastUpdated() time.Time`

GetLastUpdated returns the LastUpdated field if non-nil, zero value otherwise.

### GetLastUpdatedOk

`func (o *MaintenanceInfo) GetLastUpdatedOk() (*time.Time, bool)`

GetLastUpdatedOk returns a tuple with the LastUpdated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastUpdated

`func (o *MaintenanceInfo) SetLastUpdated(v time.Time)`

SetLastUpdated sets LastUpdated field to given value.


### GetNetworkSummary

`func (o *MaintenanceInfo) GetNetworkSummary() NetworkSummary`

GetNetworkSummary returns the NetworkSummary field if non-nil, zero value otherwise.

### GetNetworkSummaryOk

`func (o *MaintenanceInfo) GetNetworkSummaryOk() (*NetworkSummary, bool)`

GetNetworkSummaryOk returns a tuple with the NetworkSummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworkSummary

`func (o *MaintenanceInfo) SetNetworkSummary(v NetworkSummary)`

SetNetworkSummary sets NetworkSummary field to given value.


### GetSystemCleanupCovers

`func (o *MaintenanceInfo) GetSystemCleanupCovers() []string`

GetSystemCleanupCovers returns the SystemCleanupCovers field if non-nil, zero value otherwise.

### GetSystemCleanupCoversOk

`func (o *MaintenanceInfo) GetSystemCleanupCoversOk() (*[]string, bool)`

GetSystemCleanupCoversOk returns a tuple with the SystemCleanupCovers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSystemCleanupCovers

`func (o *MaintenanceInfo) SetSystemCleanupCovers(v []string)`

SetSystemCleanupCovers sets SystemCleanupCovers field to given value.


### GetSystemInfo

`func (o *MaintenanceInfo) GetSystemInfo() SystemInfo`

GetSystemInfo returns the SystemInfo field if non-nil, zero value otherwise.

### GetSystemInfoOk

`func (o *MaintenanceInfo) GetSystemInfoOk() (*SystemInfo, bool)`

GetSystemInfoOk returns a tuple with the SystemInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSystemInfo

`func (o *MaintenanceInfo) SetSystemInfo(v SystemInfo)`

SetSystemInfo sets SystemInfo field to given value.


### GetVolumeSummary

`func (o *MaintenanceInfo) GetVolumeSummary() VolumeSummary`

GetVolumeSummary returns the VolumeSummary field if non-nil, zero value otherwise.

### GetVolumeSummaryOk

`func (o *MaintenanceInfo) GetVolumeSummaryOk() (*VolumeSummary, bool)`

GetVolumeSummaryOk returns a tuple with the VolumeSummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVolumeSummary

`func (o *MaintenanceInfo) SetVolumeSummary(v VolumeSummary)`

SetVolumeSummary sets VolumeSummary field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


