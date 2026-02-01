# TOTPSetupData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**QrCodeUri** | **string** |  | 
**Secret** | **string** |  | 

## Methods

### NewTOTPSetupData

`func NewTOTPSetupData(qrCodeUri string, secret string, ) *TOTPSetupData`

NewTOTPSetupData instantiates a new TOTPSetupData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTOTPSetupDataWithDefaults

`func NewTOTPSetupDataWithDefaults() *TOTPSetupData`

NewTOTPSetupDataWithDefaults instantiates a new TOTPSetupData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetQrCodeUri

`func (o *TOTPSetupData) GetQrCodeUri() string`

GetQrCodeUri returns the QrCodeUri field if non-nil, zero value otherwise.

### GetQrCodeUriOk

`func (o *TOTPSetupData) GetQrCodeUriOk() (*string, bool)`

GetQrCodeUriOk returns a tuple with the QrCodeUri field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQrCodeUri

`func (o *TOTPSetupData) SetQrCodeUri(v string)`

SetQrCodeUri sets QrCodeUri field to given value.


### GetSecret

`func (o *TOTPSetupData) GetSecret() string`

GetSecret returns the Secret field if non-nil, zero value otherwise.

### GetSecretOk

`func (o *TOTPSetupData) GetSecretOk() (*string, bool)`

GetSecretOk returns a tuple with the Secret field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecret

`func (o *TOTPSetupData) SetSecret(v string)`

SetSecret sets Secret field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


