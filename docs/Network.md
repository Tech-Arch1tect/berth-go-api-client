# Network

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Containers** | Pointer to [**map[string]NetworkEndpoint**](NetworkEndpoint.md) |  | [optional] 
**Created** | Pointer to **string** |  | [optional] 
**Driver** | Pointer to **string** |  | [optional] 
**Exists** | **bool** |  | 
**External** | Pointer to **bool** |  | [optional] 
**Ipam** | Pointer to [**NullableNetworkIPAM**](NetworkIPAM.md) |  | [optional] 
**Labels** | Pointer to **map[string]string** |  | [optional] 
**Name** | **string** |  | 
**Options** | Pointer to **map[string]string** |  | [optional] 

## Methods

### NewNetwork

`func NewNetwork(exists bool, name string, ) *Network`

NewNetwork instantiates a new Network object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewNetworkWithDefaults

`func NewNetworkWithDefaults() *Network`

NewNetworkWithDefaults instantiates a new Network object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContainers

`func (o *Network) GetContainers() map[string]NetworkEndpoint`

GetContainers returns the Containers field if non-nil, zero value otherwise.

### GetContainersOk

`func (o *Network) GetContainersOk() (*map[string]NetworkEndpoint, bool)`

GetContainersOk returns a tuple with the Containers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainers

`func (o *Network) SetContainers(v map[string]NetworkEndpoint)`

SetContainers sets Containers field to given value.

### HasContainers

`func (o *Network) HasContainers() bool`

HasContainers returns a boolean if a field has been set.

### GetCreated

`func (o *Network) GetCreated() string`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *Network) GetCreatedOk() (*string, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *Network) SetCreated(v string)`

SetCreated sets Created field to given value.

### HasCreated

`func (o *Network) HasCreated() bool`

HasCreated returns a boolean if a field has been set.

### GetDriver

`func (o *Network) GetDriver() string`

GetDriver returns the Driver field if non-nil, zero value otherwise.

### GetDriverOk

`func (o *Network) GetDriverOk() (*string, bool)`

GetDriverOk returns a tuple with the Driver field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDriver

`func (o *Network) SetDriver(v string)`

SetDriver sets Driver field to given value.

### HasDriver

`func (o *Network) HasDriver() bool`

HasDriver returns a boolean if a field has been set.

### GetExists

`func (o *Network) GetExists() bool`

GetExists returns the Exists field if non-nil, zero value otherwise.

### GetExistsOk

`func (o *Network) GetExistsOk() (*bool, bool)`

GetExistsOk returns a tuple with the Exists field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExists

`func (o *Network) SetExists(v bool)`

SetExists sets Exists field to given value.


### GetExternal

`func (o *Network) GetExternal() bool`

GetExternal returns the External field if non-nil, zero value otherwise.

### GetExternalOk

`func (o *Network) GetExternalOk() (*bool, bool)`

GetExternalOk returns a tuple with the External field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternal

`func (o *Network) SetExternal(v bool)`

SetExternal sets External field to given value.

### HasExternal

`func (o *Network) HasExternal() bool`

HasExternal returns a boolean if a field has been set.

### GetIpam

`func (o *Network) GetIpam() NetworkIPAM`

GetIpam returns the Ipam field if non-nil, zero value otherwise.

### GetIpamOk

`func (o *Network) GetIpamOk() (*NetworkIPAM, bool)`

GetIpamOk returns a tuple with the Ipam field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpam

`func (o *Network) SetIpam(v NetworkIPAM)`

SetIpam sets Ipam field to given value.

### HasIpam

`func (o *Network) HasIpam() bool`

HasIpam returns a boolean if a field has been set.

### SetIpamNil

`func (o *Network) SetIpamNil(b bool)`

 SetIpamNil sets the value for Ipam to be an explicit nil

### UnsetIpam
`func (o *Network) UnsetIpam()`

UnsetIpam ensures that no value is present for Ipam, not even an explicit nil
### GetLabels

`func (o *Network) GetLabels() map[string]string`

GetLabels returns the Labels field if non-nil, zero value otherwise.

### GetLabelsOk

`func (o *Network) GetLabelsOk() (*map[string]string, bool)`

GetLabelsOk returns a tuple with the Labels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabels

`func (o *Network) SetLabels(v map[string]string)`

SetLabels sets Labels field to given value.

### HasLabels

`func (o *Network) HasLabels() bool`

HasLabels returns a boolean if a field has been set.

### GetName

`func (o *Network) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Network) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Network) SetName(v string)`

SetName sets Name field to given value.


### GetOptions

`func (o *Network) GetOptions() map[string]string`

GetOptions returns the Options field if non-nil, zero value otherwise.

### GetOptionsOk

`func (o *Network) GetOptionsOk() (*map[string]string, bool)`

GetOptionsOk returns a tuple with the Options field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOptions

`func (o *Network) SetOptions(v map[string]string)`

SetOptions sets Options field to given value.

### HasOptions

`func (o *Network) HasOptions() bool`

HasOptions returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


