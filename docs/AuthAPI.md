# \AuthAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApiV1AuthLoginPost**](AuthAPI.md#ApiV1AuthLoginPost) | **Post** /api/v1/auth/login | Login with username and password
[**ApiV1AuthLogoutPost**](AuthAPI.md#ApiV1AuthLogoutPost) | **Post** /api/v1/auth/logout | Logout and revoke tokens
[**ApiV1AuthRefreshPost**](AuthAPI.md#ApiV1AuthRefreshPost) | **Post** /api/v1/auth/refresh | Refresh access token
[**ApiV1AuthTotpVerifyPost**](AuthAPI.md#ApiV1AuthTotpVerifyPost) | **Post** /api/v1/auth/totp/verify | Verify TOTP code to complete login



## ApiV1AuthLoginPost

> AuthTOTPRequiredResponse ApiV1AuthLoginPost(ctx).AuthLoginRequest(authLoginRequest).Execute()

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
	// response from `ApiV1AuthLoginPost`: AuthTOTPRequiredResponse
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

[**AuthTOTPRequiredResponse**](AuthTOTPRequiredResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1AuthLogoutPost

> AuthLogoutResponse ApiV1AuthLogoutPost(ctx).AuthLogoutRequest(authLogoutRequest).Execute()

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
	authLogoutRequest := *openapiclient.NewAuthLogoutRequest("RefreshToken_example") // AuthLogoutRequest | Refresh token to revoke

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuthAPI.ApiV1AuthLogoutPost(context.Background()).AuthLogoutRequest(authLogoutRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthAPI.ApiV1AuthLogoutPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AuthLogoutPost`: AuthLogoutResponse
	fmt.Fprintf(os.Stdout, "Response from `AuthAPI.ApiV1AuthLogoutPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AuthLogoutPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **authLogoutRequest** | [**AuthLogoutRequest**](AuthLogoutRequest.md) | Refresh token to revoke | 

### Return type

[**AuthLogoutResponse**](AuthLogoutResponse.md)

### Authorization

[session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1AuthRefreshPost

> AuthRefreshResponse ApiV1AuthRefreshPost(ctx).AuthRefreshRequest(authRefreshRequest).Execute()

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
	authRefreshRequest := *openapiclient.NewAuthRefreshRequest("RefreshToken_example") // AuthRefreshRequest | Refresh token

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuthAPI.ApiV1AuthRefreshPost(context.Background()).AuthRefreshRequest(authRefreshRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthAPI.ApiV1AuthRefreshPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AuthRefreshPost`: AuthRefreshResponse
	fmt.Fprintf(os.Stdout, "Response from `AuthAPI.ApiV1AuthRefreshPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AuthRefreshPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **authRefreshRequest** | [**AuthRefreshRequest**](AuthRefreshRequest.md) | Refresh token | 

### Return type

[**AuthRefreshResponse**](AuthRefreshResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1AuthTotpVerifyPost

> AuthLoginResponse ApiV1AuthTotpVerifyPost(ctx).AuthTOTPVerifyRequest(authTOTPVerifyRequest).Execute()

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
	// response from `ApiV1AuthTotpVerifyPost`: AuthLoginResponse
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

[**AuthLoginResponse**](AuthLoginResponse.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

