# \OperationLogsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApiV1OperationLogsByOperationIdOperationIdGet**](OperationLogsAPI.md#ApiV1OperationLogsByOperationIdOperationIdGet) | **Get** /api/v1/operation-logs/by-operation-id/{operationId} | Get operation log details by operation ID
[**ApiV1OperationLogsGet**](OperationLogsAPI.md#ApiV1OperationLogsGet) | **Get** /api/v1/operation-logs | List user&#39;s operation logs
[**ApiV1OperationLogsIdGet**](OperationLogsAPI.md#ApiV1OperationLogsIdGet) | **Get** /api/v1/operation-logs/{id} | Get operation log details
[**ApiV1OperationLogsStatsGet**](OperationLogsAPI.md#ApiV1OperationLogsStatsGet) | **Get** /api/v1/operation-logs/stats | Get user&#39;s operation logs statistics
[**ApiV1RunningOperationsGet**](OperationLogsAPI.md#ApiV1RunningOperationsGet) | **Get** /api/v1/running-operations | Get running operations



## ApiV1OperationLogsByOperationIdOperationIdGet

> OperationLogDetailResponse ApiV1OperationLogsByOperationIdOperationIdGet(ctx, operationId).Execute()

Get operation log details by operation ID



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
	operationId := "operationId_example" // string | Operation ID (UUID)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperationLogsAPI.ApiV1OperationLogsByOperationIdOperationIdGet(context.Background(), operationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperationLogsAPI.ApiV1OperationLogsByOperationIdOperationIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1OperationLogsByOperationIdOperationIdGet`: OperationLogDetailResponse
	fmt.Fprintf(os.Stdout, "Response from `OperationLogsAPI.ApiV1OperationLogsByOperationIdOperationIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**operationId** | **string** | Operation ID (UUID) | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1OperationLogsByOperationIdOperationIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**OperationLogDetailResponse**](OperationLogDetailResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1OperationLogsGet

> PaginatedOperationLogsResponse ApiV1OperationLogsGet(ctx).Page(page).PageSize(pageSize).Search(search).ServerId(serverId).StackName(stackName).Command(command).Status(status).DaysBack(daysBack).Execute()

List user's operation logs



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
	page := int32(56) // int32 | Page number (optional) (default to 1)
	pageSize := int32(56) // int32 | Number of items per page (optional) (default to 20)
	search := "search_example" // string | Search term for stack name, command, or operation ID (optional)
	serverId := "serverId_example" // string | Filter by server ID (optional)
	stackName := "stackName_example" // string | Filter by stack name (partial match) (optional)
	command := "command_example" // string | Filter by command (optional)
	status := "status_example" // string | Filter by status (optional)
	daysBack := int32(56) // int32 | Only return logs from the last N days (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperationLogsAPI.ApiV1OperationLogsGet(context.Background()).Page(page).PageSize(pageSize).Search(search).ServerId(serverId).StackName(stackName).Command(command).Status(status).DaysBack(daysBack).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperationLogsAPI.ApiV1OperationLogsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1OperationLogsGet`: PaginatedOperationLogsResponse
	fmt.Fprintf(os.Stdout, "Response from `OperationLogsAPI.ApiV1OperationLogsGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiV1OperationLogsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** | Page number | [default to 1]
 **pageSize** | **int32** | Number of items per page | [default to 20]
 **search** | **string** | Search term for stack name, command, or operation ID | 
 **serverId** | **string** | Filter by server ID | 
 **stackName** | **string** | Filter by stack name (partial match) | 
 **command** | **string** | Filter by command | 
 **status** | **string** | Filter by status | 
 **daysBack** | **int32** | Only return logs from the last N days | 

### Return type

[**PaginatedOperationLogsResponse**](PaginatedOperationLogsResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1OperationLogsIdGet

> OperationLogDetailResponse ApiV1OperationLogsIdGet(ctx, id).Execute()

Get operation log details



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
	id := int32(56) // int32 | Operation log ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperationLogsAPI.ApiV1OperationLogsIdGet(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperationLogsAPI.ApiV1OperationLogsIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1OperationLogsIdGet`: OperationLogDetailResponse
	fmt.Fprintf(os.Stdout, "Response from `OperationLogsAPI.ApiV1OperationLogsIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Operation log ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1OperationLogsIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**OperationLogDetailResponse**](OperationLogDetailResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1OperationLogsStatsGet

> OperationLogStatsResponse ApiV1OperationLogsStatsGet(ctx).Execute()

Get user's operation logs statistics



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
	resp, r, err := apiClient.OperationLogsAPI.ApiV1OperationLogsStatsGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperationLogsAPI.ApiV1OperationLogsStatsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1OperationLogsStatsGet`: OperationLogStatsResponse
	fmt.Fprintf(os.Stdout, "Response from `OperationLogsAPI.ApiV1OperationLogsStatsGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1OperationLogsStatsGetRequest struct via the builder pattern


### Return type

[**OperationLogStatsResponse**](OperationLogStatsResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1RunningOperationsGet

> RunningOperationsResponse ApiV1RunningOperationsGet(ctx).Execute()

Get running operations



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
	resp, r, err := apiClient.OperationLogsAPI.ApiV1RunningOperationsGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperationLogsAPI.ApiV1RunningOperationsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1RunningOperationsGet`: RunningOperationsResponse
	fmt.Fprintf(os.Stdout, "Response from `OperationLogsAPI.ApiV1RunningOperationsGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1RunningOperationsGetRequest struct via the builder pattern


### Return type

[**RunningOperationsResponse**](RunningOperationsResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

