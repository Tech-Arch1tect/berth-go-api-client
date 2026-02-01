# NetworkIPAM

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Config** | Pointer to [**[]NetworkIPAMConfig**](NetworkIPAMConfig.md) |  | [optional] 
**Driver** | Pointer to **string** |  | [optional] 

## Methods

### NewNetworkIPAM

`func NewNetworkIPAM() *NetworkIPAM`

NewNetworkIPAM instantiates a new NetworkIPAM object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewNetworkIPAMWithDefaults

`func NewNetworkIPAMWithDefaults() *NetworkIPAM`

NewNetworkIPAMWithDefaults instantiates a new NetworkIPAM object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConfig

`func (o *NetworkIPAM) GetConfig() []NetworkIPAMConfig`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *NetworkIPAM) GetConfigOk() (*[]NetworkIPAMConfig, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *NetworkIPAM) SetConfig(v []NetworkIPAMConfig)`

SetConfig sets Config field to given value.

### HasConfig

`func (o *NetworkIPAM) HasConfig() bool`

HasConfig returns a boolean if a field has been set.

### GetDriver

`func (o *NetworkIPAM) GetDriver() string`

GetDriver returns the Driver field if non-nil, zero value otherwise.

### GetDriverOk

`func (o *NetworkIPAM) GetDriverOk() (*string, bool)`

GetDriverOk returns a tuple with the Driver field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDriver

`func (o *NetworkIPAM) SetDriver(v string)`

SetDriver sets Driver field to given value.

### HasDriver

`func (o *NetworkIPAM) HasDriver() bool`

HasDriver returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


