# IpamPool

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Gateway** | Pointer to **string** |  | [optional] 
**IpRange** | Pointer to **string** |  | [optional] 
**Subnet** | Pointer to **string** |  | [optional] 

## Methods

### NewIpamPool

`func NewIpamPool() *IpamPool`

NewIpamPool instantiates a new IpamPool object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIpamPoolWithDefaults

`func NewIpamPoolWithDefaults() *IpamPool`

NewIpamPoolWithDefaults instantiates a new IpamPool object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGateway

`func (o *IpamPool) GetGateway() string`

GetGateway returns the Gateway field if non-nil, zero value otherwise.

### GetGatewayOk

`func (o *IpamPool) GetGatewayOk() (*string, bool)`

GetGatewayOk returns a tuple with the Gateway field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGateway

`func (o *IpamPool) SetGateway(v string)`

SetGateway sets Gateway field to given value.

### HasGateway

`func (o *IpamPool) HasGateway() bool`

HasGateway returns a boolean if a field has been set.

### GetIpRange

`func (o *IpamPool) GetIpRange() string`

GetIpRange returns the IpRange field if non-nil, zero value otherwise.

### GetIpRangeOk

`func (o *IpamPool) GetIpRangeOk() (*string, bool)`

GetIpRangeOk returns a tuple with the IpRange field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpRange

`func (o *IpamPool) SetIpRange(v string)`

SetIpRange sets IpRange field to given value.

### HasIpRange

`func (o *IpamPool) HasIpRange() bool`

HasIpRange returns a boolean if a field has been set.

### GetSubnet

`func (o *IpamPool) GetSubnet() string`

GetSubnet returns the Subnet field if non-nil, zero value otherwise.

### GetSubnetOk

`func (o *IpamPool) GetSubnetOk() (*string, bool)`

GetSubnetOk returns a tuple with the Subnet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubnet

`func (o *IpamPool) SetSubnet(v string)`

SetSubnet sets Subnet field to given value.

### HasSubnet

`func (o *IpamPool) HasSubnet() bool`

HasSubnet returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


