# ComposeService

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Containers** | [**[]Container**](Container.md) |  | 
**Image** | Pointer to **string** |  | [optional] 
**Name** | **string** |  | 
**Ports** | Pointer to **[]string** |  | [optional] 

## Methods

### NewComposeService

`func NewComposeService(containers []Container, name string, ) *ComposeService`

NewComposeService instantiates a new ComposeService object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewComposeServiceWithDefaults

`func NewComposeServiceWithDefaults() *ComposeService`

NewComposeServiceWithDefaults instantiates a new ComposeService object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContainers

`func (o *ComposeService) GetContainers() []Container`

GetContainers returns the Containers field if non-nil, zero value otherwise.

### GetContainersOk

`func (o *ComposeService) GetContainersOk() (*[]Container, bool)`

GetContainersOk returns a tuple with the Containers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainers

`func (o *ComposeService) SetContainers(v []Container)`

SetContainers sets Containers field to given value.


### GetImage

`func (o *ComposeService) GetImage() string`

GetImage returns the Image field if non-nil, zero value otherwise.

### GetImageOk

`func (o *ComposeService) GetImageOk() (*string, bool)`

GetImageOk returns a tuple with the Image field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImage

`func (o *ComposeService) SetImage(v string)`

SetImage sets Image field to given value.

### HasImage

`func (o *ComposeService) HasImage() bool`

HasImage returns a boolean if a field has been set.

### GetName

`func (o *ComposeService) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ComposeService) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ComposeService) SetName(v string)`

SetName sets Name field to given value.


### GetPorts

`func (o *ComposeService) GetPorts() []string`

GetPorts returns the Ports field if non-nil, zero value otherwise.

### GetPortsOk

`func (o *ComposeService) GetPortsOk() (*[]string, bool)`

GetPortsOk returns a tuple with the Ports field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPorts

`func (o *ComposeService) SetPorts(v []string)`

SetPorts sets Ports field to given value.

### HasPorts

`func (o *ComposeService) HasPorts() bool`

HasPorts returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


