# \TotpAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApiV1TotpDisablePost**](TotpAPI.md#ApiV1TotpDisablePost) | **Post** /api/v1/totp/disable | Disable TOTP
[**ApiV1TotpEnablePost**](TotpAPI.md#ApiV1TotpEnablePost) | **Post** /api/v1/totp/enable | Enable TOTP
[**ApiV1TotpSetupGet**](TotpAPI.md#ApiV1TotpSetupGet) | **Get** /api/v1/totp/setup | Get TOTP setup information
[**ApiV1TotpStatusGet**](TotpAPI.md#ApiV1TotpStatusGet) | **Get** /api/v1/totp/status | Get TOTP status



## ApiV1TotpDisablePost

> TOTPMessageResponse ApiV1TotpDisablePost(ctx).TOTPDisableRequest(tOTPDisableRequest).Execute()

Disable TOTP



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
	tOTPDisableRequest := *openapiclient.NewTOTPDisableRequest("Code_example", "Password_example") // TOTPDisableRequest | TOTP code and password

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TotpAPI.ApiV1TotpDisablePost(context.Background()).TOTPDisableRequest(tOTPDisableRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TotpAPI.ApiV1TotpDisablePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1TotpDisablePost`: TOTPMessageResponse
	fmt.Fprintf(os.Stdout, "Response from `TotpAPI.ApiV1TotpDisablePost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiV1TotpDisablePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **tOTPDisableRequest** | [**TOTPDisableRequest**](TOTPDisableRequest.md) | TOTP code and password | 

### Return type

[**TOTPMessageResponse**](TOTPMessageResponse.md)

### Authorization

[session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1TotpEnablePost

> TOTPMessageResponse ApiV1TotpEnablePost(ctx).TOTPEnableRequest(tOTPEnableRequest).Execute()

Enable TOTP



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
	tOTPEnableRequest := *openapiclient.NewTOTPEnableRequest("Code_example") // TOTPEnableRequest | TOTP verification code

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TotpAPI.ApiV1TotpEnablePost(context.Background()).TOTPEnableRequest(tOTPEnableRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TotpAPI.ApiV1TotpEnablePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1TotpEnablePost`: TOTPMessageResponse
	fmt.Fprintf(os.Stdout, "Response from `TotpAPI.ApiV1TotpEnablePost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiV1TotpEnablePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **tOTPEnableRequest** | [**TOTPEnableRequest**](TOTPEnableRequest.md) | TOTP verification code | 

### Return type

[**TOTPMessageResponse**](TOTPMessageResponse.md)

### Authorization

[session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1TotpSetupGet

> TOTPSetupResponse ApiV1TotpSetupGet(ctx).Execute()

Get TOTP setup information



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TotpAPI.ApiV1TotpSetupGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TotpAPI.ApiV1TotpSetupGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1TotpSetupGet`: TOTPSetupResponse
	fmt.Fprintf(os.Stdout, "Response from `TotpAPI.ApiV1TotpSetupGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1TotpSetupGetRequest struct via the builder pattern


### Return type

[**TOTPSetupResponse**](TOTPSetupResponse.md)

### Authorization

[session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1TotpStatusGet

> TOTPStatusResponse ApiV1TotpStatusGet(ctx).Execute()

Get TOTP status



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TotpAPI.ApiV1TotpStatusGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TotpAPI.ApiV1TotpStatusGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1TotpStatusGet`: TOTPStatusResponse
	fmt.Fprintf(os.Stdout, "Response from `TotpAPI.ApiV1TotpStatusGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1TotpStatusGetRequest struct via the builder pattern


### Return type

[**TOTPStatusResponse**](TOTPStatusResponse.md)

### Authorization

[session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

