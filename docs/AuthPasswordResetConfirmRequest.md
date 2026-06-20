# AuthPasswordResetConfirmRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Password** | **string** |  | 
**PasswordConfirmation** | **string** |  | 
**Token** | **string** |  | 

## Methods

### NewAuthPasswordResetConfirmRequest

`func NewAuthPasswordResetConfirmRequest(password string, passwordConfirmation string, token string, ) *AuthPasswordResetConfirmRequest`

NewAuthPasswordResetConfirmRequest instantiates a new AuthPasswordResetConfirmRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAuthPasswordResetConfirmRequestWithDefaults

`func NewAuthPasswordResetConfirmRequestWithDefaults() *AuthPasswordResetConfirmRequest`

NewAuthPasswordResetConfirmRequestWithDefaults instantiates a new AuthPasswordResetConfirmRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPassword

`func (o *AuthPasswordResetConfirmRequest) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *AuthPasswordResetConfirmRequest) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *AuthPasswordResetConfirmRequest) SetPassword(v string)`

SetPassword sets Password field to given value.


### GetPasswordConfirmation

`func (o *AuthPasswordResetConfirmRequest) GetPasswordConfirmation() string`

GetPasswordConfirmation returns the PasswordConfirmation field if non-nil, zero value otherwise.

### GetPasswordConfirmationOk

`func (o *AuthPasswordResetConfirmRequest) GetPasswordConfirmationOk() (*string, bool)`

GetPasswordConfirmationOk returns a tuple with the PasswordConfirmation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPasswordConfirmation

`func (o *AuthPasswordResetConfirmRequest) SetPasswordConfirmation(v string)`

SetPasswordConfirmation sets PasswordConfirmation field to given value.


### GetToken

`func (o *AuthPasswordResetConfirmRequest) GetToken() string`

GetToken returns the Token field if non-nil, zero value otherwise.

### GetTokenOk

`func (o *AuthPasswordResetConfirmRequest) GetTokenOk() (*string, bool)`

GetTokenOk returns a tuple with the Token field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToken

`func (o *AuthPasswordResetConfirmRequest) SetToken(v string)`

SetToken sets Token field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


