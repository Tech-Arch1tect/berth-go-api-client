# ServerCreateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccessToken** | **string** |  | 
**Description** | **string** |  | 
**Host** | **string** |  | 
**IsActive** | **bool** |  | 
**Name** | **string** |  | 
**Port** | **int32** |  | 
**SkipSslVerification** | **NullableBool** |  | 

## Methods

### NewServerCreateRequest

`func NewServerCreateRequest(accessToken string, description string, host string, isActive bool, name string, port int32, skipSslVerification NullableBool, ) *ServerCreateRequest`

NewServerCreateRequest instantiates a new ServerCreateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewServerCreateRequestWithDefaults

`func NewServerCreateRequestWithDefaults() *ServerCreateRequest`

NewServerCreateRequestWithDefaults instantiates a new ServerCreateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccessToken

`func (o *ServerCreateRequest) GetAccessToken() string`

GetAccessToken returns the AccessToken field if non-nil, zero value otherwise.

### GetAccessTokenOk

`func (o *ServerCreateRequest) GetAccessTokenOk() (*string, bool)`

GetAccessTokenOk returns a tuple with the AccessToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessToken

`func (o *ServerCreateRequest) SetAccessToken(v string)`

SetAccessToken sets AccessToken field to given value.


### GetDescription

`func (o *ServerCreateRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ServerCreateRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ServerCreateRequest) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetHost

`func (o *ServerCreateRequest) GetHost() string`

GetHost returns the Host field if non-nil, zero value otherwise.

### GetHostOk

`func (o *ServerCreateRequest) GetHostOk() (*string, bool)`

GetHostOk returns a tuple with the Host field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHost

`func (o *ServerCreateRequest) SetHost(v string)`

SetHost sets Host field to given value.


### GetIsActive

`func (o *ServerCreateRequest) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *ServerCreateRequest) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *ServerCreateRequest) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.


### GetName

`func (o *ServerCreateRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ServerCreateRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ServerCreateRequest) SetName(v string)`

SetName sets Name field to given value.


### GetPort

`func (o *ServerCreateRequest) GetPort() int32`

GetPort returns the Port field if non-nil, zero value otherwise.

### GetPortOk

`func (o *ServerCreateRequest) GetPortOk() (*int32, bool)`

GetPortOk returns a tuple with the Port field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPort

`func (o *ServerCreateRequest) SetPort(v int32)`

SetPort sets Port field to given value.


### GetSkipSslVerification

`func (o *ServerCreateRequest) GetSkipSslVerification() bool`

GetSkipSslVerification returns the SkipSslVerification field if non-nil, zero value otherwise.

### GetSkipSslVerificationOk

`func (o *ServerCreateRequest) GetSkipSslVerificationOk() (*bool, bool)`

GetSkipSslVerificationOk returns a tuple with the SkipSslVerification field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSkipSslVerification

`func (o *ServerCreateRequest) SetSkipSslVerification(v bool)`

SetSkipSslVerification sets SkipSslVerification field to given value.


### SetSkipSslVerificationNil

`func (o *ServerCreateRequest) SetSkipSslVerificationNil(b bool)`

 SetSkipSslVerificationNil sets the value for SkipSslVerification to be an explicit nil

### UnsetSkipSslVerification
`func (o *ServerCreateRequest) UnsetSkipSslVerification()`

UnsetSkipSslVerification ensures that no value is present for SkipSslVerification, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


