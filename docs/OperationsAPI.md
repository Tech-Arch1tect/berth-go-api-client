# \OperationsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApiV1ServersServeridStacksStacknameOperationsPost**](OperationsAPI.md#ApiV1ServersServeridStacksStacknameOperationsPost) | **Post** /api/v1/servers/{serverid}/stacks/{stackname}/operations | Start a stack operation



## ApiV1ServersServeridStacksStacknameOperationsPost

> ResponseOperationStartData ApiV1ServersServeridStacksStacknameOperationsPost(ctx, serverid, stackname).OperationRequest(operationRequest).Execute()

Start a stack operation



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
	operationRequest := *openapiclient.NewOperationRequest("Command_example", []string{"Options_example"}, []string{"Services_example"}) // OperationRequest | Operation command and options

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperationsAPI.ApiV1ServersServeridStacksStacknameOperationsPost(context.Background(), serverid, stackname).OperationRequest(operationRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperationsAPI.ApiV1ServersServeridStacksStacknameOperationsPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridStacksStacknameOperationsPost`: ResponseOperationStartData
	fmt.Fprintf(os.Stdout, "Response from `OperationsAPI.ApiV1ServersServeridStacksStacknameOperationsPost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 
**stackname** | **string** | Stack name | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridStacksStacknameOperationsPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **operationRequest** | [**OperationRequest**](OperationRequest.md) | Operation command and options | 

### Return type

[**ResponseOperationStartData**](ResponseOperationStartData.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

