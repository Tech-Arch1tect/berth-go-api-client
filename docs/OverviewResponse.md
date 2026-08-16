# OverviewResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Servers** | [**[]ServerBackups**](ServerBackups.md) |  | 

## Methods

### NewOverviewResponse

`func NewOverviewResponse(servers []ServerBackups, ) *OverviewResponse`

NewOverviewResponse instantiates a new OverviewResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOverviewResponseWithDefaults

`func NewOverviewResponseWithDefaults() *OverviewResponse`

NewOverviewResponseWithDefaults instantiates a new OverviewResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetServers

`func (o *OverviewResponse) GetServers() []ServerBackups`

GetServers returns the Servers field if non-nil, zero value otherwise.

### GetServersOk

`func (o *OverviewResponse) GetServersOk() (*[]ServerBackups, bool)`

GetServersOk returns a tuple with the Servers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServers

`func (o *OverviewResponse) SetServers(v []ServerBackups)`

SetServers sets Servers field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


