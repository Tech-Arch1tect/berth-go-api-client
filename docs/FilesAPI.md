# \FilesAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApiV1ServersServeridStacksStacknameFilesChmodPost**](FilesAPI.md#ApiV1ServersServeridStacksStacknameFilesChmodPost) | **Post** /api/v1/servers/{serverid}/stacks/{stackname}/files/chmod | Change file permissions
[**ApiV1ServersServeridStacksStacknameFilesChownPost**](FilesAPI.md#ApiV1ServersServeridStacksStacknameFilesChownPost) | **Post** /api/v1/servers/{serverid}/stacks/{stackname}/files/chown | Change file ownership
[**ApiV1ServersServeridStacksStacknameFilesCopyPost**](FilesAPI.md#ApiV1ServersServeridStacksStacknameFilesCopyPost) | **Post** /api/v1/servers/{serverid}/stacks/{stackname}/files/copy | Copy file or directory
[**ApiV1ServersServeridStacksStacknameFilesDeleteDelete**](FilesAPI.md#ApiV1ServersServeridStacksStacknameFilesDeleteDelete) | **Delete** /api/v1/servers/{serverid}/stacks/{stackname}/files/delete | Delete file or directory
[**ApiV1ServersServeridStacksStacknameFilesDownloadGet**](FilesAPI.md#ApiV1ServersServeridStacksStacknameFilesDownloadGet) | **Get** /api/v1/servers/{serverid}/stacks/{stackname}/files/download | Download a file
[**ApiV1ServersServeridStacksStacknameFilesGet**](FilesAPI.md#ApiV1ServersServeridStacksStacknameFilesGet) | **Get** /api/v1/servers/{serverid}/stacks/{stackname}/files | List directory contents
[**ApiV1ServersServeridStacksStacknameFilesMkdirPost**](FilesAPI.md#ApiV1ServersServeridStacksStacknameFilesMkdirPost) | **Post** /api/v1/servers/{serverid}/stacks/{stackname}/files/mkdir | Create directory
[**ApiV1ServersServeridStacksStacknameFilesReadGet**](FilesAPI.md#ApiV1ServersServeridStacksStacknameFilesReadGet) | **Get** /api/v1/servers/{serverid}/stacks/{stackname}/files/read | Read file contents
[**ApiV1ServersServeridStacksStacknameFilesRenamePost**](FilesAPI.md#ApiV1ServersServeridStacksStacknameFilesRenamePost) | **Post** /api/v1/servers/{serverid}/stacks/{stackname}/files/rename | Rename file or directory
[**ApiV1ServersServeridStacksStacknameFilesStatsGet**](FilesAPI.md#ApiV1ServersServeridStacksStacknameFilesStatsGet) | **Get** /api/v1/servers/{serverid}/stacks/{stackname}/files/stats | Get directory statistics
[**ApiV1ServersServeridStacksStacknameFilesUploadPost**](FilesAPI.md#ApiV1ServersServeridStacksStacknameFilesUploadPost) | **Post** /api/v1/servers/{serverid}/stacks/{stackname}/files/upload | Upload a file
[**ApiV1ServersServeridStacksStacknameFilesWritePost**](FilesAPI.md#ApiV1ServersServeridStacksStacknameFilesWritePost) | **Post** /api/v1/servers/{serverid}/stacks/{stackname}/files/write | Write file contents



## ApiV1ServersServeridStacksStacknameFilesChmodPost

> FileMessageResponse ApiV1ServersServeridStacksStacknameFilesChmodPost(ctx, serverid, stackname).ChmodRequest(chmodRequest).Execute()

Change file permissions



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
	chmodRequest := *openapiclient.NewChmodRequest("Mode_example", "Path_example") // ChmodRequest | Chmod request

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FilesAPI.ApiV1ServersServeridStacksStacknameFilesChmodPost(context.Background(), serverid, stackname).ChmodRequest(chmodRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FilesAPI.ApiV1ServersServeridStacksStacknameFilesChmodPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridStacksStacknameFilesChmodPost`: FileMessageResponse
	fmt.Fprintf(os.Stdout, "Response from `FilesAPI.ApiV1ServersServeridStacksStacknameFilesChmodPost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 
**stackname** | **string** | Stack name | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridStacksStacknameFilesChmodPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **chmodRequest** | [**ChmodRequest**](ChmodRequest.md) | Chmod request | 

### Return type

[**FileMessageResponse**](FileMessageResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ServersServeridStacksStacknameFilesChownPost

> FileMessageResponse ApiV1ServersServeridStacksStacknameFilesChownPost(ctx, serverid, stackname).ChownRequest(chownRequest).Execute()

Change file ownership



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
	chownRequest := *openapiclient.NewChownRequest("Path_example") // ChownRequest | Chown request

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FilesAPI.ApiV1ServersServeridStacksStacknameFilesChownPost(context.Background(), serverid, stackname).ChownRequest(chownRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FilesAPI.ApiV1ServersServeridStacksStacknameFilesChownPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridStacksStacknameFilesChownPost`: FileMessageResponse
	fmt.Fprintf(os.Stdout, "Response from `FilesAPI.ApiV1ServersServeridStacksStacknameFilesChownPost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 
**stackname** | **string** | Stack name | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridStacksStacknameFilesChownPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **chownRequest** | [**ChownRequest**](ChownRequest.md) | Chown request | 

### Return type

[**FileMessageResponse**](FileMessageResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ServersServeridStacksStacknameFilesCopyPost

> FileMessageResponse ApiV1ServersServeridStacksStacknameFilesCopyPost(ctx, serverid, stackname).CopyRequest(copyRequest).Execute()

Copy file or directory



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
	copyRequest := *openapiclient.NewCopyRequest("SourcePath_example", "TargetPath_example") // CopyRequest | Copy request

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FilesAPI.ApiV1ServersServeridStacksStacknameFilesCopyPost(context.Background(), serverid, stackname).CopyRequest(copyRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FilesAPI.ApiV1ServersServeridStacksStacknameFilesCopyPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridStacksStacknameFilesCopyPost`: FileMessageResponse
	fmt.Fprintf(os.Stdout, "Response from `FilesAPI.ApiV1ServersServeridStacksStacknameFilesCopyPost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 
**stackname** | **string** | Stack name | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridStacksStacknameFilesCopyPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **copyRequest** | [**CopyRequest**](CopyRequest.md) | Copy request | 

### Return type

[**FileMessageResponse**](FileMessageResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ServersServeridStacksStacknameFilesDeleteDelete

> FileMessageResponse ApiV1ServersServeridStacksStacknameFilesDeleteDelete(ctx, serverid, stackname).DeleteRequest2(deleteRequest2).Execute()

Delete file or directory



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
	deleteRequest2 := *openapiclient.NewDeleteRequest2("Path_example") // DeleteRequest2 | Delete request

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FilesAPI.ApiV1ServersServeridStacksStacknameFilesDeleteDelete(context.Background(), serverid, stackname).DeleteRequest2(deleteRequest2).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FilesAPI.ApiV1ServersServeridStacksStacknameFilesDeleteDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridStacksStacknameFilesDeleteDelete`: FileMessageResponse
	fmt.Fprintf(os.Stdout, "Response from `FilesAPI.ApiV1ServersServeridStacksStacknameFilesDeleteDelete`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 
**stackname** | **string** | Stack name | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridStacksStacknameFilesDeleteDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **deleteRequest2** | [**DeleteRequest2**](DeleteRequest2.md) | Delete request | 

### Return type

[**FileMessageResponse**](FileMessageResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ServersServeridStacksStacknameFilesDownloadGet

> *os.File ApiV1ServersServeridStacksStacknameFilesDownloadGet(ctx, serverid, stackname).FilePath(filePath).Filename(filename).Execute()

Download a file



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
	filePath := "filePath_example" // string | File path to download
	filename := "filename_example" // string | Optional filename for the downloaded file (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FilesAPI.ApiV1ServersServeridStacksStacknameFilesDownloadGet(context.Background(), serverid, stackname).FilePath(filePath).Filename(filename).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FilesAPI.ApiV1ServersServeridStacksStacknameFilesDownloadGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridStacksStacknameFilesDownloadGet`: *os.File
	fmt.Fprintf(os.Stdout, "Response from `FilesAPI.ApiV1ServersServeridStacksStacknameFilesDownloadGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 
**stackname** | **string** | Stack name | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridStacksStacknameFilesDownloadGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **filePath** | **string** | File path to download | 
 **filename** | **string** | Optional filename for the downloaded file | 

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


## ApiV1ServersServeridStacksStacknameFilesGet

> DirectoryListingResponse ApiV1ServersServeridStacksStacknameFilesGet(ctx, serverid, stackname).FilePath(filePath).Execute()

List directory contents



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
	filePath := "filePath_example" // string | Directory path to list (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FilesAPI.ApiV1ServersServeridStacksStacknameFilesGet(context.Background(), serverid, stackname).FilePath(filePath).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FilesAPI.ApiV1ServersServeridStacksStacknameFilesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridStacksStacknameFilesGet`: DirectoryListingResponse
	fmt.Fprintf(os.Stdout, "Response from `FilesAPI.ApiV1ServersServeridStacksStacknameFilesGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 
**stackname** | **string** | Stack name | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridStacksStacknameFilesGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **filePath** | **string** | Directory path to list | 

### Return type

[**DirectoryListingResponse**](DirectoryListingResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ServersServeridStacksStacknameFilesMkdirPost

> FileMessageResponse ApiV1ServersServeridStacksStacknameFilesMkdirPost(ctx, serverid, stackname).CreateDirectoryRequest(createDirectoryRequest).Execute()

Create directory



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
	createDirectoryRequest := *openapiclient.NewCreateDirectoryRequest("Path_example") // CreateDirectoryRequest | Directory creation request

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FilesAPI.ApiV1ServersServeridStacksStacknameFilesMkdirPost(context.Background(), serverid, stackname).CreateDirectoryRequest(createDirectoryRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FilesAPI.ApiV1ServersServeridStacksStacknameFilesMkdirPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridStacksStacknameFilesMkdirPost`: FileMessageResponse
	fmt.Fprintf(os.Stdout, "Response from `FilesAPI.ApiV1ServersServeridStacksStacknameFilesMkdirPost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 
**stackname** | **string** | Stack name | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridStacksStacknameFilesMkdirPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **createDirectoryRequest** | [**CreateDirectoryRequest**](CreateDirectoryRequest.md) | Directory creation request | 

### Return type

[**FileMessageResponse**](FileMessageResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ServersServeridStacksStacknameFilesReadGet

> FileContentResponse ApiV1ServersServeridStacksStacknameFilesReadGet(ctx, serverid, stackname).FilePath(filePath).Execute()

Read file contents



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
	filePath := "filePath_example" // string | File path to read

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FilesAPI.ApiV1ServersServeridStacksStacknameFilesReadGet(context.Background(), serverid, stackname).FilePath(filePath).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FilesAPI.ApiV1ServersServeridStacksStacknameFilesReadGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridStacksStacknameFilesReadGet`: FileContentResponse
	fmt.Fprintf(os.Stdout, "Response from `FilesAPI.ApiV1ServersServeridStacksStacknameFilesReadGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 
**stackname** | **string** | Stack name | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridStacksStacknameFilesReadGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **filePath** | **string** | File path to read | 

### Return type

[**FileContentResponse**](FileContentResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ServersServeridStacksStacknameFilesRenamePost

> FileMessageResponse ApiV1ServersServeridStacksStacknameFilesRenamePost(ctx, serverid, stackname).RenameRequest(renameRequest).Execute()

Rename file or directory



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
	renameRequest := *openapiclient.NewRenameRequest("NewPath_example", "OldPath_example") // RenameRequest | Rename request

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FilesAPI.ApiV1ServersServeridStacksStacknameFilesRenamePost(context.Background(), serverid, stackname).RenameRequest(renameRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FilesAPI.ApiV1ServersServeridStacksStacknameFilesRenamePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridStacksStacknameFilesRenamePost`: FileMessageResponse
	fmt.Fprintf(os.Stdout, "Response from `FilesAPI.ApiV1ServersServeridStacksStacknameFilesRenamePost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 
**stackname** | **string** | Stack name | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridStacksStacknameFilesRenamePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **renameRequest** | [**RenameRequest**](RenameRequest.md) | Rename request | 

### Return type

[**FileMessageResponse**](FileMessageResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ServersServeridStacksStacknameFilesStatsGet

> DirectoryStatsResponse ApiV1ServersServeridStacksStacknameFilesStatsGet(ctx, serverid, stackname).FilePath(filePath).Execute()

Get directory statistics



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
	filePath := "filePath_example" // string | Directory path (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FilesAPI.ApiV1ServersServeridStacksStacknameFilesStatsGet(context.Background(), serverid, stackname).FilePath(filePath).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FilesAPI.ApiV1ServersServeridStacksStacknameFilesStatsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridStacksStacknameFilesStatsGet`: DirectoryStatsResponse
	fmt.Fprintf(os.Stdout, "Response from `FilesAPI.ApiV1ServersServeridStacksStacknameFilesStatsGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 
**stackname** | **string** | Stack name | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridStacksStacknameFilesStatsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **filePath** | **string** | Directory path | 

### Return type

[**DirectoryStatsResponse**](DirectoryStatsResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ServersServeridStacksStacknameFilesUploadPost

> FileMessageResponse ApiV1ServersServeridStacksStacknameFilesUploadPost(ctx, serverid, stackname).File(file).FilePath(filePath).Execute()

Upload a file



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
	file := os.NewFile(1234, "some_file") // *os.File | 
	filePath := "filePath_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FilesAPI.ApiV1ServersServeridStacksStacknameFilesUploadPost(context.Background(), serverid, stackname).File(file).FilePath(filePath).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FilesAPI.ApiV1ServersServeridStacksStacknameFilesUploadPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridStacksStacknameFilesUploadPost`: FileMessageResponse
	fmt.Fprintf(os.Stdout, "Response from `FilesAPI.ApiV1ServersServeridStacksStacknameFilesUploadPost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 
**stackname** | **string** | Stack name | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridStacksStacknameFilesUploadPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **file** | ***os.File** |  | 
 **filePath** | **string** |  | 

### Return type

[**FileMessageResponse**](FileMessageResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ServersServeridStacksStacknameFilesWritePost

> FileMessageResponse ApiV1ServersServeridStacksStacknameFilesWritePost(ctx, serverid, stackname).WriteFileRequest(writeFileRequest).Execute()

Write file contents



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
	writeFileRequest := *openapiclient.NewWriteFileRequest("Content_example", "Path_example") // WriteFileRequest | File write request

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FilesAPI.ApiV1ServersServeridStacksStacknameFilesWritePost(context.Background(), serverid, stackname).WriteFileRequest(writeFileRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FilesAPI.ApiV1ServersServeridStacksStacknameFilesWritePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridStacksStacknameFilesWritePost`: FileMessageResponse
	fmt.Fprintf(os.Stdout, "Response from `FilesAPI.ApiV1ServersServeridStacksStacknameFilesWritePost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 
**stackname** | **string** | Stack name | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridStacksStacknameFilesWritePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **writeFileRequest** | [**WriteFileRequest**](WriteFileRequest.md) | File write request | 

### Return type

[**FileMessageResponse**](FileMessageResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

