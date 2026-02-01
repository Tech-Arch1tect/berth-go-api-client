# \MigrationAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApiV1AdminMigrationExportPost**](MigrationAPI.md#ApiV1AdminMigrationExportPost) | **Post** /api/v1/admin/migration/export | Export data
[**ApiV1AdminMigrationImportPost**](MigrationAPI.md#ApiV1AdminMigrationImportPost) | **Post** /api/v1/admin/migration/import | Import data



## ApiV1AdminMigrationExportPost

> *os.File ApiV1AdminMigrationExportPost(ctx).ExportRequest(exportRequest).Execute()

Export data



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
	exportRequest := *openapiclient.NewExportRequest("Password_example") // ExportRequest | Export password (min 12 characters)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MigrationAPI.ApiV1AdminMigrationExportPost(context.Background()).ExportRequest(exportRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MigrationAPI.ApiV1AdminMigrationExportPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminMigrationExportPost`: *os.File
	fmt.Fprintf(os.Stdout, "Response from `MigrationAPI.ApiV1AdminMigrationExportPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AdminMigrationExportPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **exportRequest** | [**ExportRequest**](ExportRequest.md) | Export password (min 12 characters) | 

### Return type

[***os.File**](*os.File.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/octet-stream, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1AdminMigrationImportPost

> ImportResponse ApiV1AdminMigrationImportPost(ctx).BackupFile(backupFile).Password(password).Execute()

Import data



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
	backupFile := os.NewFile(1234, "some_file") // *os.File | 
	password := "password_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MigrationAPI.ApiV1AdminMigrationImportPost(context.Background()).BackupFile(backupFile).Password(password).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MigrationAPI.ApiV1AdminMigrationImportPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminMigrationImportPost`: ImportResponse
	fmt.Fprintf(os.Stdout, "Response from `MigrationAPI.ApiV1AdminMigrationImportPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AdminMigrationImportPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **backupFile** | ***os.File** |  | 
 **password** | **string** |  | 

### Return type

[**ImportResponse**](ImportResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

