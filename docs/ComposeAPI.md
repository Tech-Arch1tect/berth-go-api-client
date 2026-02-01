# \ComposeAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApiV1ServersServeridStacksStacknameComposeGet**](ComposeAPI.md#ApiV1ServersServeridStacksStacknameComposeGet) | **Get** /api/v1/servers/{serverid}/stacks/{stackname}/compose | Get compose configuration
[**ApiV1ServersServeridStacksStacknameComposePatch**](ComposeAPI.md#ApiV1ServersServeridStacksStacknameComposePatch) | **Patch** /api/v1/servers/{serverid}/stacks/{stackname}/compose | Update compose configuration



## ApiV1ServersServeridStacksStacknameComposeGet

> RawComposeConfig ApiV1ServersServeridStacksStacknameComposeGet(ctx, serverid, stackname).Execute()

Get compose configuration



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
	resp, r, err := apiClient.ComposeAPI.ApiV1ServersServeridStacksStacknameComposeGet(context.Background(), serverid, stackname).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ComposeAPI.ApiV1ServersServeridStacksStacknameComposeGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridStacksStacknameComposeGet`: RawComposeConfig
	fmt.Fprintf(os.Stdout, "Response from `ComposeAPI.ApiV1ServersServeridStacksStacknameComposeGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 
**stackname** | **string** | Stack name | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridStacksStacknameComposeGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**RawComposeConfig**](RawComposeConfig.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ServersServeridStacksStacknameComposePatch

> UpdateComposeResponse ApiV1ServersServeridStacksStacknameComposePatch(ctx, serverid, stackname).UpdateComposeRequest(updateComposeRequest).Execute()

Update compose configuration



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
	updateComposeRequest := *openapiclient.NewUpdateComposeRequest(*openapiclient.NewComposeChanges()) // UpdateComposeRequest | Changes to apply to the compose file

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ComposeAPI.ApiV1ServersServeridStacksStacknameComposePatch(context.Background(), serverid, stackname).UpdateComposeRequest(updateComposeRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ComposeAPI.ApiV1ServersServeridStacksStacknameComposePatch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridStacksStacknameComposePatch`: UpdateComposeResponse
	fmt.Fprintf(os.Stdout, "Response from `ComposeAPI.ApiV1ServersServeridStacksStacknameComposePatch`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 
**stackname** | **string** | Stack name | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridStacksStacknameComposePatchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updateComposeRequest** | [**UpdateComposeRequest**](UpdateComposeRequest.md) | Changes to apply to the compose file | 

### Return type

[**UpdateComposeResponse**](UpdateComposeResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

