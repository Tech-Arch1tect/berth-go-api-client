# \RolesAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApiV1AdminRolesGet**](RolesAPI.md#ApiV1AdminRolesGet) | **Get** /api/v1/admin/roles | List all roles
[**ApiV1AdminRolesIdDelete**](RolesAPI.md#ApiV1AdminRolesIdDelete) | **Delete** /api/v1/admin/roles/{id} | Delete a role
[**ApiV1AdminRolesIdPut**](RolesAPI.md#ApiV1AdminRolesIdPut) | **Put** /api/v1/admin/roles/{id} | Update a role
[**ApiV1AdminRolesPost**](RolesAPI.md#ApiV1AdminRolesPost) | **Post** /api/v1/admin/roles | Create a new role
[**ApiV1AdminRolesRoleIdStackPermissionsGet**](RolesAPI.md#ApiV1AdminRolesRoleIdStackPermissionsGet) | **Get** /api/v1/admin/roles/{roleId}/stack-permissions | List role stack permissions
[**ApiV1AdminRolesRoleIdStackPermissionsPermissionIdDelete**](RolesAPI.md#ApiV1AdminRolesRoleIdStackPermissionsPermissionIdDelete) | **Delete** /api/v1/admin/roles/{roleId}/stack-permissions/{permissionId} | Delete a role stack permission
[**ApiV1AdminRolesRoleIdStackPermissionsPost**](RolesAPI.md#ApiV1AdminRolesRoleIdStackPermissionsPost) | **Post** /api/v1/admin/roles/{roleId}/stack-permissions | Create a role stack permission



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
	resp, r, err := apiClient.RolesAPI.ApiV1AdminRolesGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RolesAPI.ApiV1AdminRolesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminRolesGet`: ListRolesResponse
	fmt.Fprintf(os.Stdout, "Response from `RolesAPI.ApiV1AdminRolesGet`: %v\n", resp)
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
	resp, r, err := apiClient.RolesAPI.ApiV1AdminRolesIdDelete(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RolesAPI.ApiV1AdminRolesIdDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminRolesIdDelete`: DeleteRoleResponse
	fmt.Fprintf(os.Stdout, "Response from `RolesAPI.ApiV1AdminRolesIdDelete`: %v\n", resp)
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
	resp, r, err := apiClient.RolesAPI.ApiV1AdminRolesIdPut(context.Background(), id).UpdateRoleRequest(updateRoleRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RolesAPI.ApiV1AdminRolesIdPut``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminRolesIdPut`: UpdateRoleResponse
	fmt.Fprintf(os.Stdout, "Response from `RolesAPI.ApiV1AdminRolesIdPut`: %v\n", resp)
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
	resp, r, err := apiClient.RolesAPI.ApiV1AdminRolesPost(context.Background()).CreateRoleRequest(createRoleRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RolesAPI.ApiV1AdminRolesPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminRolesPost`: CreateRoleResponse
	fmt.Fprintf(os.Stdout, "Response from `RolesAPI.ApiV1AdminRolesPost`: %v\n", resp)
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
	resp, r, err := apiClient.RolesAPI.ApiV1AdminRolesRoleIdStackPermissionsGet(context.Background(), roleId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RolesAPI.ApiV1AdminRolesRoleIdStackPermissionsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminRolesRoleIdStackPermissionsGet`: ListRoleStackPermissionsResponse
	fmt.Fprintf(os.Stdout, "Response from `RolesAPI.ApiV1AdminRolesRoleIdStackPermissionsGet`: %v\n", resp)
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
	resp, r, err := apiClient.RolesAPI.ApiV1AdminRolesRoleIdStackPermissionsPermissionIdDelete(context.Background(), roleId, permissionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RolesAPI.ApiV1AdminRolesRoleIdStackPermissionsPermissionIdDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminRolesRoleIdStackPermissionsPermissionIdDelete`: DeleteStackPermissionResponse
	fmt.Fprintf(os.Stdout, "Response from `RolesAPI.ApiV1AdminRolesRoleIdStackPermissionsPermissionIdDelete`: %v\n", resp)
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
	resp, r, err := apiClient.RolesAPI.ApiV1AdminRolesRoleIdStackPermissionsPost(context.Background(), roleId).CreateStackPermissionRequest(createStackPermissionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RolesAPI.ApiV1AdminRolesRoleIdStackPermissionsPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminRolesRoleIdStackPermissionsPost`: CreateStackPermissionResponse
	fmt.Fprintf(os.Stdout, "Response from `RolesAPI.ApiV1AdminRolesRoleIdStackPermissionsPost`: %v\n", resp)
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

