# PortMapping

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**HostIp** | Pointer to **string** |  | [optional] 
**Protocol** | Pointer to **string** |  | [optional] 
**Published** | Pointer to **string** |  | [optional] 
**Target** | **string** |  | 

## Methods

### NewPortMapping

`func NewPortMapping(target string, ) *PortMapping`

NewPortMapping instantiates a new PortMapping object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPortMappingWithDefaults

`func NewPortMappingWithDefaults() *PortMapping`

NewPortMappingWithDefaults instantiates a new PortMapping object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHostIp

`func (o *PortMapping) GetHostIp() string`

GetHostIp returns the HostIp field if non-nil, zero value otherwise.

### GetHostIpOk

`func (o *PortMapping) GetHostIpOk() (*string, bool)`

GetHostIpOk returns a tuple with the HostIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHostIp

`func (o *PortMapping) SetHostIp(v string)`

SetHostIp sets HostIp field to given value.

### HasHostIp

`func (o *PortMapping) HasHostIp() bool`

HasHostIp returns a boolean if a field has been set.

### GetProtocol

`func (o *PortMapping) GetProtocol() string`

GetProtocol returns the Protocol field if non-nil, zero value otherwise.

### GetProtocolOk

`func (o *PortMapping) GetProtocolOk() (*string, bool)`

GetProtocolOk returns a tuple with the Protocol field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProtocol

`func (o *PortMapping) SetProtocol(v string)`

SetProtocol sets Protocol field to given value.

### HasProtocol

`func (o *PortMapping) HasProtocol() bool`

HasProtocol returns a boolean if a field has been set.

### GetPublished

`func (o *PortMapping) GetPublished() string`

GetPublished returns the Published field if non-nil, zero value otherwise.

### GetPublishedOk

`func (o *PortMapping) GetPublishedOk() (*string, bool)`

GetPublishedOk returns a tuple with the Published field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublished

`func (o *PortMapping) SetPublished(v string)`

SetPublished sets Published field to given value.

### HasPublished

`func (o *PortMapping) HasPublished() bool`

HasPublished returns a boolean if a field has been set.

### GetTarget

`func (o *PortMapping) GetTarget() string`

GetTarget returns the Target field if non-nil, zero value otherwise.

### GetTargetOk

`func (o *PortMapping) GetTargetOk() (*string, bool)`

GetTargetOk returns a tuple with the Target field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTarget

`func (o *PortMapping) SetTarget(v string)`

SetTarget sets Target field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


