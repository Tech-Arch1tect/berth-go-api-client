# \AuthAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApiV1AuthLoginPost**](AuthAPI.md#ApiV1AuthLoginPost) | **Post** /api/v1/auth/login | Login with username and password
[**ApiV1AuthLogoutPost**](AuthAPI.md#ApiV1AuthLogoutPost) | **Post** /api/v1/auth/logout | Logout and revoke tokens
[**ApiV1AuthPasswordResetConfirmPost**](AuthAPI.md#ApiV1AuthPasswordResetConfirmPost) | **Post** /api/v1/auth/password-reset/confirm | Complete a password reset
[**ApiV1AuthPasswordResetPost**](AuthAPI.md#ApiV1AuthPasswordResetPost) | **Post** /api/v1/auth/password-reset | Request a password reset email
[**ApiV1AuthRefreshPost**](AuthAPI.md#ApiV1AuthRefreshPost) | **Post** /api/v1/auth/refresh | Refresh access token
[**ApiV1AuthResendVerificationPost**](AuthAPI.md#ApiV1AuthResendVerificationPost) | **Post** /api/v1/auth/resend-verification | Request a new email verification link
[**ApiV1AuthTotpVerifyPost**](AuthAPI.md#ApiV1AuthTotpVerifyPost) | **Post** /api/v1/auth/totp/verify | Verify TOTP code to complete login
[**ApiV1AuthVerifyEmailPost**](AuthAPI.md#ApiV1AuthVerifyEmailPost) | **Post** /api/v1/auth/verify-email | Verify an email address



## ApiV1AuthLoginPost

> ApiV1AuthLoginPost200Response ApiV1AuthLoginPost(ctx).AuthLoginRequest(authLoginRequest).Execute()

Login with username and password



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/tech-arch1tect/berth-go-api-client"
)

func main() {
	authLoginRequest := *openapiclient.NewAuthLoginRequest("Password_example", "Username_example") // AuthLoginRequest | Login credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuthAPI.ApiV1AuthLoginPost(context.Background()).AuthLoginRequest(authLoginRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthAPI.ApiV1AuthLoginPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AuthLoginPost`: ApiV1AuthLoginPost200Response
	fmt.Fprintf(os.Stdout, "Response from `AuthAPI.ApiV1AuthLoginPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AuthLoginPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **authLoginRequest** | [**AuthLoginRequest**](AuthLoginRequest.md) | Login credentials | 

### Return type

[**ApiV1AuthLoginPost200Response**](ApiV1AuthLoginPost200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1AuthLogoutPost

> ResponseAuthLogoutData ApiV1AuthLogoutPost(ctx).AuthLogoutRequest(authLogoutRequest).Execute()

Logout and revoke tokens



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/tech-arch1tect/berth-go-api-client"
)

func main() {
	authLogoutRequest := *openapiclient.NewAuthLogoutRequest() // AuthLogoutRequest | Refresh token to revoke (optional - may be supplied via berth_refresh cookie instead)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuthAPI.ApiV1AuthLogoutPost(context.Background()).AuthLogoutRequest(authLogoutRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthAPI.ApiV1AuthLogoutPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AuthLogoutPost`: ResponseAuthLogoutData
	fmt.Fprintf(os.Stdout, "Response from `AuthAPI.ApiV1AuthLogoutPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AuthLogoutPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **authLogoutRequest** | [**AuthLogoutRequest**](AuthLogoutRequest.md) | Refresh token to revoke (optional - may be supplied via berth_refresh cookie instead) | 

### Return type

[**ResponseAuthLogoutData**](ResponseAuthLogoutData.md)

### Authorization

[session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1AuthPasswordResetConfirmPost

> ResponseAuthMessageData ApiV1AuthPasswordResetConfirmPost(ctx).AuthPasswordResetConfirmRequest(authPasswordResetConfirmRequest).Execute()

Complete a password reset



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/tech-arch1tect/berth-go-api-client"
)

func main() {
	authPasswordResetConfirmRequest := *openapiclient.NewAuthPasswordResetConfirmRequest("Password_example", "PasswordConfirmation_example", "Token_example") // AuthPasswordResetConfirmRequest | Reset token plus new password and confirmation

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuthAPI.ApiV1AuthPasswordResetConfirmPost(context.Background()).AuthPasswordResetConfirmRequest(authPasswordResetConfirmRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthAPI.ApiV1AuthPasswordResetConfirmPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AuthPasswordResetConfirmPost`: ResponseAuthMessageData
	fmt.Fprintf(os.Stdout, "Response from `AuthAPI.ApiV1AuthPasswordResetConfirmPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AuthPasswordResetConfirmPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **authPasswordResetConfirmRequest** | [**AuthPasswordResetConfirmRequest**](AuthPasswordResetConfirmRequest.md) | Reset token plus new password and confirmation | 

### Return type

[**ResponseAuthMessageData**](ResponseAuthMessageData.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1AuthPasswordResetPost

> ResponseAuthMessageData ApiV1AuthPasswordResetPost(ctx).AuthPasswordResetRequest(authPasswordResetRequest).Execute()

Request a password reset email



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/tech-arch1tect/berth-go-api-client"
)

func main() {
	authPasswordResetRequest := *openapiclient.NewAuthPasswordResetRequest("Email_example") // AuthPasswordResetRequest | Email address to send the reset link to

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuthAPI.ApiV1AuthPasswordResetPost(context.Background()).AuthPasswordResetRequest(authPasswordResetRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthAPI.ApiV1AuthPasswordResetPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AuthPasswordResetPost`: ResponseAuthMessageData
	fmt.Fprintf(os.Stdout, "Response from `AuthAPI.ApiV1AuthPasswordResetPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AuthPasswordResetPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **authPasswordResetRequest** | [**AuthPasswordResetRequest**](AuthPasswordResetRequest.md) | Email address to send the reset link to | 

### Return type

[**ResponseAuthMessageData**](ResponseAuthMessageData.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1AuthRefreshPost

> ResponseAuthRefreshData ApiV1AuthRefreshPost(ctx).AuthRefreshRequest(authRefreshRequest).Execute()

Refresh access token



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/tech-arch1tect/berth-go-api-client"
)

func main() {
	authRefreshRequest := *openapiclient.NewAuthRefreshRequest() // AuthRefreshRequest | Refresh token (optional - may be supplied via berth_refresh cookie instead)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuthAPI.ApiV1AuthRefreshPost(context.Background()).AuthRefreshRequest(authRefreshRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthAPI.ApiV1AuthRefreshPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AuthRefreshPost`: ResponseAuthRefreshData
	fmt.Fprintf(os.Stdout, "Response from `AuthAPI.ApiV1AuthRefreshPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AuthRefreshPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **authRefreshRequest** | [**AuthRefreshRequest**](AuthRefreshRequest.md) | Refresh token (optional - may be supplied via berth_refresh cookie instead) | 

### Return type

[**ResponseAuthRefreshData**](ResponseAuthRefreshData.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1AuthResendVerificationPost

> ResponseAuthMessageData ApiV1AuthResendVerificationPost(ctx).AuthResendVerificationRequest(authResendVerificationRequest).Execute()

Request a new email verification link



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/tech-arch1tect/berth-go-api-client"
)

func main() {
	authResendVerificationRequest := *openapiclient.NewAuthResendVerificationRequest("Email_example") // AuthResendVerificationRequest | Email address to send the verification link to

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuthAPI.ApiV1AuthResendVerificationPost(context.Background()).AuthResendVerificationRequest(authResendVerificationRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthAPI.ApiV1AuthResendVerificationPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AuthResendVerificationPost`: ResponseAuthMessageData
	fmt.Fprintf(os.Stdout, "Response from `AuthAPI.ApiV1AuthResendVerificationPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AuthResendVerificationPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **authResendVerificationRequest** | [**AuthResendVerificationRequest**](AuthResendVerificationRequest.md) | Email address to send the verification link to | 

### Return type

[**ResponseAuthMessageData**](ResponseAuthMessageData.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1AuthTotpVerifyPost

> ResponseAuthLoginData ApiV1AuthTotpVerifyPost(ctx).AuthTOTPVerifyRequest(authTOTPVerifyRequest).Execute()

Verify TOTP code to complete login



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/tech-arch1tect/berth-go-api-client"
)

func main() {
	authTOTPVerifyRequest := *openapiclient.NewAuthTOTPVerifyRequest("Code_example") // AuthTOTPVerifyRequest | TOTP verification code

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuthAPI.ApiV1AuthTotpVerifyPost(context.Background()).AuthTOTPVerifyRequest(authTOTPVerifyRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthAPI.ApiV1AuthTotpVerifyPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AuthTotpVerifyPost`: ResponseAuthLoginData
	fmt.Fprintf(os.Stdout, "Response from `AuthAPI.ApiV1AuthTotpVerifyPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AuthTotpVerifyPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **authTOTPVerifyRequest** | [**AuthTOTPVerifyRequest**](AuthTOTPVerifyRequest.md) | TOTP verification code | 

### Return type

[**ResponseAuthLoginData**](ResponseAuthLoginData.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1AuthVerifyEmailPost

> ResponseAuthMessageData ApiV1AuthVerifyEmailPost(ctx).AuthVerifyEmailRequest(authVerifyEmailRequest).Execute()

Verify an email address



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/tech-arch1tect/berth-go-api-client"
)

func main() {
	authVerifyEmailRequest := *openapiclient.NewAuthVerifyEmailRequest("Token_example") // AuthVerifyEmailRequest | Email verification token

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuthAPI.ApiV1AuthVerifyEmailPost(context.Background()).AuthVerifyEmailRequest(authVerifyEmailRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthAPI.ApiV1AuthVerifyEmailPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AuthVerifyEmailPost`: ResponseAuthMessageData
	fmt.Fprintf(os.Stdout, "Response from `AuthAPI.ApiV1AuthVerifyEmailPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AuthVerifyEmailPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **authVerifyEmailRequest** | [**AuthVerifyEmailRequest**](AuthVerifyEmailRequest.md) | Email verification token | 

### Return type

[**ResponseAuthMessageData**](ResponseAuthMessageData.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

