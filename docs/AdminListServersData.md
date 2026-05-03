# AdminListServersData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Servers** | [**[]ServerInfo**](ServerInfo.md) |  | 

## Methods

### NewAdminListServersData

`func NewAdminListServersData(servers []ServerInfo, ) *AdminListServersData`

NewAdminListServersData instantiates a new AdminListServersData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAdminListServersDataWithDefaults

`func NewAdminListServersDataWithDefaults() *AdminListServersData`

NewAdminListServersDataWithDefaults instantiates a new AdminListServersData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetServers

`func (o *AdminListServersData) GetServers() []ServerInfo`

GetServers returns the Servers field if non-nil, zero value otherwise.

### GetServersOk

`func (o *AdminListServersData) GetServersOk() (*[]ServerInfo, bool)`

GetServersOk returns a tuple with the Servers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServers

`func (o *AdminListServersData) SetServers(v []ServerInfo)`

SetServers sets Servers field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


