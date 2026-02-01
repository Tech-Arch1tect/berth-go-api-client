# AuthRefreshData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccessToken** | **string** |  | 
**ExpiresIn** | **int32** |  | 
**RefreshExpiresIn** | **int32** |  | 
**RefreshToken** | **string** |  | 
**TokenType** | **string** |  | 

## Methods

### NewAuthRefreshData

`func NewAuthRefreshData(accessToken string, expiresIn int32, refreshExpiresIn int32, refreshToken string, tokenType string, ) *AuthRefreshData`

NewAuthRefreshData instantiates a new AuthRefreshData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAuthRefreshDataWithDefaults

`func NewAuthRefreshDataWithDefaults() *AuthRefreshData`

NewAuthRefreshDataWithDefaults instantiates a new AuthRefreshData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccessToken

`func (o *AuthRefreshData) GetAccessToken() string`

GetAccessToken returns the AccessToken field if non-nil, zero value otherwise.

### GetAccessTokenOk

`func (o *AuthRefreshData) GetAccessTokenOk() (*string, bool)`

GetAccessTokenOk returns a tuple with the AccessToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessToken

`func (o *AuthRefreshData) SetAccessToken(v string)`

SetAccessToken sets AccessToken field to given value.


### GetExpiresIn

`func (o *AuthRefreshData) GetExpiresIn() int32`

GetExpiresIn returns the ExpiresIn field if non-nil, zero value otherwise.

### GetExpiresInOk

`func (o *AuthRefreshData) GetExpiresInOk() (*int32, bool)`

GetExpiresInOk returns a tuple with the ExpiresIn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresIn

`func (o *AuthRefreshData) SetExpiresIn(v int32)`

SetExpiresIn sets ExpiresIn field to given value.


### GetRefreshExpiresIn

`func (o *AuthRefreshData) GetRefreshExpiresIn() int32`

GetRefreshExpiresIn returns the RefreshExpiresIn field if non-nil, zero value otherwise.

### GetRefreshExpiresInOk

`func (o *AuthRefreshData) GetRefreshExpiresInOk() (*int32, bool)`

GetRefreshExpiresInOk returns a tuple with the RefreshExpiresIn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRefreshExpiresIn

`func (o *AuthRefreshData) SetRefreshExpiresIn(v int32)`

SetRefreshExpiresIn sets RefreshExpiresIn field to given value.


### GetRefreshToken

`func (o *AuthRefreshData) GetRefreshToken() string`

GetRefreshToken returns the RefreshToken field if non-nil, zero value otherwise.

### GetRefreshTokenOk

`func (o *AuthRefreshData) GetRefreshTokenOk() (*string, bool)`

GetRefreshTokenOk returns a tuple with the RefreshToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRefreshToken

`func (o *AuthRefreshData) SetRefreshToken(v string)`

SetRefreshToken sets RefreshToken field to given value.


### GetTokenType

`func (o *AuthRefreshData) GetTokenType() string`

GetTokenType returns the TokenType field if non-nil, zero value otherwise.

### GetTokenTypeOk

`func (o *AuthRefreshData) GetTokenTypeOk() (*string, bool)`

GetTokenTypeOk returns a tuple with the TokenType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokenType

`func (o *AuthRefreshData) SetTokenType(v string)`

SetTokenType sets TokenType field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


