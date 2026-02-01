# \ServersAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApiV1AdminServersGet**](ServersAPI.md#ApiV1AdminServersGet) | **Get** /api/v1/admin/servers | List all servers
[**ApiV1AdminServersIdDelete**](ServersAPI.md#ApiV1AdminServersIdDelete) | **Delete** /api/v1/admin/servers/{id} | Delete a server
[**ApiV1AdminServersIdPut**](ServersAPI.md#ApiV1AdminServersIdPut) | **Put** /api/v1/admin/servers/{id} | Update a server
[**ApiV1AdminServersIdTestPost**](ServersAPI.md#ApiV1AdminServersIdTestPost) | **Post** /api/v1/admin/servers/{id}/test | Test server connection
[**ApiV1AdminServersPost**](ServersAPI.md#ApiV1AdminServersPost) | **Post** /api/v1/admin/servers | Create a new server
[**ApiV1ServersGet**](ServersAPI.md#ApiV1ServersGet) | **Get** /api/v1/servers | List accessible servers
[**ApiV1ServersServeridStatisticsGet**](ServersAPI.md#ApiV1ServersServeridStatisticsGet) | **Get** /api/v1/servers/{serverid}/statistics | Get server statistics



## ApiV1AdminServersGet

> AdminListServersResponse ApiV1AdminServersGet(ctx).Execute()

List all servers



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
	resp, r, err := apiClient.ServersAPI.ApiV1AdminServersGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ServersAPI.ApiV1AdminServersGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminServersGet`: AdminListServersResponse
	fmt.Fprintf(os.Stdout, "Response from `ServersAPI.ApiV1AdminServersGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AdminServersGetRequest struct via the builder pattern


### Return type

[**AdminListServersResponse**](AdminListServersResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1AdminServersIdDelete

> AdminDeleteServerResponse ApiV1AdminServersIdDelete(ctx, id).Execute()

Delete a server



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
	id := int32(56) // int32 | Server ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ServersAPI.ApiV1AdminServersIdDelete(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ServersAPI.ApiV1AdminServersIdDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminServersIdDelete`: AdminDeleteServerResponse
	fmt.Fprintf(os.Stdout, "Response from `ServersAPI.ApiV1AdminServersIdDelete`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Server ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AdminServersIdDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AdminDeleteServerResponse**](AdminDeleteServerResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1AdminServersIdPut

> AdminUpdateServerResponse ApiV1AdminServersIdPut(ctx, id).ServerUpdateRequest(serverUpdateRequest).Execute()

Update a server



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
	id := int32(56) // int32 | Server ID
	serverUpdateRequest := *openapiclient.NewServerUpdateRequest("AccessToken_example", "Description_example", "Host_example", false, "Name_example", int32(123), false) // ServerUpdateRequest | Server details

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ServersAPI.ApiV1AdminServersIdPut(context.Background(), id).ServerUpdateRequest(serverUpdateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ServersAPI.ApiV1AdminServersIdPut``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminServersIdPut`: AdminUpdateServerResponse
	fmt.Fprintf(os.Stdout, "Response from `ServersAPI.ApiV1AdminServersIdPut`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Server ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AdminServersIdPutRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **serverUpdateRequest** | [**ServerUpdateRequest**](ServerUpdateRequest.md) | Server details | 

### Return type

[**AdminUpdateServerResponse**](AdminUpdateServerResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1AdminServersIdTestPost

> AdminTestConnectionResponse ApiV1AdminServersIdTestPost(ctx, id).Execute()

Test server connection



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
	id := int32(56) // int32 | Server ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ServersAPI.ApiV1AdminServersIdTestPost(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ServersAPI.ApiV1AdminServersIdTestPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminServersIdTestPost`: AdminTestConnectionResponse
	fmt.Fprintf(os.Stdout, "Response from `ServersAPI.ApiV1AdminServersIdTestPost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Server ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AdminServersIdTestPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AdminTestConnectionResponse**](AdminTestConnectionResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1AdminServersPost

> AdminCreateServerResponse ApiV1AdminServersPost(ctx).ServerCreateRequest(serverCreateRequest).Execute()

Create a new server



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
	serverCreateRequest := *openapiclient.NewServerCreateRequest("AccessToken_example", "Description_example", "Host_example", false, "Name_example", int32(123), false) // ServerCreateRequest | Server details

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ServersAPI.ApiV1AdminServersPost(context.Background()).ServerCreateRequest(serverCreateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ServersAPI.ApiV1AdminServersPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminServersPost`: AdminCreateServerResponse
	fmt.Fprintf(os.Stdout, "Response from `ServersAPI.ApiV1AdminServersPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AdminServersPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **serverCreateRequest** | [**ServerCreateRequest**](ServerCreateRequest.md) | Server details | 

### Return type

[**AdminCreateServerResponse**](AdminCreateServerResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ServersGet

> ListServersResponse ApiV1ServersGet(ctx).Execute()

List accessible servers



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
	resp, r, err := apiClient.ServersAPI.ApiV1ServersGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ServersAPI.ApiV1ServersGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersGet`: ListServersResponse
	fmt.Fprintf(os.Stdout, "Response from `ServersAPI.ApiV1ServersGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersGetRequest struct via the builder pattern


### Return type

[**ListServersResponse**](ListServersResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ServersServeridStatisticsGet

> ServerStatisticsResponse ApiV1ServersServeridStatisticsGet(ctx, serverid).Execute()

Get server statistics



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
	resp, r, err := apiClient.ServersAPI.ApiV1ServersServeridStatisticsGet(context.Background(), serverid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ServersAPI.ApiV1ServersServeridStatisticsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridStatisticsGet`: ServerStatisticsResponse
	fmt.Fprintf(os.Stdout, "Response from `ServersAPI.ApiV1ServersServeridStatisticsGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridStatisticsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ServerStatisticsResponse**](ServerStatisticsResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

