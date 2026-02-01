# ListServersResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Servers** | [**[]ServerInfo**](ServerInfo.md) |  | 

## Methods

### NewListServersResponseData

`func NewListServersResponseData(servers []ServerInfo, ) *ListServersResponseData`

NewListServersResponseData instantiates a new ListServersResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListServersResponseDataWithDefaults

`func NewListServersResponseDataWithDefaults() *ListServersResponseData`

NewListServersResponseDataWithDefaults instantiates a new ListServersResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetServers

`func (o *ListServersResponseData) GetServers() []ServerInfo`

GetServers returns the Servers field if non-nil, zero value otherwise.

### GetServersOk

`func (o *ListServersResponseData) GetServersOk() (*[]ServerInfo, bool)`

GetServersOk returns a tuple with the Servers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServers

`func (o *ListServersResponseData) SetServers(v []ServerInfo)`

SetServers sets Servers field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


