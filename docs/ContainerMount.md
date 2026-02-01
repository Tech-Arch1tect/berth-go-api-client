# ContainerMount

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Destination** | **string** |  | 
**Driver** | Pointer to **string** |  | [optional] 
**Mode** | Pointer to **string** |  | [optional] 
**Propagation** | Pointer to **string** |  | [optional] 
**Rw** | **bool** |  | 
**Source** | **string** |  | 
**Type** | **string** |  | 

## Methods

### NewContainerMount

`func NewContainerMount(destination string, rw bool, source string, type_ string, ) *ContainerMount`

NewContainerMount instantiates a new ContainerMount object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContainerMountWithDefaults

`func NewContainerMountWithDefaults() *ContainerMount`

NewContainerMountWithDefaults instantiates a new ContainerMount object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDestination

`func (o *ContainerMount) GetDestination() string`

GetDestination returns the Destination field if non-nil, zero value otherwise.

### GetDestinationOk

`func (o *ContainerMount) GetDestinationOk() (*string, bool)`

GetDestinationOk returns a tuple with the Destination field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestination

`func (o *ContainerMount) SetDestination(v string)`

SetDestination sets Destination field to given value.


### GetDriver

`func (o *ContainerMount) GetDriver() string`

GetDriver returns the Driver field if non-nil, zero value otherwise.

### GetDriverOk

`func (o *ContainerMount) GetDriverOk() (*string, bool)`

GetDriverOk returns a tuple with the Driver field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDriver

`func (o *ContainerMount) SetDriver(v string)`

SetDriver sets Driver field to given value.

### HasDriver

`func (o *ContainerMount) HasDriver() bool`

HasDriver returns a boolean if a field has been set.

### GetMode

`func (o *ContainerMount) GetMode() string`

GetMode returns the Mode field if non-nil, zero value otherwise.

### GetModeOk

`func (o *ContainerMount) GetModeOk() (*string, bool)`

GetModeOk returns a tuple with the Mode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMode

`func (o *ContainerMount) SetMode(v string)`

SetMode sets Mode field to given value.

### HasMode

`func (o *ContainerMount) HasMode() bool`

HasMode returns a boolean if a field has been set.

### GetPropagation

`func (o *ContainerMount) GetPropagation() string`

GetPropagation returns the Propagation field if non-nil, zero value otherwise.

### GetPropagationOk

`func (o *ContainerMount) GetPropagationOk() (*string, bool)`

GetPropagationOk returns a tuple with the Propagation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPropagation

`func (o *ContainerMount) SetPropagation(v string)`

SetPropagation sets Propagation field to given value.

### HasPropagation

`func (o *ContainerMount) HasPropagation() bool`

HasPropagation returns a boolean if a field has been set.

### GetRw

`func (o *ContainerMount) GetRw() bool`

GetRw returns the Rw field if non-nil, zero value otherwise.

### GetRwOk

`func (o *ContainerMount) GetRwOk() (*bool, bool)`

GetRwOk returns a tuple with the Rw field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRw

`func (o *ContainerMount) SetRw(v bool)`

SetRw sets Rw field to given value.


### GetSource

`func (o *ContainerMount) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *ContainerMount) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *ContainerMount) SetSource(v string)`

SetSource sets Source field to given value.


### GetType

`func (o *ContainerMount) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ContainerMount) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ContainerMount) SetType(v string)`

SetType sets Type field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


