# AuthTOTPRequiredData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | **string** |  | 
**TemporaryToken** | **string** |  | 
**TotpRequired** | **bool** |  | 

## Methods

### NewAuthTOTPRequiredData

`func NewAuthTOTPRequiredData(message string, temporaryToken string, totpRequired bool, ) *AuthTOTPRequiredData`

NewAuthTOTPRequiredData instantiates a new AuthTOTPRequiredData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAuthTOTPRequiredDataWithDefaults

`func NewAuthTOTPRequiredDataWithDefaults() *AuthTOTPRequiredData`

NewAuthTOTPRequiredDataWithDefaults instantiates a new AuthTOTPRequiredData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *AuthTOTPRequiredData) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *AuthTOTPRequiredData) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *AuthTOTPRequiredData) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetTemporaryToken

`func (o *AuthTOTPRequiredData) GetTemporaryToken() string`

GetTemporaryToken returns the TemporaryToken field if non-nil, zero value otherwise.

### GetTemporaryTokenOk

`func (o *AuthTOTPRequiredData) GetTemporaryTokenOk() (*string, bool)`

GetTemporaryTokenOk returns a tuple with the TemporaryToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemporaryToken

`func (o *AuthTOTPRequiredData) SetTemporaryToken(v string)`

SetTemporaryToken sets TemporaryToken field to given value.


### GetTotpRequired

`func (o *AuthTOTPRequiredData) GetTotpRequired() bool`

GetTotpRequired returns the TotpRequired field if non-nil, zero value otherwise.

### GetTotpRequiredOk

`func (o *AuthTOTPRequiredData) GetTotpRequiredOk() (*bool, bool)`

GetTotpRequiredOk returns a tuple with the TotpRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotpRequired

`func (o *AuthTOTPRequiredData) SetTotpRequired(v bool)`

SetTotpRequired sets TotpRequired field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


