# \SessionsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApiV1SessionsPost**](SessionsAPI.md#ApiV1SessionsPost) | **Post** /api/v1/sessions | List user sessions
[**ApiV1SessionsRevokeAllOthersPost**](SessionsAPI.md#ApiV1SessionsRevokeAllOthersPost) | **Post** /api/v1/sessions/revoke-all-others | Revoke all other sessions
[**ApiV1SessionsRevokePost**](SessionsAPI.md#ApiV1SessionsRevokePost) | **Post** /api/v1/sessions/revoke | Revoke a session



## ApiV1SessionsPost

> GetSessionsResponse ApiV1SessionsPost(ctx).GetSessionsRequest(getSessionsRequest).Execute()

List user sessions



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
	getSessionsRequest := *openapiclient.NewGetSessionsRequest("RefreshToken_example") // GetSessionsRequest | Refresh token to identify current session

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SessionsAPI.ApiV1SessionsPost(context.Background()).GetSessionsRequest(getSessionsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SessionsAPI.ApiV1SessionsPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1SessionsPost`: GetSessionsResponse
	fmt.Fprintf(os.Stdout, "Response from `SessionsAPI.ApiV1SessionsPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiV1SessionsPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **getSessionsRequest** | [**GetSessionsRequest**](GetSessionsRequest.md) | Refresh token to identify current session | 

### Return type

[**GetSessionsResponse**](GetSessionsResponse.md)

### Authorization

[session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1SessionsRevokeAllOthersPost

> SessionMessageResponse ApiV1SessionsRevokeAllOthersPost(ctx).RevokeAllOtherSessionsRequest(revokeAllOtherSessionsRequest).Execute()

Revoke all other sessions



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
	revokeAllOtherSessionsRequest := *openapiclient.NewRevokeAllOtherSessionsRequest() // RevokeAllOtherSessionsRequest | Refresh token (required for JWT auth, not needed for session auth)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SessionsAPI.ApiV1SessionsRevokeAllOthersPost(context.Background()).RevokeAllOtherSessionsRequest(revokeAllOtherSessionsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SessionsAPI.ApiV1SessionsRevokeAllOthersPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1SessionsRevokeAllOthersPost`: SessionMessageResponse
	fmt.Fprintf(os.Stdout, "Response from `SessionsAPI.ApiV1SessionsRevokeAllOthersPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiV1SessionsRevokeAllOthersPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **revokeAllOtherSessionsRequest** | [**RevokeAllOtherSessionsRequest**](RevokeAllOtherSessionsRequest.md) | Refresh token (required for JWT auth, not needed for session auth) | 

### Return type

[**SessionMessageResponse**](SessionMessageResponse.md)

### Authorization

[session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1SessionsRevokePost

> SessionMessageResponse ApiV1SessionsRevokePost(ctx).RevokeSessionRequest(revokeSessionRequest).Execute()

Revoke a session



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
	revokeSessionRequest := *openapiclient.NewRevokeSessionRequest(int32(123)) // RevokeSessionRequest | Session to revoke

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SessionsAPI.ApiV1SessionsRevokePost(context.Background()).RevokeSessionRequest(revokeSessionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SessionsAPI.ApiV1SessionsRevokePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1SessionsRevokePost`: SessionMessageResponse
	fmt.Fprintf(os.Stdout, "Response from `SessionsAPI.ApiV1SessionsRevokePost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiV1SessionsRevokePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **revokeSessionRequest** | [**RevokeSessionRequest**](RevokeSessionRequest.md) | Session to revoke | 

### Return type

[**SessionMessageResponse**](SessionMessageResponse.md)

### Authorization

[session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

