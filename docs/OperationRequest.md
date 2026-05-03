# OperationRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Command** | **string** |  | 
**Options** | **[]string** |  | 
**RegistryCredentials** | Pointer to [**[]RegistryCredential**](RegistryCredential.md) |  | [optional] 
**Services** | **[]string** |  | 

## Methods

### NewOperationRequest

`func NewOperationRequest(command string, options []string, services []string, ) *OperationRequest`

NewOperationRequest instantiates a new OperationRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperationRequestWithDefaults

`func NewOperationRequestWithDefaults() *OperationRequest`

NewOperationRequestWithDefaults instantiates a new OperationRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCommand

`func (o *OperationRequest) GetCommand() string`

GetCommand returns the Command field if non-nil, zero value otherwise.

### GetCommandOk

`func (o *OperationRequest) GetCommandOk() (*string, bool)`

GetCommandOk returns a tuple with the Command field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommand

`func (o *OperationRequest) SetCommand(v string)`

SetCommand sets Command field to given value.


### GetOptions

`func (o *OperationRequest) GetOptions() []string`

GetOptions returns the Options field if non-nil, zero value otherwise.

### GetOptionsOk

`func (o *OperationRequest) GetOptionsOk() (*[]string, bool)`

GetOptionsOk returns a tuple with the Options field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOptions

`func (o *OperationRequest) SetOptions(v []string)`

SetOptions sets Options field to given value.


### GetRegistryCredentials

`func (o *OperationRequest) GetRegistryCredentials() []RegistryCredential`

GetRegistryCredentials returns the RegistryCredentials field if non-nil, zero value otherwise.

### GetRegistryCredentialsOk

`func (o *OperationRequest) GetRegistryCredentialsOk() (*[]RegistryCredential, bool)`

GetRegistryCredentialsOk returns a tuple with the RegistryCredentials field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegistryCredentials

`func (o *OperationRequest) SetRegistryCredentials(v []RegistryCredential)`

SetRegistryCredentials sets RegistryCredentials field to given value.

### HasRegistryCredentials

`func (o *OperationRequest) HasRegistryCredentials() bool`

HasRegistryCredentials returns a boolean if a field has been set.

### GetServices

`func (o *OperationRequest) GetServices() []string`

GetServices returns the Services field if non-nil, zero value otherwise.

### GetServicesOk

`func (o *OperationRequest) GetServicesOk() (*[]string, bool)`

GetServicesOk returns a tuple with the Services field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServices

`func (o *OperationRequest) SetServices(v []string)`

SetServices sets Services field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


