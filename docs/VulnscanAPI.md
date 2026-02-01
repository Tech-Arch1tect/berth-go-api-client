# \VulnscanAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApiV1ServersServeridStacksStacknameVulnscanGet**](VulnscanAPI.md#ApiV1ServersServeridStacksStacknameVulnscanGet) | **Get** /api/v1/servers/{serverid}/stacks/{stackname}/vulnscan | Get latest scan for stack
[**ApiV1ServersServeridStacksStacknameVulnscanHistoryGet**](VulnscanAPI.md#ApiV1ServersServeridStacksStacknameVulnscanHistoryGet) | **Get** /api/v1/servers/{serverid}/stacks/{stackname}/vulnscan/history | Get scan history for stack
[**ApiV1ServersServeridStacksStacknameVulnscanPost**](VulnscanAPI.md#ApiV1ServersServeridStacksStacknameVulnscanPost) | **Post** /api/v1/servers/{serverid}/stacks/{stackname}/vulnscan | Start vulnerability scan
[**ApiV1ServersServeridStacksStacknameVulnscanTrendGet**](VulnscanAPI.md#ApiV1ServersServeridStacksStacknameVulnscanTrendGet) | **Get** /api/v1/servers/{serverid}/stacks/{stackname}/vulnscan/trend | Get scan trend for stack
[**ApiV1VulnscanCompareBaseScanIdCompareScanIdGet**](VulnscanAPI.md#ApiV1VulnscanCompareBaseScanIdCompareScanIdGet) | **Get** /api/v1/vulnscan/compare/{baseScanId}/{compareScanId} | Compare two scans
[**ApiV1VulnscanScanidGet**](VulnscanAPI.md#ApiV1VulnscanScanidGet) | **Get** /api/v1/vulnscan/{scanid} | Get scan by ID
[**ApiV1VulnscanScanidSummaryGet**](VulnscanAPI.md#ApiV1VulnscanScanidSummaryGet) | **Get** /api/v1/vulnscan/{scanid}/summary | Get scan summary



## ApiV1ServersServeridStacksStacknameVulnscanGet

> GetLatestScanResponse ApiV1ServersServeridStacksStacknameVulnscanGet(ctx, serverid, stackname).Execute()

Get latest scan for stack



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
	resp, r, err := apiClient.VulnscanAPI.ApiV1ServersServeridStacksStacknameVulnscanGet(context.Background(), serverid, stackname).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VulnscanAPI.ApiV1ServersServeridStacksStacknameVulnscanGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridStacksStacknameVulnscanGet`: GetLatestScanResponse
	fmt.Fprintf(os.Stdout, "Response from `VulnscanAPI.ApiV1ServersServeridStacksStacknameVulnscanGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 
**stackname** | **string** | Stack name | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridStacksStacknameVulnscanGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**GetLatestScanResponse**](GetLatestScanResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ServersServeridStacksStacknameVulnscanHistoryGet

> GetScansHistoryResponse ApiV1ServersServeridStacksStacknameVulnscanHistoryGet(ctx, serverid, stackname).Execute()

Get scan history for stack



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
	resp, r, err := apiClient.VulnscanAPI.ApiV1ServersServeridStacksStacknameVulnscanHistoryGet(context.Background(), serverid, stackname).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VulnscanAPI.ApiV1ServersServeridStacksStacknameVulnscanHistoryGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridStacksStacknameVulnscanHistoryGet`: GetScansHistoryResponse
	fmt.Fprintf(os.Stdout, "Response from `VulnscanAPI.ApiV1ServersServeridStacksStacknameVulnscanHistoryGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 
**stackname** | **string** | Stack name | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridStacksStacknameVulnscanHistoryGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**GetScansHistoryResponse**](GetScansHistoryResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ServersServeridStacksStacknameVulnscanPost

> StartScanResponse ApiV1ServersServeridStacksStacknameVulnscanPost(ctx, serverid, stackname).StartScanRequest(startScanRequest).Execute()

Start vulnerability scan



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
	startScanRequest := *openapiclient.NewStartScanRequest() // StartScanRequest | Optional list of services to scan

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.VulnscanAPI.ApiV1ServersServeridStacksStacknameVulnscanPost(context.Background(), serverid, stackname).StartScanRequest(startScanRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VulnscanAPI.ApiV1ServersServeridStacksStacknameVulnscanPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridStacksStacknameVulnscanPost`: StartScanResponse
	fmt.Fprintf(os.Stdout, "Response from `VulnscanAPI.ApiV1ServersServeridStacksStacknameVulnscanPost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 
**stackname** | **string** | Stack name | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridStacksStacknameVulnscanPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **startScanRequest** | [**StartScanRequest**](StartScanRequest.md) | Optional list of services to scan | 

### Return type

[**StartScanResponse**](StartScanResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ServersServeridStacksStacknameVulnscanTrendGet

> GetScanTrendResponse ApiV1ServersServeridStacksStacknameVulnscanTrendGet(ctx, serverid, stackname).Limit(limit).Execute()

Get scan trend for stack



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
	limit := int32(56) // int32 | Maximum number of scans to include (default 10, max 50) (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.VulnscanAPI.ApiV1ServersServeridStacksStacknameVulnscanTrendGet(context.Background(), serverid, stackname).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VulnscanAPI.ApiV1ServersServeridStacksStacknameVulnscanTrendGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridStacksStacknameVulnscanTrendGet`: GetScanTrendResponse
	fmt.Fprintf(os.Stdout, "Response from `VulnscanAPI.ApiV1ServersServeridStacksStacknameVulnscanTrendGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 
**stackname** | **string** | Stack name | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridStacksStacknameVulnscanTrendGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **limit** | **int32** | Maximum number of scans to include (default 10, max 50) | 

### Return type

[**GetScanTrendResponse**](GetScanTrendResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1VulnscanCompareBaseScanIdCompareScanIdGet

> CompareScanResponse ApiV1VulnscanCompareBaseScanIdCompareScanIdGet(ctx, baseScanId, compareScanId).Execute()

Compare two scans



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
	baseScanId := int32(56) // int32 | Base scan ID
	compareScanId := int32(56) // int32 | Comparison scan ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.VulnscanAPI.ApiV1VulnscanCompareBaseScanIdCompareScanIdGet(context.Background(), baseScanId, compareScanId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VulnscanAPI.ApiV1VulnscanCompareBaseScanIdCompareScanIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1VulnscanCompareBaseScanIdCompareScanIdGet`: CompareScanResponse
	fmt.Fprintf(os.Stdout, "Response from `VulnscanAPI.ApiV1VulnscanCompareBaseScanIdCompareScanIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**baseScanId** | **int32** | Base scan ID | 
**compareScanId** | **int32** | Comparison scan ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1VulnscanCompareBaseScanIdCompareScanIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**CompareScanResponse**](CompareScanResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1VulnscanScanidGet

> GetScanResponse ApiV1VulnscanScanidGet(ctx, scanid).Execute()

Get scan by ID



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
	scanid := int32(56) // int32 | Scan ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.VulnscanAPI.ApiV1VulnscanScanidGet(context.Background(), scanid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VulnscanAPI.ApiV1VulnscanScanidGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1VulnscanScanidGet`: GetScanResponse
	fmt.Fprintf(os.Stdout, "Response from `VulnscanAPI.ApiV1VulnscanScanidGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**scanid** | **int32** | Scan ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1VulnscanScanidGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**GetScanResponse**](GetScanResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1VulnscanScanidSummaryGet

> GetScanSummaryResponse ApiV1VulnscanScanidSummaryGet(ctx, scanid).Execute()

Get scan summary



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
	scanid := int32(56) // int32 | Scan ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.VulnscanAPI.ApiV1VulnscanScanidSummaryGet(context.Background(), scanid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VulnscanAPI.ApiV1VulnscanScanidSummaryGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1VulnscanScanidSummaryGet`: GetScanSummaryResponse
	fmt.Fprintf(os.Stdout, "Response from `VulnscanAPI.ApiV1VulnscanScanidSummaryGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**scanid** | **int32** | Scan ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1VulnscanScanidSummaryGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**GetScanSummaryResponse**](GetScanSummaryResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

