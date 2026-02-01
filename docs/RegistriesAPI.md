# \RegistriesAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApiV1ServersServeridRegistriesGet**](RegistriesAPI.md#ApiV1ServersServeridRegistriesGet) | **Get** /api/v1/servers/{serverid}/registries | List registry credentials
[**ApiV1ServersServeridRegistriesIdDelete**](RegistriesAPI.md#ApiV1ServersServeridRegistriesIdDelete) | **Delete** /api/v1/servers/{serverid}/registries/{id} | Delete registry credential
[**ApiV1ServersServeridRegistriesIdGet**](RegistriesAPI.md#ApiV1ServersServeridRegistriesIdGet) | **Get** /api/v1/servers/{serverid}/registries/{id} | Get registry credential
[**ApiV1ServersServeridRegistriesIdPut**](RegistriesAPI.md#ApiV1ServersServeridRegistriesIdPut) | **Put** /api/v1/servers/{serverid}/registries/{id} | Update registry credential
[**ApiV1ServersServeridRegistriesPost**](RegistriesAPI.md#ApiV1ServersServeridRegistriesPost) | **Post** /api/v1/servers/{serverid}/registries | Create registry credential



## ApiV1ServersServeridRegistriesGet

> ListCredentialsResponse ApiV1ServersServeridRegistriesGet(ctx, serverid).Execute()

List registry credentials



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
	resp, r, err := apiClient.RegistriesAPI.ApiV1ServersServeridRegistriesGet(context.Background(), serverid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RegistriesAPI.ApiV1ServersServeridRegistriesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridRegistriesGet`: ListCredentialsResponse
	fmt.Fprintf(os.Stdout, "Response from `RegistriesAPI.ApiV1ServersServeridRegistriesGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridRegistriesGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ListCredentialsResponse**](ListCredentialsResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ServersServeridRegistriesIdDelete

> DeleteCredentialResponse ApiV1ServersServeridRegistriesIdDelete(ctx, serverid, id).Execute()

Delete registry credential



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
	id := int32(56) // int32 | Credential ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RegistriesAPI.ApiV1ServersServeridRegistriesIdDelete(context.Background(), serverid, id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RegistriesAPI.ApiV1ServersServeridRegistriesIdDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridRegistriesIdDelete`: DeleteCredentialResponse
	fmt.Fprintf(os.Stdout, "Response from `RegistriesAPI.ApiV1ServersServeridRegistriesIdDelete`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 
**id** | **int32** | Credential ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridRegistriesIdDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**DeleteCredentialResponse**](DeleteCredentialResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ServersServeridRegistriesIdGet

> GetCredentialResponse ApiV1ServersServeridRegistriesIdGet(ctx, serverid, id).Execute()

Get registry credential



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
	id := int32(56) // int32 | Credential ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RegistriesAPI.ApiV1ServersServeridRegistriesIdGet(context.Background(), serverid, id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RegistriesAPI.ApiV1ServersServeridRegistriesIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridRegistriesIdGet`: GetCredentialResponse
	fmt.Fprintf(os.Stdout, "Response from `RegistriesAPI.ApiV1ServersServeridRegistriesIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 
**id** | **int32** | Credential ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridRegistriesIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**GetCredentialResponse**](GetCredentialResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ServersServeridRegistriesIdPut

> UpdateCredentialResponse ApiV1ServersServeridRegistriesIdPut(ctx, serverid, id).UpdateCredentialRequest(updateCredentialRequest).Execute()

Update registry credential



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
	id := int32(56) // int32 | Credential ID
	updateCredentialRequest := *openapiclient.NewUpdateCredentialRequest("ImagePattern_example", "Password_example", "RegistryUrl_example", "StackPattern_example", "Username_example") // UpdateCredentialRequest | Updated registry credential details

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RegistriesAPI.ApiV1ServersServeridRegistriesIdPut(context.Background(), serverid, id).UpdateCredentialRequest(updateCredentialRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RegistriesAPI.ApiV1ServersServeridRegistriesIdPut``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridRegistriesIdPut`: UpdateCredentialResponse
	fmt.Fprintf(os.Stdout, "Response from `RegistriesAPI.ApiV1ServersServeridRegistriesIdPut`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 
**id** | **int32** | Credential ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridRegistriesIdPutRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updateCredentialRequest** | [**UpdateCredentialRequest**](UpdateCredentialRequest.md) | Updated registry credential details | 

### Return type

[**UpdateCredentialResponse**](UpdateCredentialResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1ServersServeridRegistriesPost

> CreateCredentialResponse ApiV1ServersServeridRegistriesPost(ctx, serverid).CreateCredentialRequest(createCredentialRequest).Execute()

Create registry credential



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
	createCredentialRequest := *openapiclient.NewCreateCredentialRequest("ImagePattern_example", "Password_example", "RegistryUrl_example", "StackPattern_example", "Username_example") // CreateCredentialRequest | Registry credential details

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RegistriesAPI.ApiV1ServersServeridRegistriesPost(context.Background(), serverid).CreateCredentialRequest(createCredentialRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RegistriesAPI.ApiV1ServersServeridRegistriesPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1ServersServeridRegistriesPost`: CreateCredentialResponse
	fmt.Fprintf(os.Stdout, "Response from `RegistriesAPI.ApiV1ServersServeridRegistriesPost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serverid** | **int32** | Server ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1ServersServeridRegistriesPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createCredentialRequest** | [**CreateCredentialRequest**](CreateCredentialRequest.md) | Registry credential details | 

### Return type

[**CreateCredentialResponse**](CreateCredentialResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

