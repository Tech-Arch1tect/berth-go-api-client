# \SessionsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApiV1SessionsGet**](SessionsAPI.md#ApiV1SessionsGet) | **Get** /api/v1/sessions | List user sessions
[**ApiV1SessionsRevokeAllOthersPost**](SessionsAPI.md#ApiV1SessionsRevokeAllOthersPost) | **Post** /api/v1/sessions/revoke-all-others | Revoke all other sessions
[**ApiV1SessionsRevokePost**](SessionsAPI.md#ApiV1SessionsRevokePost) | **Post** /api/v1/sessions/revoke | Revoke a session



## ApiV1SessionsGet

> ResponseGetSessionsData ApiV1SessionsGet(ctx).Execute()

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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SessionsAPI.ApiV1SessionsGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SessionsAPI.ApiV1SessionsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1SessionsGet`: ResponseGetSessionsData
	fmt.Fprintf(os.Stdout, "Response from `SessionsAPI.ApiV1SessionsGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1SessionsGetRequest struct via the builder pattern


### Return type

[**ResponseGetSessionsData**](ResponseGetSessionsData.md)

### Authorization

[session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1SessionsRevokeAllOthersPost

> ResponseSessionMessageData ApiV1SessionsRevokeAllOthersPost(ctx).Body(body).Execute()

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
	body := map[string]interface{}{ ... } // map[string]interface{} | No body required

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SessionsAPI.ApiV1SessionsRevokeAllOthersPost(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SessionsAPI.ApiV1SessionsRevokeAllOthersPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1SessionsRevokeAllOthersPost`: ResponseSessionMessageData
	fmt.Fprintf(os.Stdout, "Response from `SessionsAPI.ApiV1SessionsRevokeAllOthersPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiV1SessionsRevokeAllOthersPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | **map[string]interface{}** | No body required | 

### Return type

[**ResponseSessionMessageData**](ResponseSessionMessageData.md)

### Authorization

[session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1SessionsRevokePost

> ResponseSessionMessageData ApiV1SessionsRevokePost(ctx).RevokeSessionRequest(revokeSessionRequest).Execute()

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
	// response from `ApiV1SessionsRevokePost`: ResponseSessionMessageData
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

[**ResponseSessionMessageData**](ResponseSessionMessageData.md)

### Authorization

[session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

