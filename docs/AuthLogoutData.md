# AuthLogoutData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | **string** |  | 
**RevokedTokens** | **[]string** |  | 

## Methods

### NewAuthLogoutData

`func NewAuthLogoutData(message string, revokedTokens []string, ) *AuthLogoutData`

NewAuthLogoutData instantiates a new AuthLogoutData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAuthLogoutDataWithDefaults

`func NewAuthLogoutDataWithDefaults() *AuthLogoutData`

NewAuthLogoutDataWithDefaults instantiates a new AuthLogoutData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *AuthLogoutData) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *AuthLogoutData) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *AuthLogoutData) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetRevokedTokens

`func (o *AuthLogoutData) GetRevokedTokens() []string`

GetRevokedTokens returns the RevokedTokens field if non-nil, zero value otherwise.

### GetRevokedTokensOk

`func (o *AuthLogoutData) GetRevokedTokensOk() (*[]string, bool)`

GetRevokedTokensOk returns a tuple with the RevokedTokens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevokedTokens

`func (o *AuthLogoutData) SetRevokedTokens(v []string)`

SetRevokedTokens sets RevokedTokens field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


