# \ImageUpdatesAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApiV1ImageUpdatesGet**](ImageUpdatesAPI.md#ApiV1ImageUpdatesGet) | **Get** /api/v1/image-updates | List available image updates
[**ApiV1ServersServeridImageUpdatesGet**](ImageUpdatesAPI.md#ApiV1ServersServeridImageUpdatesGet) | **Get** /api/v1/servers/{serverid}/image-updates | List server image updates



## ApiV1ImageUpdatesGet

> ImageUpdatesResponse ApiV1ImageUpdatesGet(ctx).Execute()

List available image updates



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
	resp, r, err := apiClient.ImageUpdatesAPI.ApiV1ImageUpdatesGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ImageUpdatesAPI.ApiV1ImageUpdatesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ImageUpdatesGet`: ImageUpdatesResponse
	fmt.Fprintf(os.Stdout, "Response from `ImageUpdatesAPI.ApiV1ImageUpdatesGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ImageUpdatesGetRequest struct via the builder pattern


### Return type

[**ImageUpdatesResponse**](ImageUpdatesResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ServersServeridImageUpdatesGet

> ImageUpdatesResponse ApiV1ServersServeridImageUpdatesGet(ctx, serverid).Execute()

List server image updates



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
	serverid := int32(56) // int32 | Server ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ImageUpdatesAPI.ApiV1ServersServeridImageUpdatesGet(context.Background(), serverid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ImageUpdatesAPI.ApiV1ServersServeridImageUpdatesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridImageUpdatesGet`: ImageUpdatesResponse
	fmt.Fprintf(os.Stdout, "Response from `ImageUpdatesAPI.ApiV1ServersServeridImageUpdatesGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridImageUpdatesGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ImageUpdatesResponse**](ImageUpdatesResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

