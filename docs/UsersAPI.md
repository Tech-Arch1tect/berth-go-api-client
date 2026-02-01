# \UsersAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApiV1AdminUsersAssignRolePost**](UsersAPI.md#ApiV1AdminUsersAssignRolePost) | **Post** /api/v1/admin/users/assign-role | Assign a role to a user
[**ApiV1AdminUsersGet**](UsersAPI.md#ApiV1AdminUsersGet) | **Get** /api/v1/admin/users | List all users
[**ApiV1AdminUsersIdRolesGet**](UsersAPI.md#ApiV1AdminUsersIdRolesGet) | **Get** /api/v1/admin/users/{id}/roles | Get user with roles
[**ApiV1AdminUsersPost**](UsersAPI.md#ApiV1AdminUsersPost) | **Post** /api/v1/admin/users | Create a new user
[**ApiV1AdminUsersRevokeRolePost**](UsersAPI.md#ApiV1AdminUsersRevokeRolePost) | **Post** /api/v1/admin/users/revoke-role | Revoke a role from a user



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
	resp, r, err := apiClient.UsersAPI.ApiV1AdminUsersAssignRolePost(context.Background()).AssignRoleRequest(assignRoleRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.ApiV1AdminUsersAssignRolePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminUsersAssignRolePost`: AssignRoleResponse
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.ApiV1AdminUsersAssignRolePost`: %v\n", resp)
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
	resp, r, err := apiClient.UsersAPI.ApiV1AdminUsersGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.ApiV1AdminUsersGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminUsersGet`: ListUsersResponse
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.ApiV1AdminUsersGet`: %v\n", resp)
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
	resp, r, err := apiClient.UsersAPI.ApiV1AdminUsersIdRolesGet(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.ApiV1AdminUsersIdRolesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminUsersIdRolesGet`: GetUserRolesResponse
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.ApiV1AdminUsersIdRolesGet`: %v\n", resp)
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
	resp, r, err := apiClient.UsersAPI.ApiV1AdminUsersPost(context.Background()).CreateUserRequest(createUserRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.ApiV1AdminUsersPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminUsersPost`: CreateUserResponse
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.ApiV1AdminUsersPost`: %v\n", resp)
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
	resp, r, err := apiClient.UsersAPI.ApiV1AdminUsersRevokeRolePost(context.Background()).RevokeRoleRequest(revokeRoleRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.ApiV1AdminUsersRevokeRolePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminUsersRevokeRolePost`: RevokeRoleResponse
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.ApiV1AdminUsersRevokeRolePost`: %v\n", resp)
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

