# \LogsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApiV1ServersServeridStacksStacknameContainersContainerNameLogsGet**](LogsAPI.md#ApiV1ServersServeridStacksStacknameContainersContainerNameLogsGet) | **Get** /api/v1/servers/{serverid}/stacks/{stackname}/containers/{containerName}/logs | Get container logs
[**ApiV1ServersServeridStacksStacknameLogsGet**](LogsAPI.md#ApiV1ServersServeridStacksStacknameLogsGet) | **Get** /api/v1/servers/{serverid}/stacks/{stackname}/logs | Get stack logs



## ApiV1ServersServeridStacksStacknameContainersContainerNameLogsGet

> LogsResponse ApiV1ServersServeridStacksStacknameContainersContainerNameLogsGet(ctx, serverid, stackname, containerName).Tail(tail).Since(since).Timestamps(timestamps).Execute()

Get container logs



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
	stackname := "stackname_example" // string | Stack name
	containerName := "containerName_example" // string | Container name
	tail := int32(56) // int32 | Number of log lines to return (optional) (default to 100)
	since := "since_example" // string | Only return logs since this timestamp (RFC3339 format) (optional)
	timestamps := true // bool | Include timestamps in log output (optional) (default to true)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LogsAPI.ApiV1ServersServeridStacksStacknameContainersContainerNameLogsGet(context.Background(), serverid, stackname, containerName).Tail(tail).Since(since).Timestamps(timestamps).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LogsAPI.ApiV1ServersServeridStacksStacknameContainersContainerNameLogsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridStacksStacknameContainersContainerNameLogsGet`: LogsResponse
	fmt.Fprintf(os.Stdout, "Response from `LogsAPI.ApiV1ServersServeridStacksStacknameContainersContainerNameLogsGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 
**stackname** | **string** | Stack name | 
**containerName** | **string** | Container name | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridStacksStacknameContainersContainerNameLogsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **tail** | **int32** | Number of log lines to return | [default to 100]
 **since** | **string** | Only return logs since this timestamp (RFC3339 format) | 
 **timestamps** | **bool** | Include timestamps in log output | [default to true]

### Return type

[**LogsResponse**](LogsResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ServersServeridStacksStacknameLogsGet

> LogsResponse ApiV1ServersServeridStacksStacknameLogsGet(ctx, serverid, stackname).Tail(tail).Since(since).Timestamps(timestamps).Execute()

Get stack logs



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
	stackname := "stackname_example" // string | Stack name
	tail := int32(56) // int32 | Number of log lines to return (optional) (default to 100)
	since := "since_example" // string | Only return logs since this timestamp (RFC3339 format) (optional)
	timestamps := true // bool | Include timestamps in log output (optional) (default to true)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LogsAPI.ApiV1ServersServeridStacksStacknameLogsGet(context.Background(), serverid, stackname).Tail(tail).Since(since).Timestamps(timestamps).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LogsAPI.ApiV1ServersServeridStacksStacknameLogsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridStacksStacknameLogsGet`: LogsResponse
	fmt.Fprintf(os.Stdout, "Response from `LogsAPI.ApiV1ServersServeridStacksStacknameLogsGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 
**stackname** | **string** | Stack name | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridStacksStacknameLogsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **tail** | **int32** | Number of log lines to return | [default to 100]
 **since** | **string** | Only return logs since this timestamp (RFC3339 format) | 
 **timestamps** | **bool** | Include timestamps in log output | [default to true]

### Return type

[**LogsResponse**](LogsResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

