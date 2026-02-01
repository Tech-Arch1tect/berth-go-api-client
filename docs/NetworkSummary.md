# NetworkSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Networks** | [**[]NetworkInfo**](NetworkInfo.md) |  | 
**TotalCount** | **int32** |  | 
**UnusedCount** | **int32** |  | 

## Methods

### NewNetworkSummary

`func NewNetworkSummary(networks []NetworkInfo, totalCount int32, unusedCount int32, ) *NetworkSummary`

NewNetworkSummary instantiates a new NetworkSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewNetworkSummaryWithDefaults

`func NewNetworkSummaryWithDefaults() *NetworkSummary`

NewNetworkSummaryWithDefaults instantiates a new NetworkSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNetworks

`func (o *NetworkSummary) GetNetworks() []NetworkInfo`

GetNetworks returns the Networks field if non-nil, zero value otherwise.

### GetNetworksOk

`func (o *NetworkSummary) GetNetworksOk() (*[]NetworkInfo, bool)`

GetNetworksOk returns a tuple with the Networks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworks

`func (o *NetworkSummary) SetNetworks(v []NetworkInfo)`

SetNetworks sets Networks field to given value.


### GetTotalCount

`func (o *NetworkSummary) GetTotalCount() int32`

GetTotalCount returns the TotalCount field if non-nil, zero value otherwise.

### GetTotalCountOk

`func (o *NetworkSummary) GetTotalCountOk() (*int32, bool)`

GetTotalCountOk returns a tuple with the TotalCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCount

`func (o *NetworkSummary) SetTotalCount(v int32)`

SetTotalCount sets TotalCount field to given value.


### GetUnusedCount

`func (o *NetworkSummary) GetUnusedCount() int32`

GetUnusedCount returns the UnusedCount field if non-nil, zero value otherwise.

### GetUnusedCountOk

`func (o *NetworkSummary) GetUnusedCountOk() (*int32, bool)`

GetUnusedCountOk returns a tuple with the UnusedCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnusedCount

`func (o *NetworkSummary) SetUnusedCount(v int32)`

SetUnusedCount sets UnusedCount field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


