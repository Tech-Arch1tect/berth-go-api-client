# AuthLoginData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccessToken** | **string** |  | 
**ExpiresIn** | **int32** |  | 
**RefreshExpiresIn** | **int32** |  | 
**RefreshToken** | **string** |  | 
**TokenType** | **string** |  | 
**User** | [**UserInfo**](UserInfo.md) |  | 

## Methods

### NewAuthLoginData

`func NewAuthLoginData(accessToken string, expiresIn int32, refreshExpiresIn int32, refreshToken string, tokenType string, user UserInfo, ) *AuthLoginData`

NewAuthLoginData instantiates a new AuthLoginData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAuthLoginDataWithDefaults

`func NewAuthLoginDataWithDefaults() *AuthLoginData`

NewAuthLoginDataWithDefaults instantiates a new AuthLoginData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccessToken

`func (o *AuthLoginData) GetAccessToken() string`

GetAccessToken returns the AccessToken field if non-nil, zero value otherwise.

### GetAccessTokenOk

`func (o *AuthLoginData) GetAccessTokenOk() (*string, bool)`

GetAccessTokenOk returns a tuple with the AccessToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessToken

`func (o *AuthLoginData) SetAccessToken(v string)`

SetAccessToken sets AccessToken field to given value.


### GetExpiresIn

`func (o *AuthLoginData) GetExpiresIn() int32`

GetExpiresIn returns the ExpiresIn field if non-nil, zero value otherwise.

### GetExpiresInOk

`func (o *AuthLoginData) GetExpiresInOk() (*int32, bool)`

GetExpiresInOk returns a tuple with the ExpiresIn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresIn

`func (o *AuthLoginData) SetExpiresIn(v int32)`

SetExpiresIn sets ExpiresIn field to given value.


### GetRefreshExpiresIn

`func (o *AuthLoginData) GetRefreshExpiresIn() int32`

GetRefreshExpiresIn returns the RefreshExpiresIn field if non-nil, zero value otherwise.

### GetRefreshExpiresInOk

`func (o *AuthLoginData) GetRefreshExpiresInOk() (*int32, bool)`

GetRefreshExpiresInOk returns a tuple with the RefreshExpiresIn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRefreshExpiresIn

`func (o *AuthLoginData) SetRefreshExpiresIn(v int32)`

SetRefreshExpiresIn sets RefreshExpiresIn field to given value.


### GetRefreshToken

`func (o *AuthLoginData) GetRefreshToken() string`

GetRefreshToken returns the RefreshToken field if non-nil, zero value otherwise.

### GetRefreshTokenOk

`func (o *AuthLoginData) GetRefreshTokenOk() (*string, bool)`

GetRefreshTokenOk returns a tuple with the RefreshToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRefreshToken

`func (o *AuthLoginData) SetRefreshToken(v string)`

SetRefreshToken sets RefreshToken field to given value.


### GetTokenType

`func (o *AuthLoginData) GetTokenType() string`

GetTokenType returns the TokenType field if non-nil, zero value otherwise.

### GetTokenTypeOk

`func (o *AuthLoginData) GetTokenTypeOk() (*string, bool)`

GetTokenTypeOk returns a tuple with the TokenType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokenType

`func (o *AuthLoginData) SetTokenType(v string)`

SetTokenType sets TokenType field to given value.


### GetUser

`func (o *AuthLoginData) GetUser() UserInfo`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *AuthLoginData) GetUserOk() (*UserInfo, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *AuthLoginData) SetUser(v UserInfo)`

SetUser sets User field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


