# NetworkInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Created** | **time.Time** |  | 
**Driver** | **string** |  | 
**Id** | **string** |  | 
**Internal** | **bool** |  | 
**Labels** | **map[string]string** |  | 
**Name** | **string** |  | 
**Scope** | **string** |  | 
**Subnet** | **string** |  | 
**Unused** | **bool** |  | 

## Methods

### NewNetworkInfo

`func NewNetworkInfo(created time.Time, driver string, id string, internal bool, labels map[string]string, name string, scope string, subnet string, unused bool, ) *NetworkInfo`

NewNetworkInfo instantiates a new NetworkInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewNetworkInfoWithDefaults

`func NewNetworkInfoWithDefaults() *NetworkInfo`

NewNetworkInfoWithDefaults instantiates a new NetworkInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreated

`func (o *NetworkInfo) GetCreated() time.Time`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *NetworkInfo) GetCreatedOk() (*time.Time, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *NetworkInfo) SetCreated(v time.Time)`

SetCreated sets Created field to given value.


### GetDriver

`func (o *NetworkInfo) GetDriver() string`

GetDriver returns the Driver field if non-nil, zero value otherwise.

### GetDriverOk

`func (o *NetworkInfo) GetDriverOk() (*string, bool)`

GetDriverOk returns a tuple with the Driver field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDriver

`func (o *NetworkInfo) SetDriver(v string)`

SetDriver sets Driver field to given value.


### GetId

`func (o *NetworkInfo) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *NetworkInfo) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *NetworkInfo) SetId(v string)`

SetId sets Id field to given value.


### GetInternal

`func (o *NetworkInfo) GetInternal() bool`

GetInternal returns the Internal field if non-nil, zero value otherwise.

### GetInternalOk

`func (o *NetworkInfo) GetInternalOk() (*bool, bool)`

GetInternalOk returns a tuple with the Internal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInternal

`func (o *NetworkInfo) SetInternal(v bool)`

SetInternal sets Internal field to given value.


### GetLabels

`func (o *NetworkInfo) GetLabels() map[string]string`

GetLabels returns the Labels field if non-nil, zero value otherwise.

### GetLabelsOk

`func (o *NetworkInfo) GetLabelsOk() (*map[string]string, bool)`

GetLabelsOk returns a tuple with the Labels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabels

`func (o *NetworkInfo) SetLabels(v map[string]string)`

SetLabels sets Labels field to given value.


### GetName

`func (o *NetworkInfo) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *NetworkInfo) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *NetworkInfo) SetName(v string)`

SetName sets Name field to given value.


### GetScope

`func (o *NetworkInfo) GetScope() string`

GetScope returns the Scope field if non-nil, zero value otherwise.

### GetScopeOk

`func (o *NetworkInfo) GetScopeOk() (*string, bool)`

GetScopeOk returns a tuple with the Scope field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScope

`func (o *NetworkInfo) SetScope(v string)`

SetScope sets Scope field to given value.


### GetSubnet

`func (o *NetworkInfo) GetSubnet() string`

GetSubnet returns the Subnet field if non-nil, zero value otherwise.

### GetSubnetOk

`func (o *NetworkInfo) GetSubnetOk() (*string, bool)`

GetSubnetOk returns a tuple with the Subnet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubnet

`func (o *NetworkInfo) SetSubnet(v string)`

SetSubnet sets Subnet field to given value.


### GetUnused

`func (o *NetworkInfo) GetUnused() bool`

GetUnused returns the Unused field if non-nil, zero value otherwise.

### GetUnusedOk

`func (o *NetworkInfo) GetUnusedOk() (*bool, bool)`

GetUnusedOk returns a tuple with the Unused field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnused

`func (o *NetworkInfo) SetUnused(v bool)`

SetUnused sets Unused field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


