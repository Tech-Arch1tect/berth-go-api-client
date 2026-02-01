# ListCredentialsData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Credentials** | [**[]RegistryCredentialInfo**](RegistryCredentialInfo.md) |  | 

## Methods

### NewListCredentialsData

`func NewListCredentialsData(credentials []RegistryCredentialInfo, ) *ListCredentialsData`

NewListCredentialsData instantiates a new ListCredentialsData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListCredentialsDataWithDefaults

`func NewListCredentialsDataWithDefaults() *ListCredentialsData`

NewListCredentialsDataWithDefaults instantiates a new ListCredentialsData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCredentials

`func (o *ListCredentialsData) GetCredentials() []RegistryCredentialInfo`

GetCredentials returns the Credentials field if non-nil, zero value otherwise.

### GetCredentialsOk

`func (o *ListCredentialsData) GetCredentialsOk() (*[]RegistryCredentialInfo, bool)`

GetCredentialsOk returns a tuple with the Credentials field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCredentials

`func (o *ListCredentialsData) SetCredentials(v []RegistryCredentialInfo)`

SetCredentials sets Credentials field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


