# \StacksAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApiV1ServersServeridStacksCanCreateGet**](StacksAPI.md#ApiV1ServersServeridStacksCanCreateGet) | **Get** /api/v1/servers/{serverid}/stacks/can-create | Check if user can create stacks
[**ApiV1ServersServeridStacksGet**](StacksAPI.md#ApiV1ServersServeridStacksGet) | **Get** /api/v1/servers/{serverid}/stacks | List server stacks
[**ApiV1ServersServeridStacksPost**](StacksAPI.md#ApiV1ServersServeridStacksPost) | **Post** /api/v1/servers/{serverid}/stacks | Create a new stack
[**ApiV1ServersServeridStacksStacknameComposeGet**](StacksAPI.md#ApiV1ServersServeridStacksStacknameComposeGet) | **Get** /api/v1/servers/{serverid}/stacks/{stackname}/compose | Get compose configuration
[**ApiV1ServersServeridStacksStacknameComposePatch**](StacksAPI.md#ApiV1ServersServeridStacksStacknameComposePatch) | **Patch** /api/v1/servers/{serverid}/stacks/{stackname}/compose | Update compose configuration
[**ApiV1ServersServeridStacksStacknameEnvironmentGet**](StacksAPI.md#ApiV1ServersServeridStacksStacknameEnvironmentGet) | **Get** /api/v1/servers/{serverid}/stacks/{stackname}/environment | Get stack environment variables
[**ApiV1ServersServeridStacksStacknameGet**](StacksAPI.md#ApiV1ServersServeridStacksStacknameGet) | **Get** /api/v1/servers/{serverid}/stacks/{stackname} | Get stack details
[**ApiV1ServersServeridStacksStacknameImagesGet**](StacksAPI.md#ApiV1ServersServeridStacksStacknameImagesGet) | **Get** /api/v1/servers/{serverid}/stacks/{stackname}/images | Get container image details
[**ApiV1ServersServeridStacksStacknameNetworksGet**](StacksAPI.md#ApiV1ServersServeridStacksStacknameNetworksGet) | **Get** /api/v1/servers/{serverid}/stacks/{stackname}/networks | Get stack networks
[**ApiV1ServersServeridStacksStacknamePermissionsGet**](StacksAPI.md#ApiV1ServersServeridStacksStacknamePermissionsGet) | **Get** /api/v1/servers/{serverid}/stacks/{stackname}/permissions | Check stack permissions
[**ApiV1ServersServeridStacksStacknameStatsGet**](StacksAPI.md#ApiV1ServersServeridStacksStacknameStatsGet) | **Get** /api/v1/servers/{serverid}/stacks/{stackname}/stats | Get stack statistics
[**ApiV1ServersServeridStacksStacknameVolumesGet**](StacksAPI.md#ApiV1ServersServeridStacksStacknameVolumesGet) | **Get** /api/v1/servers/{serverid}/stacks/{stackname}/volumes | Get stack volumes



## ApiV1ServersServeridStacksCanCreateGet

> CanCreateStackResponse ApiV1ServersServeridStacksCanCreateGet(ctx, serverid).Execute()

Check if user can create stacks



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
	resp, r, err := apiClient.StacksAPI.ApiV1ServersServeridStacksCanCreateGet(context.Background(), serverid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StacksAPI.ApiV1ServersServeridStacksCanCreateGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridStacksCanCreateGet`: CanCreateStackResponse
	fmt.Fprintf(os.Stdout, "Response from `StacksAPI.ApiV1ServersServeridStacksCanCreateGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridStacksCanCreateGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**CanCreateStackResponse**](CanCreateStackResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ServersServeridStacksGet

> ListStacksResponse ApiV1ServersServeridStacksGet(ctx, serverid).Execute()

List server stacks



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
	resp, r, err := apiClient.StacksAPI.ApiV1ServersServeridStacksGet(context.Background(), serverid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StacksAPI.ApiV1ServersServeridStacksGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridStacksGet`: ListStacksResponse
	fmt.Fprintf(os.Stdout, "Response from `StacksAPI.ApiV1ServersServeridStacksGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridStacksGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ListStacksResponse**](ListStacksResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ServersServeridStacksPost

> CreateStackResponse ApiV1ServersServeridStacksPost(ctx, serverid).CreateStackRequest(createStackRequest).Execute()

Create a new stack



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
	createStackRequest := *openapiclient.NewCreateStackRequest("Name_example") // CreateStackRequest | Stack creation request

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StacksAPI.ApiV1ServersServeridStacksPost(context.Background(), serverid).CreateStackRequest(createStackRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StacksAPI.ApiV1ServersServeridStacksPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridStacksPost`: CreateStackResponse
	fmt.Fprintf(os.Stdout, "Response from `StacksAPI.ApiV1ServersServeridStacksPost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridStacksPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createStackRequest** | [**CreateStackRequest**](CreateStackRequest.md) | Stack creation request | 

### Return type

[**CreateStackResponse**](CreateStackResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


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
	resp, r, err := apiClient.StacksAPI.ApiV1ServersServeridStacksStacknameComposeGet(context.Background(), serverid, stackname).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StacksAPI.ApiV1ServersServeridStacksStacknameComposeGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridStacksStacknameComposeGet`: RawComposeConfig
	fmt.Fprintf(os.Stdout, "Response from `StacksAPI.ApiV1ServersServeridStacksStacknameComposeGet`: %v\n", resp)
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
	resp, r, err := apiClient.StacksAPI.ApiV1ServersServeridStacksStacknameComposePatch(context.Background(), serverid, stackname).UpdateComposeRequest(updateComposeRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StacksAPI.ApiV1ServersServeridStacksStacknameComposePatch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridStacksStacknameComposePatch`: UpdateComposeResponse
	fmt.Fprintf(os.Stdout, "Response from `StacksAPI.ApiV1ServersServeridStacksStacknameComposePatch`: %v\n", resp)
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


## ApiV1ServersServeridStacksStacknameEnvironmentGet

> StackEnvironmentResponse ApiV1ServersServeridStacksStacknameEnvironmentGet(ctx, serverid, stackname).Unmask(unmask).Execute()

Get stack environment variables



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
	unmask := "unmask_example" // string | Set to true to unmask sensitive values (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StacksAPI.ApiV1ServersServeridStacksStacknameEnvironmentGet(context.Background(), serverid, stackname).Unmask(unmask).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StacksAPI.ApiV1ServersServeridStacksStacknameEnvironmentGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridStacksStacknameEnvironmentGet`: StackEnvironmentResponse
	fmt.Fprintf(os.Stdout, "Response from `StacksAPI.ApiV1ServersServeridStacksStacknameEnvironmentGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 
**stackname** | **string** | Stack name | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridStacksStacknameEnvironmentGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **unmask** | **string** | Set to true to unmask sensitive values | 

### Return type

[**StackEnvironmentResponse**](StackEnvironmentResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ServersServeridStacksStacknameGet

> StackDetails ApiV1ServersServeridStacksStacknameGet(ctx, serverid, stackname).Execute()

Get stack details



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
	resp, r, err := apiClient.StacksAPI.ApiV1ServersServeridStacksStacknameGet(context.Background(), serverid, stackname).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StacksAPI.ApiV1ServersServeridStacksStacknameGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridStacksStacknameGet`: StackDetails
	fmt.Fprintf(os.Stdout, "Response from `StacksAPI.ApiV1ServersServeridStacksStacknameGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 
**stackname** | **string** | Stack name | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridStacksStacknameGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**StackDetails**](StackDetails.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ServersServeridStacksStacknameImagesGet

> StackImagesResponse ApiV1ServersServeridStacksStacknameImagesGet(ctx, serverid, stackname).Execute()

Get container image details



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
	resp, r, err := apiClient.StacksAPI.ApiV1ServersServeridStacksStacknameImagesGet(context.Background(), serverid, stackname).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StacksAPI.ApiV1ServersServeridStacksStacknameImagesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridStacksStacknameImagesGet`: StackImagesResponse
	fmt.Fprintf(os.Stdout, "Response from `StacksAPI.ApiV1ServersServeridStacksStacknameImagesGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 
**stackname** | **string** | Stack name | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridStacksStacknameImagesGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**StackImagesResponse**](StackImagesResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ServersServeridStacksStacknameNetworksGet

> StackNetworksResponse ApiV1ServersServeridStacksStacknameNetworksGet(ctx, serverid, stackname).Execute()

Get stack networks



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
	resp, r, err := apiClient.StacksAPI.ApiV1ServersServeridStacksStacknameNetworksGet(context.Background(), serverid, stackname).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StacksAPI.ApiV1ServersServeridStacksStacknameNetworksGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridStacksStacknameNetworksGet`: StackNetworksResponse
	fmt.Fprintf(os.Stdout, "Response from `StacksAPI.ApiV1ServersServeridStacksStacknameNetworksGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 
**stackname** | **string** | Stack name | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridStacksStacknameNetworksGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**StackNetworksResponse**](StackNetworksResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ServersServeridStacksStacknamePermissionsGet

> StackPermissionsResponse ApiV1ServersServeridStacksStacknamePermissionsGet(ctx, serverid, stackname).Execute()

Check stack permissions



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
	resp, r, err := apiClient.StacksAPI.ApiV1ServersServeridStacksStacknamePermissionsGet(context.Background(), serverid, stackname).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StacksAPI.ApiV1ServersServeridStacksStacknamePermissionsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridStacksStacknamePermissionsGet`: StackPermissionsResponse
	fmt.Fprintf(os.Stdout, "Response from `StacksAPI.ApiV1ServersServeridStacksStacknamePermissionsGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 
**stackname** | **string** | Stack name | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridStacksStacknamePermissionsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**StackPermissionsResponse**](StackPermissionsResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ServersServeridStacksStacknameStatsGet

> StackStatsResponse ApiV1ServersServeridStacksStacknameStatsGet(ctx, serverid, stackname).Execute()

Get stack statistics



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
	resp, r, err := apiClient.StacksAPI.ApiV1ServersServeridStacksStacknameStatsGet(context.Background(), serverid, stackname).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StacksAPI.ApiV1ServersServeridStacksStacknameStatsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridStacksStacknameStatsGet`: StackStatsResponse
	fmt.Fprintf(os.Stdout, "Response from `StacksAPI.ApiV1ServersServeridStacksStacknameStatsGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 
**stackname** | **string** | Stack name | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridStacksStacknameStatsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**StackStatsResponse**](StackStatsResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ServersServeridStacksStacknameVolumesGet

> StackVolumesResponse ApiV1ServersServeridStacksStacknameVolumesGet(ctx, serverid, stackname).Execute()

Get stack volumes



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
	resp, r, err := apiClient.StacksAPI.ApiV1ServersServeridStacksStacknameVolumesGet(context.Background(), serverid, stackname).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StacksAPI.ApiV1ServersServeridStacksStacknameVolumesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridStacksStacknameVolumesGet`: StackVolumesResponse
	fmt.Fprintf(os.Stdout, "Response from `StacksAPI.ApiV1ServersServeridStacksStacknameVolumesGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 
**stackname** | **string** | Stack name | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridStacksStacknameVolumesGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**StackVolumesResponse**](StackVolumesResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

