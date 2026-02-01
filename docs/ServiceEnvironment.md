# ServiceEnvironment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ServiceName** | Pointer to **string** |  | [optional] 
**Variables** | [**[]EnvironmentVariable**](EnvironmentVariable.md) |  | 

## Methods

### NewServiceEnvironment

`func NewServiceEnvironment(variables []EnvironmentVariable, ) *ServiceEnvironment`

NewServiceEnvironment instantiates a new ServiceEnvironment object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewServiceEnvironmentWithDefaults

`func NewServiceEnvironmentWithDefaults() *ServiceEnvironment`

NewServiceEnvironmentWithDefaults instantiates a new ServiceEnvironment object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetServiceName

`func (o *ServiceEnvironment) GetServiceName() string`

GetServiceName returns the ServiceName field if non-nil, zero value otherwise.

### GetServiceNameOk

`func (o *ServiceEnvironment) GetServiceNameOk() (*string, bool)`

GetServiceNameOk returns a tuple with the ServiceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceName

`func (o *ServiceEnvironment) SetServiceName(v string)`

SetServiceName sets ServiceName field to given value.

### HasServiceName

`func (o *ServiceEnvironment) HasServiceName() bool`

HasServiceName returns a boolean if a field has been set.

### GetVariables

`func (o *ServiceEnvironment) GetVariables() []EnvironmentVariable`

GetVariables returns the Variables field if non-nil, zero value otherwise.

### GetVariablesOk

`func (o *ServiceEnvironment) GetVariablesOk() (*[]EnvironmentVariable, bool)`

GetVariablesOk returns a tuple with the Variables field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVariables

`func (o *ServiceEnvironment) SetVariables(v []EnvironmentVariable)`

SetVariables sets Variables field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


