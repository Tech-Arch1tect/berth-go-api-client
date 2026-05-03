# GetServerData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Server** | [**ServerInfo**](ServerInfo.md) |  | 

## Methods

### NewGetServerData

`func NewGetServerData(server ServerInfo, ) *GetServerData`

NewGetServerData instantiates a new GetServerData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetServerDataWithDefaults

`func NewGetServerDataWithDefaults() *GetServerData`

NewGetServerDataWithDefaults instantiates a new GetServerData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetServer

`func (o *GetServerData) GetServer() ServerInfo`

GetServer returns the Server field if non-nil, zero value otherwise.

### GetServerOk

`func (o *GetServerData) GetServerOk() (*ServerInfo, bool)`

GetServerOk returns a tuple with the Server field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServer

`func (o *GetServerData) SetServer(v ServerInfo)`

SetServer sets Server field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


