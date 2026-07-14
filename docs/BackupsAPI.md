# \BackupsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApiV1ServersServeridStacksStacknameBackupsBackupidDelete**](BackupsAPI.md#ApiV1ServersServeridStacksStacknameBackupsBackupidDelete) | **Delete** /api/v1/servers/{serverid}/stacks/{stackname}/backups/{backupid} | Delete a stack backup
[**ApiV1ServersServeridStacksStacknameBackupsBackupidGet**](BackupsAPI.md#ApiV1ServersServeridStacksStacknameBackupsBackupidGet) | **Get** /api/v1/servers/{serverid}/stacks/{stackname}/backups/{backupid} | Get a stack backup
[**ApiV1ServersServeridStacksStacknameBackupsGet**](BackupsAPI.md#ApiV1ServersServeridStacksStacknameBackupsGet) | **Get** /api/v1/servers/{serverid}/stacks/{stackname}/backups | List stack backups



## ApiV1ServersServeridStacksStacknameBackupsBackupidDelete

> ResponseDeleteResponse ApiV1ServersServeridStacksStacknameBackupsBackupidDelete(ctx, serverid, stackname, backupid).Execute()

Delete a stack backup



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
	backupid := "backupid_example" // string | Backup run ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BackupsAPI.ApiV1ServersServeridStacksStacknameBackupsBackupidDelete(context.Background(), serverid, stackname, backupid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BackupsAPI.ApiV1ServersServeridStacksStacknameBackupsBackupidDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridStacksStacknameBackupsBackupidDelete`: ResponseDeleteResponse
	fmt.Fprintf(os.Stdout, "Response from `BackupsAPI.ApiV1ServersServeridStacksStacknameBackupsBackupidDelete`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 
**stackname** | **string** | Stack name | 
**backupid** | **string** | Backup run ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridStacksStacknameBackupsBackupidDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------




### Return type

[**ResponseDeleteResponse**](ResponseDeleteResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ServersServeridStacksStacknameBackupsBackupidGet

> ResponseRun ApiV1ServersServeridStacksStacknameBackupsBackupidGet(ctx, serverid, stackname, backupid).Execute()

Get a stack backup



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
	backupid := "backupid_example" // string | Backup run ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BackupsAPI.ApiV1ServersServeridStacksStacknameBackupsBackupidGet(context.Background(), serverid, stackname, backupid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BackupsAPI.ApiV1ServersServeridStacksStacknameBackupsBackupidGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridStacksStacknameBackupsBackupidGet`: ResponseRun
	fmt.Fprintf(os.Stdout, "Response from `BackupsAPI.ApiV1ServersServeridStacksStacknameBackupsBackupidGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 
**stackname** | **string** | Stack name | 
**backupid** | **string** | Backup run ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridStacksStacknameBackupsBackupidGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------




### Return type

[**ResponseRun**](ResponseRun.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ServersServeridStacksStacknameBackupsGet

> ResponseListResponse ApiV1ServersServeridStacksStacknameBackupsGet(ctx, serverid, stackname).Limit(limit).Offset(offset).Execute()

List stack backups



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
	limit := int32(56) // int32 | Page size (default 20, maximum 100) (optional)
	offset := int32(56) // int32 | Number of runs to skip (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BackupsAPI.ApiV1ServersServeridStacksStacknameBackupsGet(context.Background(), serverid, stackname).Limit(limit).Offset(offset).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BackupsAPI.ApiV1ServersServeridStacksStacknameBackupsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridStacksStacknameBackupsGet`: ResponseListResponse
	fmt.Fprintf(os.Stdout, "Response from `BackupsAPI.ApiV1ServersServeridStacksStacknameBackupsGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 
**stackname** | **string** | Stack name | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridStacksStacknameBackupsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **limit** | **int32** | Page size (default 20, maximum 100) | 
 **offset** | **int32** | Number of runs to skip | 

### Return type

[**ResponseListResponse**](ResponseListResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

