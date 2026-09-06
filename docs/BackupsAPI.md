# \BackupsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApiV1AdminServersIdBackupStorageAbandonPost**](BackupsAPI.md#ApiV1AdminServersIdBackupStorageAbandonPost) | **Post** /api/v1/admin/servers/{id}/backup-storage/abandon | Abandon a server&#39;s backup history
[**ApiV1AdminServersIdBackupStorageDeleteAllPost**](BackupsAPI.md#ApiV1AdminServersIdBackupStorageDeleteAllPost) | **Post** /api/v1/admin/servers/{id}/backup-storage/delete-all | Delete every backup for a server
[**ApiV1AdminServersIdBackupStorageGet**](BackupsAPI.md#ApiV1AdminServersIdBackupStorageGet) | **Get** /api/v1/admin/servers/{id}/backup-storage | Read a server&#39;s backup storage history status
[**ApiV1BackupsGet**](BackupsAPI.md#ApiV1BackupsGet) | **Get** /api/v1/backups | List backup coverage across every reachable server
[**ApiV1ServersServeridStacksStacknameBackupsBackupidDelete**](BackupsAPI.md#ApiV1ServersServeridStacksStacknameBackupsBackupidDelete) | **Delete** /api/v1/servers/{serverid}/stacks/{stackname}/backups/{backupid} | Delete a stack backup
[**ApiV1ServersServeridStacksStacknameBackupsBackupidDownloadGet**](BackupsAPI.md#ApiV1ServersServeridStacksStacknameBackupsBackupidDownloadGet) | **Get** /api/v1/servers/{serverid}/stacks/{stackname}/backups/{backupid}/download | Download files from a backup
[**ApiV1ServersServeridStacksStacknameBackupsBackupidFilesGet**](BackupsAPI.md#ApiV1ServersServeridStacksStacknameBackupsBackupidFilesGet) | **Get** /api/v1/servers/{serverid}/stacks/{stackname}/backups/{backupid}/files | List files inside a backup
[**ApiV1ServersServeridStacksStacknameBackupsBackupidGet**](BackupsAPI.md#ApiV1ServersServeridStacksStacknameBackupsBackupidGet) | **Get** /api/v1/servers/{serverid}/stacks/{stackname}/backups/{backupid} | Get a stack backup
[**ApiV1ServersServeridStacksStacknameBackupsGet**](BackupsAPI.md#ApiV1ServersServeridStacksStacknameBackupsGet) | **Get** /api/v1/servers/{serverid}/stacks/{stackname}/backups | List stack backups
[**ApiV1ServersServeridStacksStacknameBackupsRebuildPost**](BackupsAPI.md#ApiV1ServersServeridStacksStacknameBackupsRebuildPost) | **Post** /api/v1/servers/{serverid}/stacks/{stackname}/backups/rebuild | Rebuild a stack&#39;s backup history from its repository



## ApiV1AdminServersIdBackupStorageAbandonPost

> ResponseAbandonBackupStorageResult ApiV1AdminServersIdBackupStorageAbandonPost(ctx, id).Execute()

Abandon a server's backup history



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
	id := int32(56) // int32 | Server ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BackupsAPI.ApiV1AdminServersIdBackupStorageAbandonPost(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BackupsAPI.ApiV1AdminServersIdBackupStorageAbandonPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminServersIdBackupStorageAbandonPost`: ResponseAbandonBackupStorageResult
	fmt.Fprintf(os.Stdout, "Response from `BackupsAPI.ApiV1AdminServersIdBackupStorageAbandonPost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Server ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AdminServersIdBackupStorageAbandonPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ResponseAbandonBackupStorageResult**](ResponseAbandonBackupStorageResult.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1AdminServersIdBackupStorageDeleteAllPost

> ResponseDeleteAllResult ApiV1AdminServersIdBackupStorageDeleteAllPost(ctx, id).Execute()

Delete every backup for a server



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
	id := int32(56) // int32 | Server ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BackupsAPI.ApiV1AdminServersIdBackupStorageDeleteAllPost(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BackupsAPI.ApiV1AdminServersIdBackupStorageDeleteAllPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminServersIdBackupStorageDeleteAllPost`: ResponseDeleteAllResult
	fmt.Fprintf(os.Stdout, "Response from `BackupsAPI.ApiV1AdminServersIdBackupStorageDeleteAllPost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Server ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AdminServersIdBackupStorageDeleteAllPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ResponseDeleteAllResult**](ResponseDeleteAllResult.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1AdminServersIdBackupStorageGet

> ResponseHistoryState ApiV1AdminServersIdBackupStorageGet(ctx, id).Execute()

Read a server's backup storage history status



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
	id := int32(56) // int32 | Server ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BackupsAPI.ApiV1AdminServersIdBackupStorageGet(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BackupsAPI.ApiV1AdminServersIdBackupStorageGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminServersIdBackupStorageGet`: ResponseHistoryState
	fmt.Fprintf(os.Stdout, "Response from `BackupsAPI.ApiV1AdminServersIdBackupStorageGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Server ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AdminServersIdBackupStorageGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ResponseHistoryState**](ResponseHistoryState.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1BackupsGet

> ResponseOverviewResponse ApiV1BackupsGet(ctx).Execute()

List backup coverage across every reachable server



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
	resp, r, err := apiClient.BackupsAPI.ApiV1BackupsGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BackupsAPI.ApiV1BackupsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1BackupsGet`: ResponseOverviewResponse
	fmt.Fprintf(os.Stdout, "Response from `BackupsAPI.ApiV1BackupsGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1BackupsGetRequest struct via the builder pattern


### Return type

[**ResponseOverviewResponse**](ResponseOverviewResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


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


## ApiV1ServersServeridStacksStacknameBackupsBackupidDownloadGet

> *os.File ApiV1ServersServeridStacksStacknameBackupsBackupidDownloadGet(ctx, serverid, stackname, backupid).Component(component).Path(path).Execute()

Download files from a backup



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
	component := "component_example" // string | Backup component ID
	path := "path_example" // string | File or directory to download; repeat for a multi-path selection

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BackupsAPI.ApiV1ServersServeridStacksStacknameBackupsBackupidDownloadGet(context.Background(), serverid, stackname, backupid).Component(component).Path(path).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BackupsAPI.ApiV1ServersServeridStacksStacknameBackupsBackupidDownloadGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridStacksStacknameBackupsBackupidDownloadGet`: *os.File
	fmt.Fprintf(os.Stdout, "Response from `BackupsAPI.ApiV1ServersServeridStacksStacknameBackupsBackupidDownloadGet`: %v\n", resp)
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

Other parameters are passed through a pointer to a apiApiV1ServersServeridStacksStacknameBackupsBackupidDownloadGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **component** | **string** | Backup component ID | 
 **path** | **string** | File or directory to download; repeat for a multi-path selection | 

### Return type

[***os.File**](*os.File.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/octet-stream, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ServersServeridStacksStacknameBackupsBackupidFilesGet

> ResponseBackupFileListing ApiV1ServersServeridStacksStacknameBackupsBackupidFilesGet(ctx, serverid, stackname, backupid).Component(component).Path(path).Execute()

List files inside a backup



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
	component := "component_example" // string | Backup component ID
	path := "path_example" // string | Directory inside the component (default the component root) (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BackupsAPI.ApiV1ServersServeridStacksStacknameBackupsBackupidFilesGet(context.Background(), serverid, stackname, backupid).Component(component).Path(path).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BackupsAPI.ApiV1ServersServeridStacksStacknameBackupsBackupidFilesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridStacksStacknameBackupsBackupidFilesGet`: ResponseBackupFileListing
	fmt.Fprintf(os.Stdout, "Response from `BackupsAPI.ApiV1ServersServeridStacksStacknameBackupsBackupidFilesGet`: %v\n", resp)
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

Other parameters are passed through a pointer to a apiApiV1ServersServeridStacksStacknameBackupsBackupidFilesGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **component** | **string** | Backup component ID | 
 **path** | **string** | Directory inside the component (default the component root) | 

### Return type

[**ResponseBackupFileListing**](ResponseBackupFileListing.md)

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


## ApiV1ServersServeridStacksStacknameBackupsRebuildPost

> ResponseRebuildResult ApiV1ServersServeridStacksStacknameBackupsRebuildPost(ctx, serverid, stackname).Execute()

Rebuild a stack's backup history from its repository



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
	resp, r, err := apiClient.BackupsAPI.ApiV1ServersServeridStacksStacknameBackupsRebuildPost(context.Background(), serverid, stackname).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BackupsAPI.ApiV1ServersServeridStacksStacknameBackupsRebuildPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridStacksStacknameBackupsRebuildPost`: ResponseRebuildResult
	fmt.Fprintf(os.Stdout, "Response from `BackupsAPI.ApiV1ServersServeridStacksStacknameBackupsRebuildPost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 
**stackname** | **string** | Stack name | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridStacksStacknameBackupsRebuildPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**ResponseRebuildResult**](ResponseRebuildResult.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

