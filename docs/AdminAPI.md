# \AdminAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApiV1AdminMigrationExportPost**](AdminAPI.md#ApiV1AdminMigrationExportPost) | **Post** /api/v1/admin/migration/export | Export data
[**ApiV1AdminMigrationImportPost**](AdminAPI.md#ApiV1AdminMigrationImportPost) | **Post** /api/v1/admin/migration/import | Import data
[**ApiV1AdminOperationLogsGet**](AdminAPI.md#ApiV1AdminOperationLogsGet) | **Get** /api/v1/admin/operation-logs | List all operation logs
[**ApiV1AdminOperationLogsIdGet**](AdminAPI.md#ApiV1AdminOperationLogsIdGet) | **Get** /api/v1/admin/operation-logs/{id} | Get operation log details
[**ApiV1AdminOperationLogsStatsGet**](AdminAPI.md#ApiV1AdminOperationLogsStatsGet) | **Get** /api/v1/admin/operation-logs/stats | Get operation logs statistics
[**ApiV1AdminRolesGet**](AdminAPI.md#ApiV1AdminRolesGet) | **Get** /api/v1/admin/roles | List all roles
[**ApiV1AdminRolesIdDelete**](AdminAPI.md#ApiV1AdminRolesIdDelete) | **Delete** /api/v1/admin/roles/{id} | Delete a role
[**ApiV1AdminRolesIdPut**](AdminAPI.md#ApiV1AdminRolesIdPut) | **Put** /api/v1/admin/roles/{id} | Update a role
[**ApiV1AdminRolesPost**](AdminAPI.md#ApiV1AdminRolesPost) | **Post** /api/v1/admin/roles | Create a new role
[**ApiV1AdminRolesRoleIdStackPermissionsGet**](AdminAPI.md#ApiV1AdminRolesRoleIdStackPermissionsGet) | **Get** /api/v1/admin/roles/{roleId}/stack-permissions | List role stack permissions
[**ApiV1AdminRolesRoleIdStackPermissionsPermissionIdDelete**](AdminAPI.md#ApiV1AdminRolesRoleIdStackPermissionsPermissionIdDelete) | **Delete** /api/v1/admin/roles/{roleId}/stack-permissions/{permissionId} | Delete a role stack permission
[**ApiV1AdminRolesRoleIdStackPermissionsPost**](AdminAPI.md#ApiV1AdminRolesRoleIdStackPermissionsPost) | **Post** /api/v1/admin/roles/{roleId}/stack-permissions | Create a role stack permission
[**ApiV1AdminSecurityAuditLogsGet**](AdminAPI.md#ApiV1AdminSecurityAuditLogsGet) | **Get** /api/v1/admin/security-audit-logs | List security audit logs
[**ApiV1AdminSecurityAuditLogsIdGet**](AdminAPI.md#ApiV1AdminSecurityAuditLogsIdGet) | **Get** /api/v1/admin/security-audit-logs/{id} | Get security audit log details
[**ApiV1AdminSecurityAuditLogsStatsGet**](AdminAPI.md#ApiV1AdminSecurityAuditLogsStatsGet) | **Get** /api/v1/admin/security-audit-logs/stats | Get security audit statistics
[**ApiV1AdminServersGet**](AdminAPI.md#ApiV1AdminServersGet) | **Get** /api/v1/admin/servers | List all servers
[**ApiV1AdminServersIdDelete**](AdminAPI.md#ApiV1AdminServersIdDelete) | **Delete** /api/v1/admin/servers/{id} | Delete a server
[**ApiV1AdminServersIdPut**](AdminAPI.md#ApiV1AdminServersIdPut) | **Put** /api/v1/admin/servers/{id} | Update a server
[**ApiV1AdminServersIdTestPost**](AdminAPI.md#ApiV1AdminServersIdTestPost) | **Post** /api/v1/admin/servers/{id}/test | Test server connection
[**ApiV1AdminServersPost**](AdminAPI.md#ApiV1AdminServersPost) | **Post** /api/v1/admin/servers | Create a new server
[**ApiV1AdminUsersAssignRolePost**](AdminAPI.md#ApiV1AdminUsersAssignRolePost) | **Post** /api/v1/admin/users/assign-role | Assign a role to a user
[**ApiV1AdminUsersGet**](AdminAPI.md#ApiV1AdminUsersGet) | **Get** /api/v1/admin/users | List all users
[**ApiV1AdminUsersIdRolesGet**](AdminAPI.md#ApiV1AdminUsersIdRolesGet) | **Get** /api/v1/admin/users/{id}/roles | Get user with roles
[**ApiV1AdminUsersPost**](AdminAPI.md#ApiV1AdminUsersPost) | **Post** /api/v1/admin/users | Create a new user
[**ApiV1AdminUsersRevokeRolePost**](AdminAPI.md#ApiV1AdminUsersRevokeRolePost) | **Post** /api/v1/admin/users/revoke-role | Revoke a role from a user



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
	resp, r, err := apiClient.AdminAPI.ApiV1AdminMigrationExportPost(context.Background()).ExportRequest(exportRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminAPI.ApiV1AdminMigrationExportPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminMigrationExportPost`: *os.File
	fmt.Fprintf(os.Stdout, "Response from `AdminAPI.ApiV1AdminMigrationExportPost`: %v\n", resp)
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
	resp, r, err := apiClient.AdminAPI.ApiV1AdminMigrationImportPost(context.Background()).BackupFile(backupFile).Password(password).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminAPI.ApiV1AdminMigrationImportPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminMigrationImportPost`: ImportResponse
	fmt.Fprintf(os.Stdout, "Response from `AdminAPI.ApiV1AdminMigrationImportPost`: %v\n", resp)
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


## ApiV1AdminOperationLogsGet

> PaginatedOperationLogsResponse ApiV1AdminOperationLogsGet(ctx).Page(page).PageSize(pageSize).Search(search).ServerId(serverId).StackName(stackName).Command(command).Status(status).DaysBack(daysBack).Execute()

List all operation logs



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
	pageSize := int32(56) // int32 | Number of items per page (optional) (default to 20)
	search := "search_example" // string | Search term for stack name, command, or operation ID (optional)
	serverId := "serverId_example" // string | Filter by server ID (optional)
	stackName := "stackName_example" // string | Filter by stack name (partial match) (optional)
	command := "command_example" // string | Filter by command (optional)
	status := "status_example" // string | Filter by status (optional)
	daysBack := int32(56) // int32 | Only return logs from the last N days (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AdminAPI.ApiV1AdminOperationLogsGet(context.Background()).Page(page).PageSize(pageSize).Search(search).ServerId(serverId).StackName(stackName).Command(command).Status(status).DaysBack(daysBack).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminAPI.ApiV1AdminOperationLogsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminOperationLogsGet`: PaginatedOperationLogsResponse
	fmt.Fprintf(os.Stdout, "Response from `AdminAPI.ApiV1AdminOperationLogsGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AdminOperationLogsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** | Page number | [default to 1]
 **pageSize** | **int32** | Number of items per page | [default to 20]
 **search** | **string** | Search term for stack name, command, or operation ID | 
 **serverId** | **string** | Filter by server ID | 
 **stackName** | **string** | Filter by stack name (partial match) | 
 **command** | **string** | Filter by command | 
 **status** | **string** | Filter by status | 
 **daysBack** | **int32** | Only return logs from the last N days | 

### Return type

[**PaginatedOperationLogsResponse**](PaginatedOperationLogsResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1AdminOperationLogsIdGet

> OperationLogDetailResponse ApiV1AdminOperationLogsIdGet(ctx, id).Execute()

Get operation log details



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
	id := int32(56) // int32 | Operation log ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AdminAPI.ApiV1AdminOperationLogsIdGet(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminAPI.ApiV1AdminOperationLogsIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminOperationLogsIdGet`: OperationLogDetailResponse
	fmt.Fprintf(os.Stdout, "Response from `AdminAPI.ApiV1AdminOperationLogsIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Operation log ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AdminOperationLogsIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**OperationLogDetailResponse**](OperationLogDetailResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1AdminOperationLogsStatsGet

> OperationLogStatsResponse ApiV1AdminOperationLogsStatsGet(ctx).Execute()

Get operation logs statistics



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
	resp, r, err := apiClient.AdminAPI.ApiV1AdminOperationLogsStatsGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminAPI.ApiV1AdminOperationLogsStatsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminOperationLogsStatsGet`: OperationLogStatsResponse
	fmt.Fprintf(os.Stdout, "Response from `AdminAPI.ApiV1AdminOperationLogsStatsGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AdminOperationLogsStatsGetRequest struct via the builder pattern


### Return type

[**OperationLogStatsResponse**](OperationLogStatsResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1AdminRolesGet

> ListRolesResponse ApiV1AdminRolesGet(ctx).Execute()

List all roles



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
	resp, r, err := apiClient.AdminAPI.ApiV1AdminRolesGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminAPI.ApiV1AdminRolesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminRolesGet`: ListRolesResponse
	fmt.Fprintf(os.Stdout, "Response from `AdminAPI.ApiV1AdminRolesGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AdminRolesGetRequest struct via the builder pattern


### Return type

[**ListRolesResponse**](ListRolesResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1AdminRolesIdDelete

> DeleteRoleResponse ApiV1AdminRolesIdDelete(ctx, id).Execute()

Delete a role



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
	id := int32(56) // int32 | Role ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AdminAPI.ApiV1AdminRolesIdDelete(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminAPI.ApiV1AdminRolesIdDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminRolesIdDelete`: DeleteRoleResponse
	fmt.Fprintf(os.Stdout, "Response from `AdminAPI.ApiV1AdminRolesIdDelete`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Role ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AdminRolesIdDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**DeleteRoleResponse**](DeleteRoleResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1AdminRolesIdPut

> UpdateRoleResponse ApiV1AdminRolesIdPut(ctx, id).UpdateRoleRequest(updateRoleRequest).Execute()

Update a role



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
	id := int32(56) // int32 | Role ID
	updateRoleRequest := *openapiclient.NewUpdateRoleRequest("Description_example", "Name_example") // UpdateRoleRequest | Role details

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AdminAPI.ApiV1AdminRolesIdPut(context.Background(), id).UpdateRoleRequest(updateRoleRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminAPI.ApiV1AdminRolesIdPut``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminRolesIdPut`: UpdateRoleResponse
	fmt.Fprintf(os.Stdout, "Response from `AdminAPI.ApiV1AdminRolesIdPut`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Role ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AdminRolesIdPutRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateRoleRequest** | [**UpdateRoleRequest**](UpdateRoleRequest.md) | Role details | 

### Return type

[**UpdateRoleResponse**](UpdateRoleResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1AdminRolesPost

> CreateRoleResponse ApiV1AdminRolesPost(ctx).CreateRoleRequest(createRoleRequest).Execute()

Create a new role



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
	createRoleRequest := *openapiclient.NewCreateRoleRequest("Description_example", "Name_example") // CreateRoleRequest | Role details

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AdminAPI.ApiV1AdminRolesPost(context.Background()).CreateRoleRequest(createRoleRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminAPI.ApiV1AdminRolesPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminRolesPost`: CreateRoleResponse
	fmt.Fprintf(os.Stdout, "Response from `AdminAPI.ApiV1AdminRolesPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AdminRolesPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createRoleRequest** | [**CreateRoleRequest**](CreateRoleRequest.md) | Role details | 

### Return type

[**CreateRoleResponse**](CreateRoleResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1AdminRolesRoleIdStackPermissionsGet

> ListRoleStackPermissionsResponse ApiV1AdminRolesRoleIdStackPermissionsGet(ctx, roleId).Execute()

List role stack permissions



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
	roleId := int32(56) // int32 | Role ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AdminAPI.ApiV1AdminRolesRoleIdStackPermissionsGet(context.Background(), roleId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminAPI.ApiV1AdminRolesRoleIdStackPermissionsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminRolesRoleIdStackPermissionsGet`: ListRoleStackPermissionsResponse
	fmt.Fprintf(os.Stdout, "Response from `AdminAPI.ApiV1AdminRolesRoleIdStackPermissionsGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**roleId** | **int32** | Role ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AdminRolesRoleIdStackPermissionsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ListRoleStackPermissionsResponse**](ListRoleStackPermissionsResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1AdminRolesRoleIdStackPermissionsPermissionIdDelete

> DeleteStackPermissionResponse ApiV1AdminRolesRoleIdStackPermissionsPermissionIdDelete(ctx, roleId, permissionId).Execute()

Delete a role stack permission



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
	roleId := int32(56) // int32 | Role ID
	permissionId := int32(56) // int32 | Permission rule ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AdminAPI.ApiV1AdminRolesRoleIdStackPermissionsPermissionIdDelete(context.Background(), roleId, permissionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminAPI.ApiV1AdminRolesRoleIdStackPermissionsPermissionIdDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminRolesRoleIdStackPermissionsPermissionIdDelete`: DeleteStackPermissionResponse
	fmt.Fprintf(os.Stdout, "Response from `AdminAPI.ApiV1AdminRolesRoleIdStackPermissionsPermissionIdDelete`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**roleId** | **int32** | Role ID | 
**permissionId** | **int32** | Permission rule ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AdminRolesRoleIdStackPermissionsPermissionIdDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**DeleteStackPermissionResponse**](DeleteStackPermissionResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1AdminRolesRoleIdStackPermissionsPost

> CreateStackPermissionResponse ApiV1AdminRolesRoleIdStackPermissionsPost(ctx, roleId).CreateStackPermissionRequest(createStackPermissionRequest).Execute()

Create a role stack permission



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
	roleId := int32(56) // int32 | Role ID
	createStackPermissionRequest := *openapiclient.NewCreateStackPermissionRequest(int32(123), int32(123), "StackPattern_example") // CreateStackPermissionRequest | Permission rule details

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AdminAPI.ApiV1AdminRolesRoleIdStackPermissionsPost(context.Background(), roleId).CreateStackPermissionRequest(createStackPermissionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminAPI.ApiV1AdminRolesRoleIdStackPermissionsPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminRolesRoleIdStackPermissionsPost`: CreateStackPermissionResponse
	fmt.Fprintf(os.Stdout, "Response from `AdminAPI.ApiV1AdminRolesRoleIdStackPermissionsPost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**roleId** | **int32** | Role ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AdminRolesRoleIdStackPermissionsPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createStackPermissionRequest** | [**CreateStackPermissionRequest**](CreateStackPermissionRequest.md) | Permission rule details | 

### Return type

[**CreateStackPermissionResponse**](CreateStackPermissionResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


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
	resp, r, err := apiClient.AdminAPI.ApiV1AdminSecurityAuditLogsGet(context.Background()).Page(page).PerPage(perPage).EventType(eventType).EventCategory(eventCategory).Severity(severity).ActorUserId(actorUserId).Success(success).StartDate(startDate).EndDate(endDate).Search(search).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminAPI.ApiV1AdminSecurityAuditLogsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminSecurityAuditLogsGet`: ListLogsAPIResponse
	fmt.Fprintf(os.Stdout, "Response from `AdminAPI.ApiV1AdminSecurityAuditLogsGet`: %v\n", resp)
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
	resp, r, err := apiClient.AdminAPI.ApiV1AdminSecurityAuditLogsIdGet(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminAPI.ApiV1AdminSecurityAuditLogsIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminSecurityAuditLogsIdGet`: GetLogAPIResponse
	fmt.Fprintf(os.Stdout, "Response from `AdminAPI.ApiV1AdminSecurityAuditLogsIdGet`: %v\n", resp)
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
	resp, r, err := apiClient.AdminAPI.ApiV1AdminSecurityAuditLogsStatsGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminAPI.ApiV1AdminSecurityAuditLogsStatsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminSecurityAuditLogsStatsGet`: GetStatsAPIResponse
	fmt.Fprintf(os.Stdout, "Response from `AdminAPI.ApiV1AdminSecurityAuditLogsStatsGet`: %v\n", resp)
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


## ApiV1AdminServersGet

> AdminListServersResponse ApiV1AdminServersGet(ctx).Execute()

List all servers



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
	resp, r, err := apiClient.AdminAPI.ApiV1AdminServersGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminAPI.ApiV1AdminServersGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminServersGet`: AdminListServersResponse
	fmt.Fprintf(os.Stdout, "Response from `AdminAPI.ApiV1AdminServersGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AdminServersGetRequest struct via the builder pattern


### Return type

[**AdminListServersResponse**](AdminListServersResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1AdminServersIdDelete

> AdminDeleteServerResponse ApiV1AdminServersIdDelete(ctx, id).Execute()

Delete a server



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
	resp, r, err := apiClient.AdminAPI.ApiV1AdminServersIdDelete(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminAPI.ApiV1AdminServersIdDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminServersIdDelete`: AdminDeleteServerResponse
	fmt.Fprintf(os.Stdout, "Response from `AdminAPI.ApiV1AdminServersIdDelete`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Server ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AdminServersIdDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AdminDeleteServerResponse**](AdminDeleteServerResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1AdminServersIdPut

> AdminUpdateServerResponse ApiV1AdminServersIdPut(ctx, id).ServerUpdateRequest(serverUpdateRequest).Execute()

Update a server



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
	serverUpdateRequest := *openapiclient.NewServerUpdateRequest("AccessToken_example", "Description_example", "Host_example", false, "Name_example", int32(123), false) // ServerUpdateRequest | Server details

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AdminAPI.ApiV1AdminServersIdPut(context.Background(), id).ServerUpdateRequest(serverUpdateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminAPI.ApiV1AdminServersIdPut``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminServersIdPut`: AdminUpdateServerResponse
	fmt.Fprintf(os.Stdout, "Response from `AdminAPI.ApiV1AdminServersIdPut`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Server ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AdminServersIdPutRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **serverUpdateRequest** | [**ServerUpdateRequest**](ServerUpdateRequest.md) | Server details | 

### Return type

[**AdminUpdateServerResponse**](AdminUpdateServerResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1AdminServersIdTestPost

> AdminTestConnectionResponse ApiV1AdminServersIdTestPost(ctx, id).Execute()

Test server connection



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
	resp, r, err := apiClient.AdminAPI.ApiV1AdminServersIdTestPost(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminAPI.ApiV1AdminServersIdTestPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminServersIdTestPost`: AdminTestConnectionResponse
	fmt.Fprintf(os.Stdout, "Response from `AdminAPI.ApiV1AdminServersIdTestPost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Server ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AdminServersIdTestPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AdminTestConnectionResponse**](AdminTestConnectionResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1AdminServersPost

> AdminCreateServerResponse ApiV1AdminServersPost(ctx).ServerCreateRequest(serverCreateRequest).Execute()

Create a new server



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
	serverCreateRequest := *openapiclient.NewServerCreateRequest("AccessToken_example", "Description_example", "Host_example", false, "Name_example", int32(123), false) // ServerCreateRequest | Server details

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AdminAPI.ApiV1AdminServersPost(context.Background()).ServerCreateRequest(serverCreateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminAPI.ApiV1AdminServersPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminServersPost`: AdminCreateServerResponse
	fmt.Fprintf(os.Stdout, "Response from `AdminAPI.ApiV1AdminServersPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AdminServersPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **serverCreateRequest** | [**ServerCreateRequest**](ServerCreateRequest.md) | Server details | 

### Return type

[**AdminCreateServerResponse**](AdminCreateServerResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1AdminUsersAssignRolePost

> AssignRoleResponse ApiV1AdminUsersAssignRolePost(ctx).AssignRoleRequest(assignRoleRequest).Execute()

Assign a role to a user



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
	assignRoleRequest := *openapiclient.NewAssignRoleRequest(int32(123), int32(123)) // AssignRoleRequest | User and role IDs

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AdminAPI.ApiV1AdminUsersAssignRolePost(context.Background()).AssignRoleRequest(assignRoleRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminAPI.ApiV1AdminUsersAssignRolePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminUsersAssignRolePost`: AssignRoleResponse
	fmt.Fprintf(os.Stdout, "Response from `AdminAPI.ApiV1AdminUsersAssignRolePost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AdminUsersAssignRolePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **assignRoleRequest** | [**AssignRoleRequest**](AssignRoleRequest.md) | User and role IDs | 

### Return type

[**AssignRoleResponse**](AssignRoleResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1AdminUsersGet

> ListUsersResponse ApiV1AdminUsersGet(ctx).Execute()

List all users



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
	resp, r, err := apiClient.AdminAPI.ApiV1AdminUsersGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminAPI.ApiV1AdminUsersGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminUsersGet`: ListUsersResponse
	fmt.Fprintf(os.Stdout, "Response from `AdminAPI.ApiV1AdminUsersGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AdminUsersGetRequest struct via the builder pattern


### Return type

[**ListUsersResponse**](ListUsersResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1AdminUsersIdRolesGet

> GetUserRolesResponse ApiV1AdminUsersIdRolesGet(ctx, id).Execute()

Get user with roles



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
	id := int32(56) // int32 | User ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AdminAPI.ApiV1AdminUsersIdRolesGet(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminAPI.ApiV1AdminUsersIdRolesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminUsersIdRolesGet`: GetUserRolesResponse
	fmt.Fprintf(os.Stdout, "Response from `AdminAPI.ApiV1AdminUsersIdRolesGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | User ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AdminUsersIdRolesGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**GetUserRolesResponse**](GetUserRolesResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1AdminUsersPost

> CreateUserResponse ApiV1AdminUsersPost(ctx).CreateUserRequest(createUserRequest).Execute()

Create a new user



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
	createUserRequest := *openapiclient.NewCreateUserRequest("Email_example", "Password_example", "PasswordConfirm_example", "Username_example") // CreateUserRequest | User details

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AdminAPI.ApiV1AdminUsersPost(context.Background()).CreateUserRequest(createUserRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminAPI.ApiV1AdminUsersPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminUsersPost`: CreateUserResponse
	fmt.Fprintf(os.Stdout, "Response from `AdminAPI.ApiV1AdminUsersPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AdminUsersPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createUserRequest** | [**CreateUserRequest**](CreateUserRequest.md) | User details | 

### Return type

[**CreateUserResponse**](CreateUserResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1AdminUsersRevokeRolePost

> RevokeRoleResponse ApiV1AdminUsersRevokeRolePost(ctx).RevokeRoleRequest(revokeRoleRequest).Execute()

Revoke a role from a user



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
	revokeRoleRequest := *openapiclient.NewRevokeRoleRequest(int32(123), int32(123)) // RevokeRoleRequest | User and role IDs

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AdminAPI.ApiV1AdminUsersRevokeRolePost(context.Background()).RevokeRoleRequest(revokeRoleRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminAPI.ApiV1AdminUsersRevokeRolePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminUsersRevokeRolePost`: RevokeRoleResponse
	fmt.Fprintf(os.Stdout, "Response from `AdminAPI.ApiV1AdminUsersRevokeRolePost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AdminUsersRevokeRolePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **revokeRoleRequest** | [**RevokeRoleRequest**](RevokeRoleRequest.md) | User and role IDs | 

### Return type

[**RevokeRoleResponse**](RevokeRoleResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

