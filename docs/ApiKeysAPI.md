# \ApiKeysAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApiV1ApiKeysGet**](ApiKeysAPI.md#ApiV1ApiKeysGet) | **Get** /api/v1/api-keys | List API keys
[**ApiV1ApiKeysIdDelete**](ApiKeysAPI.md#ApiV1ApiKeysIdDelete) | **Delete** /api/v1/api-keys/{id} | Revoke API key
[**ApiV1ApiKeysIdGet**](ApiKeysAPI.md#ApiV1ApiKeysIdGet) | **Get** /api/v1/api-keys/{id} | Get API key
[**ApiV1ApiKeysIdScopesGet**](ApiKeysAPI.md#ApiV1ApiKeysIdScopesGet) | **Get** /api/v1/api-keys/{id}/scopes | List API key scopes
[**ApiV1ApiKeysIdScopesPost**](ApiKeysAPI.md#ApiV1ApiKeysIdScopesPost) | **Post** /api/v1/api-keys/{id}/scopes | Add scope to API key
[**ApiV1ApiKeysIdScopesScopeIdDelete**](ApiKeysAPI.md#ApiV1ApiKeysIdScopesScopeIdDelete) | **Delete** /api/v1/api-keys/{id}/scopes/{scopeId} | Remove scope from API key
[**ApiV1ApiKeysPost**](ApiKeysAPI.md#ApiV1ApiKeysPost) | **Post** /api/v1/api-keys | Create API key



## ApiV1ApiKeysGet

> ListAPIKeysResponse ApiV1ApiKeysGet(ctx).Execute()

List API keys



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
	resp, r, err := apiClient.ApiKeysAPI.ApiV1ApiKeysGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApiKeysAPI.ApiV1ApiKeysGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ApiKeysGet`: ListAPIKeysResponse
	fmt.Fprintf(os.Stdout, "Response from `ApiKeysAPI.ApiV1ApiKeysGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ApiKeysGetRequest struct via the builder pattern


### Return type

[**ListAPIKeysResponse**](ListAPIKeysResponse.md)

### Authorization

[session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ApiKeysIdDelete

> MessageResponse ApiV1ApiKeysIdDelete(ctx, id).Execute()

Revoke API key



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
	id := int32(56) // int32 | API key ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApiKeysAPI.ApiV1ApiKeysIdDelete(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApiKeysAPI.ApiV1ApiKeysIdDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ApiKeysIdDelete`: MessageResponse
	fmt.Fprintf(os.Stdout, "Response from `ApiKeysAPI.ApiV1ApiKeysIdDelete`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | API key ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ApiKeysIdDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**MessageResponse**](MessageResponse.md)

### Authorization

[session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ApiKeysIdGet

> GetAPIKeyResponse ApiV1ApiKeysIdGet(ctx, id).Execute()

Get API key



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
	id := int32(56) // int32 | API key ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApiKeysAPI.ApiV1ApiKeysIdGet(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApiKeysAPI.ApiV1ApiKeysIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ApiKeysIdGet`: GetAPIKeyResponse
	fmt.Fprintf(os.Stdout, "Response from `ApiKeysAPI.ApiV1ApiKeysIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | API key ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ApiKeysIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**GetAPIKeyResponse**](GetAPIKeyResponse.md)

### Authorization

[session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ApiKeysIdScopesGet

> ListScopesResponse ApiV1ApiKeysIdScopesGet(ctx, id).Execute()

List API key scopes



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
	id := int32(56) // int32 | API key ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApiKeysAPI.ApiV1ApiKeysIdScopesGet(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApiKeysAPI.ApiV1ApiKeysIdScopesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ApiKeysIdScopesGet`: ListScopesResponse
	fmt.Fprintf(os.Stdout, "Response from `ApiKeysAPI.ApiV1ApiKeysIdScopesGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | API key ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ApiKeysIdScopesGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ListScopesResponse**](ListScopesResponse.md)

### Authorization

[session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ApiKeysIdScopesPost

> MessageResponse ApiV1ApiKeysIdScopesPost(ctx, id).AddScopeRequest(addScopeRequest).Execute()

Add scope to API key



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
	id := int32(56) // int32 | API key ID
	addScopeRequest := *openapiclient.NewAddScopeRequest("Permission_example", "StackPattern_example") // AddScopeRequest | Scope details

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApiKeysAPI.ApiV1ApiKeysIdScopesPost(context.Background(), id).AddScopeRequest(addScopeRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApiKeysAPI.ApiV1ApiKeysIdScopesPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ApiKeysIdScopesPost`: MessageResponse
	fmt.Fprintf(os.Stdout, "Response from `ApiKeysAPI.ApiV1ApiKeysIdScopesPost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | API key ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ApiKeysIdScopesPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **addScopeRequest** | [**AddScopeRequest**](AddScopeRequest.md) | Scope details | 

### Return type

[**MessageResponse**](MessageResponse.md)

### Authorization

[session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ApiKeysIdScopesScopeIdDelete

> MessageResponse ApiV1ApiKeysIdScopesScopeIdDelete(ctx, id, scopeId).Execute()

Remove scope from API key



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
	id := int32(56) // int32 | API key ID
	scopeId := int32(56) // int32 | Scope ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApiKeysAPI.ApiV1ApiKeysIdScopesScopeIdDelete(context.Background(), id, scopeId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApiKeysAPI.ApiV1ApiKeysIdScopesScopeIdDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ApiKeysIdScopesScopeIdDelete`: MessageResponse
	fmt.Fprintf(os.Stdout, "Response from `ApiKeysAPI.ApiV1ApiKeysIdScopesScopeIdDelete`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | API key ID | 
**scopeId** | **int32** | Scope ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ApiKeysIdScopesScopeIdDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**MessageResponse**](MessageResponse.md)

### Authorization

[session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ApiKeysPost

> CreateAPIKeyResponse ApiV1ApiKeysPost(ctx).CreateAPIKeyRequest(createAPIKeyRequest).Execute()

Create API key



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
	createAPIKeyRequest := *openapiclient.NewCreateAPIKeyRequest("Name_example") // CreateAPIKeyRequest | API key creation request

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApiKeysAPI.ApiV1ApiKeysPost(context.Background()).CreateAPIKeyRequest(createAPIKeyRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApiKeysAPI.ApiV1ApiKeysPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ApiKeysPost`: CreateAPIKeyResponse
	fmt.Fprintf(os.Stdout, "Response from `ApiKeysAPI.ApiV1ApiKeysPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ApiKeysPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createAPIKeyRequest** | [**CreateAPIKeyRequest**](CreateAPIKeyRequest.md) | API key creation request | 

### Return type

[**CreateAPIKeyResponse**](CreateAPIKeyResponse.md)

### Authorization

[session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

