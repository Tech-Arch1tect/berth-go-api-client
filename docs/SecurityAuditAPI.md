# \SecurityAuditAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApiV1AdminSecurityAuditLogsGet**](SecurityAuditAPI.md#ApiV1AdminSecurityAuditLogsGet) | **Get** /api/v1/admin/security-audit-logs | List security audit logs
[**ApiV1AdminSecurityAuditLogsIdGet**](SecurityAuditAPI.md#ApiV1AdminSecurityAuditLogsIdGet) | **Get** /api/v1/admin/security-audit-logs/{id} | Get security audit log details
[**ApiV1AdminSecurityAuditLogsStatsGet**](SecurityAuditAPI.md#ApiV1AdminSecurityAuditLogsStatsGet) | **Get** /api/v1/admin/security-audit-logs/stats | Get security audit statistics



## ApiV1AdminSecurityAuditLogsGet

> ListLogsAPIResponse ApiV1AdminSecurityAuditLogsGet(ctx).Page(page).PerPage(perPage).EventType(eventType).EventCategory(eventCategory).Severity(severity).ActorUserId(actorUserId).Success(success).StartDate(startDate).EndDate(endDate).Search(search).Execute()

List security audit logs



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
	perPage := int32(56) // int32 | Number of items per page (optional) (default to 50)
	eventType := "eventType_example" // string | Filter by event type (optional)
	eventCategory := "eventCategory_example" // string | Filter by event category (optional)
	severity := "severity_example" // string | Filter by severity (optional)
	actorUserId := "actorUserId_example" // string | Filter by actor user ID (optional)
	success := "success_example" // string | Filter by success status (true/false) (optional)
	startDate := "startDate_example" // string | Filter by start date (RFC3339 format) (optional)
	endDate := "endDate_example" // string | Filter by end date (RFC3339 format) (optional)
	search := "search_example" // string | Search in actor username, target name, or event type (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SecurityAuditAPI.ApiV1AdminSecurityAuditLogsGet(context.Background()).Page(page).PerPage(perPage).EventType(eventType).EventCategory(eventCategory).Severity(severity).ActorUserId(actorUserId).Success(success).StartDate(startDate).EndDate(endDate).Search(search).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SecurityAuditAPI.ApiV1AdminSecurityAuditLogsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminSecurityAuditLogsGet`: ListLogsAPIResponse
	fmt.Fprintf(os.Stdout, "Response from `SecurityAuditAPI.ApiV1AdminSecurityAuditLogsGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AdminSecurityAuditLogsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** | Page number | [default to 1]
 **perPage** | **int32** | Number of items per page | [default to 50]
 **eventType** | **string** | Filter by event type | 
 **eventCategory** | **string** | Filter by event category | 
 **severity** | **string** | Filter by severity | 
 **actorUserId** | **string** | Filter by actor user ID | 
 **success** | **string** | Filter by success status (true/false) | 
 **startDate** | **string** | Filter by start date (RFC3339 format) | 
 **endDate** | **string** | Filter by end date (RFC3339 format) | 
 **search** | **string** | Search in actor username, target name, or event type | 

### Return type

[**ListLogsAPIResponse**](ListLogsAPIResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1AdminSecurityAuditLogsIdGet

> GetLogAPIResponse ApiV1AdminSecurityAuditLogsIdGet(ctx, id).Execute()

Get security audit log details



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
	id := int32(56) // int32 | Security audit log ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SecurityAuditAPI.ApiV1AdminSecurityAuditLogsIdGet(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SecurityAuditAPI.ApiV1AdminSecurityAuditLogsIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminSecurityAuditLogsIdGet`: GetLogAPIResponse
	fmt.Fprintf(os.Stdout, "Response from `SecurityAuditAPI.ApiV1AdminSecurityAuditLogsIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Security audit log ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AdminSecurityAuditLogsIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**GetLogAPIResponse**](GetLogAPIResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1AdminSecurityAuditLogsStatsGet

> GetStatsAPIResponse ApiV1AdminSecurityAuditLogsStatsGet(ctx).Execute()

Get security audit statistics



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
	resp, r, err := apiClient.SecurityAuditAPI.ApiV1AdminSecurityAuditLogsStatsGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SecurityAuditAPI.ApiV1AdminSecurityAuditLogsStatsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminSecurityAuditLogsStatsGet`: GetStatsAPIResponse
	fmt.Fprintf(os.Stdout, "Response from `SecurityAuditAPI.ApiV1AdminSecurityAuditLogsStatsGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AdminSecurityAuditLogsStatsGetRequest struct via the builder pattern


### Return type

[**GetStatsAPIResponse**](GetStatsAPIResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

