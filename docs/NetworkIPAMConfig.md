# NetworkIPAMConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Gateway** | Pointer to **string** |  | [optional] 
**Subnet** | Pointer to **string** |  | [optional] 

## Methods

### NewNetworkIPAMConfig

`func NewNetworkIPAMConfig() *NetworkIPAMConfig`

NewNetworkIPAMConfig instantiates a new NetworkIPAMConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewNetworkIPAMConfigWithDefaults

`func NewNetworkIPAMConfigWithDefaults() *NetworkIPAMConfig`

NewNetworkIPAMConfigWithDefaults instantiates a new NetworkIPAMConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGateway

`func (o *NetworkIPAMConfig) GetGateway() string`

GetGateway returns the Gateway field if non-nil, zero value otherwise.

### GetGatewayOk

`func (o *NetworkIPAMConfig) GetGatewayOk() (*string, bool)`

GetGatewayOk returns a tuple with the Gateway field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGateway

`func (o *NetworkIPAMConfig) SetGateway(v string)`

SetGateway sets Gateway field to given value.

### HasGateway

`func (o *NetworkIPAMConfig) HasGateway() bool`

HasGateway returns a boolean if a field has been set.

### GetSubnet

`func (o *NetworkIPAMConfig) GetSubnet() string`

GetSubnet returns the Subnet field if non-nil, zero value otherwise.

### GetSubnetOk

`func (o *NetworkIPAMConfig) GetSubnetOk() (*string, bool)`

GetSubnetOk returns a tuple with the Subnet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubnet

`func (o *NetworkIPAMConfig) SetSubnet(v string)`

SetSubnet sets Subnet field to given value.

### HasSubnet

`func (o *NetworkIPAMConfig) HasSubnet() bool`

HasSubnet returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


