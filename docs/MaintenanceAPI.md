# \MaintenanceAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApiV1ServersServeridMaintenanceInfoGet**](MaintenanceAPI.md#ApiV1ServersServeridMaintenanceInfoGet) | **Get** /api/v1/servers/{serverid}/maintenance/info | Get Docker system information
[**ApiV1ServersServeridMaintenancePermissionsGet**](MaintenanceAPI.md#ApiV1ServersServeridMaintenancePermissionsGet) | **Get** /api/v1/servers/{serverid}/maintenance/permissions | Check maintenance permissions
[**ApiV1ServersServeridMaintenancePrunePost**](MaintenanceAPI.md#ApiV1ServersServeridMaintenancePrunePost) | **Post** /api/v1/servers/{serverid}/maintenance/prune | Prune Docker resources
[**ApiV1ServersServeridMaintenanceResourceDelete**](MaintenanceAPI.md#ApiV1ServersServeridMaintenanceResourceDelete) | **Delete** /api/v1/servers/{serverid}/maintenance/resource | Delete Docker resource



## ApiV1ServersServeridMaintenanceInfoGet

> MaintenanceInfo ApiV1ServersServeridMaintenanceInfoGet(ctx, serverid).Execute()

Get Docker system information



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
	resp, r, err := apiClient.MaintenanceAPI.ApiV1ServersServeridMaintenanceInfoGet(context.Background(), serverid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MaintenanceAPI.ApiV1ServersServeridMaintenanceInfoGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridMaintenanceInfoGet`: MaintenanceInfo
	fmt.Fprintf(os.Stdout, "Response from `MaintenanceAPI.ApiV1ServersServeridMaintenanceInfoGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridMaintenanceInfoGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**MaintenanceInfo**](MaintenanceInfo.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ServersServeridMaintenancePermissionsGet

> PermissionsResponse ApiV1ServersServeridMaintenancePermissionsGet(ctx, serverid).Execute()

Check maintenance permissions



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
	resp, r, err := apiClient.MaintenanceAPI.ApiV1ServersServeridMaintenancePermissionsGet(context.Background(), serverid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MaintenanceAPI.ApiV1ServersServeridMaintenancePermissionsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridMaintenancePermissionsGet`: PermissionsResponse
	fmt.Fprintf(os.Stdout, "Response from `MaintenanceAPI.ApiV1ServersServeridMaintenancePermissionsGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridMaintenancePermissionsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PermissionsResponse**](PermissionsResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ServersServeridMaintenancePrunePost

> PruneResult ApiV1ServersServeridMaintenancePrunePost(ctx, serverid).PruneRequest(pruneRequest).Execute()

Prune Docker resources



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
	pruneRequest := *openapiclient.NewPruneRequest(false, "Filters_example", false, "Type_example") // PruneRequest | Prune request specifying the resource type to prune

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MaintenanceAPI.ApiV1ServersServeridMaintenancePrunePost(context.Background(), serverid).PruneRequest(pruneRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MaintenanceAPI.ApiV1ServersServeridMaintenancePrunePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridMaintenancePrunePost`: PruneResult
	fmt.Fprintf(os.Stdout, "Response from `MaintenanceAPI.ApiV1ServersServeridMaintenancePrunePost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridMaintenancePrunePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **pruneRequest** | [**PruneRequest**](PruneRequest.md) | Prune request specifying the resource type to prune | 

### Return type

[**PruneResult**](PruneResult.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ServersServeridMaintenanceResourceDelete

> DeleteResult ApiV1ServersServeridMaintenanceResourceDelete(ctx, serverid).DeleteRequest(deleteRequest).Execute()

Delete Docker resource



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
	deleteRequest := *openapiclient.NewDeleteRequest("Id_example", "Type_example") // DeleteRequest | Delete request specifying the resource type and ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MaintenanceAPI.ApiV1ServersServeridMaintenanceResourceDelete(context.Background(), serverid).DeleteRequest(deleteRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MaintenanceAPI.ApiV1ServersServeridMaintenanceResourceDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridMaintenanceResourceDelete`: DeleteResult
	fmt.Fprintf(os.Stdout, "Response from `MaintenanceAPI.ApiV1ServersServeridMaintenanceResourceDelete`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridMaintenanceResourceDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **deleteRequest** | [**DeleteRequest**](DeleteRequest.md) | Delete request specifying the resource type and ID | 

### Return type

[**DeleteResult**](DeleteResult.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

