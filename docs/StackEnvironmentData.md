# StackEnvironmentData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Services** | [**map[string][]ServiceEnvironment**](array.md) |  | 

## Methods

### NewStackEnvironmentData

`func NewStackEnvironmentData(services map[string][]ServiceEnvironment, ) *StackEnvironmentData`

NewStackEnvironmentData instantiates a new StackEnvironmentData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStackEnvironmentDataWithDefaults

`func NewStackEnvironmentDataWithDefaults() *StackEnvironmentData`

NewStackEnvironmentDataWithDefaults instantiates a new StackEnvironmentData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetServices

`func (o *StackEnvironmentData) GetServices() map[string][]ServiceEnvironment`

GetServices returns the Services field if non-nil, zero value otherwise.

### GetServicesOk

`func (o *StackEnvironmentData) GetServicesOk() (*map[string][]ServiceEnvironment, bool)`

GetServicesOk returns a tuple with the Services field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServices

`func (o *StackEnvironmentData) SetServices(v map[string][]ServiceEnvironment)`

SetServices sets Services field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


