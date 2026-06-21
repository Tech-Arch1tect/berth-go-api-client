# \WebsocketAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**WsApiServersServeridStacksStacknameEventsGet**](WebsocketAPI.md#WsApiServersServeridStacksStacknameEventsGet) | **Get** /ws/api/servers/{serverid}/stacks/{stackname}/events | Per-stack status event stream (WebSocket)
[**WsApiServersServeridStacksStacknameOperationsOperationIdGet**](WebsocketAPI.md#WsApiServersServeridStacksStacknameOperationsOperationIdGet) | **Get** /ws/api/servers/{serverid}/stacks/{stackname}/operations/{operationId} | Operation output stream (WebSocket)
[**WsApiServersServeridStacksStacknameTerminalGet**](WebsocketAPI.md#WsApiServersServeridStacksStacknameTerminalGet) | **Get** /ws/api/servers/{serverid}/stacks/{stackname}/terminal | Interactive container terminal (WebSocket)



## WsApiServersServeridStacksStacknameEventsGet

> WsApiServersServeridStacksStacknameEventsGet(ctx, serverid, stackname).Execute()

Per-stack status event stream (WebSocket)



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.WebsocketAPI.WsApiServersServeridStacksStacknameEventsGet(context.Background(), serverid, stackname).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebsocketAPI.WsApiServersServeridStacksStacknameEventsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 
**stackname** | **string** | Stack name | 

### Other Parameters

Other parameters are passed through a pointer to a apiWsApiServersServeridStacksStacknameEventsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

 (empty response body)

### Authorization

[apiKey](../README.md#apiKey), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## WsApiServersServeridStacksStacknameOperationsOperationIdGet

> WsApiServersServeridStacksStacknameOperationsOperationIdGet(ctx, serverid, stackname, operationId).Execute()

Operation output stream (WebSocket)



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
	operationId := "operationId_example" // string | Operation ID returned by the start-operation endpoint

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.WebsocketAPI.WsApiServersServeridStacksStacknameOperationsOperationIdGet(context.Background(), serverid, stackname, operationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebsocketAPI.WsApiServersServeridStacksStacknameOperationsOperationIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 
**stackname** | **string** | Stack name | 
**operationId** | **string** | Operation ID returned by the start-operation endpoint | 

### Other Parameters

Other parameters are passed through a pointer to a apiWsApiServersServeridStacksStacknameOperationsOperationIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------




### Return type

 (empty response body)

### Authorization

[apiKey](../README.md#apiKey), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## WsApiServersServeridStacksStacknameTerminalGet

> WsApiServersServeridStacksStacknameTerminalGet(ctx, serverid, stackname).Execute()

Interactive container terminal (WebSocket)



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.WebsocketAPI.WsApiServersServeridStacksStacknameTerminalGet(context.Background(), serverid, stackname).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebsocketAPI.WsApiServersServeridStacksStacknameTerminalGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 
**stackname** | **string** | Stack name | 

### Other Parameters

Other parameters are passed through a pointer to a apiWsApiServersServeridStacksStacknameTerminalGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

 (empty response body)

### Authorization

[apiKey](../README.md#apiKey), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

