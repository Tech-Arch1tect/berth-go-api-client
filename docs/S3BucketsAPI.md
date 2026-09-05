# \S3BucketsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApiV1AdminS3BucketsGet**](S3BucketsAPI.md#ApiV1AdminS3BucketsGet) | **Get** /api/v1/admin/s3-buckets | List S3 bucket configurations
[**ApiV1AdminS3BucketsIdDelete**](S3BucketsAPI.md#ApiV1AdminS3BucketsIdDelete) | **Delete** /api/v1/admin/s3-buckets/{id} | Delete an S3 bucket configuration
[**ApiV1AdminS3BucketsIdGet**](S3BucketsAPI.md#ApiV1AdminS3BucketsIdGet) | **Get** /api/v1/admin/s3-buckets/{id} | Get an S3 bucket configuration
[**ApiV1AdminS3BucketsIdPut**](S3BucketsAPI.md#ApiV1AdminS3BucketsIdPut) | **Put** /api/v1/admin/s3-buckets/{id} | Update an S3 bucket configuration
[**ApiV1AdminS3BucketsPost**](S3BucketsAPI.md#ApiV1AdminS3BucketsPost) | **Post** /api/v1/admin/s3-buckets | Create an S3 bucket configuration



## ApiV1AdminS3BucketsGet

> ResponseBucketResponse ApiV1AdminS3BucketsGet(ctx).Execute()

List S3 bucket configurations



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
	resp, r, err := apiClient.S3BucketsAPI.ApiV1AdminS3BucketsGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `S3BucketsAPI.ApiV1AdminS3BucketsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminS3BucketsGet`: ResponseBucketResponse
	fmt.Fprintf(os.Stdout, "Response from `S3BucketsAPI.ApiV1AdminS3BucketsGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AdminS3BucketsGetRequest struct via the builder pattern


### Return type

[**ResponseBucketResponse**](ResponseBucketResponse.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1AdminS3BucketsIdDelete

> ResponseEmpty ApiV1AdminS3BucketsIdDelete(ctx, id).Execute()

Delete an S3 bucket configuration



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
	id := int32(56) // int32 | Bucket configuration ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.S3BucketsAPI.ApiV1AdminS3BucketsIdDelete(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `S3BucketsAPI.ApiV1AdminS3BucketsIdDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminS3BucketsIdDelete`: ResponseEmpty
	fmt.Fprintf(os.Stdout, "Response from `S3BucketsAPI.ApiV1AdminS3BucketsIdDelete`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Bucket configuration ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AdminS3BucketsIdDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ResponseEmpty**](ResponseEmpty.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1AdminS3BucketsIdGet

> ResponseBucketResponse2 ApiV1AdminS3BucketsIdGet(ctx, id).Execute()

Get an S3 bucket configuration

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
	id := int32(56) // int32 | Bucket configuration ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.S3BucketsAPI.ApiV1AdminS3BucketsIdGet(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `S3BucketsAPI.ApiV1AdminS3BucketsIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminS3BucketsIdGet`: ResponseBucketResponse2
	fmt.Fprintf(os.Stdout, "Response from `S3BucketsAPI.ApiV1AdminS3BucketsIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Bucket configuration ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AdminS3BucketsIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ResponseBucketResponse2**](ResponseBucketResponse2.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1AdminS3BucketsIdPut

> ResponseBucketResponse2 ApiV1AdminS3BucketsIdPut(ctx, id).UpdateRequest(updateRequest).Execute()

Update an S3 bucket configuration



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
	id := int32(56) // int32 | Bucket configuration ID
	updateRequest := *openapiclient.NewUpdateRequest("AccessKeyId_example", "BucketName_example", "Endpoint_example", "Label_example", "Region_example", "SecretAccessKey_example") // UpdateRequest | Bucket configuration; empty secret access key keeps the stored secret

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.S3BucketsAPI.ApiV1AdminS3BucketsIdPut(context.Background(), id).UpdateRequest(updateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `S3BucketsAPI.ApiV1AdminS3BucketsIdPut``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminS3BucketsIdPut`: ResponseBucketResponse2
	fmt.Fprintf(os.Stdout, "Response from `S3BucketsAPI.ApiV1AdminS3BucketsIdPut`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Bucket configuration ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AdminS3BucketsIdPutRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateRequest** | [**UpdateRequest**](UpdateRequest.md) | Bucket configuration; empty secret access key keeps the stored secret | 

### Return type

[**ResponseBucketResponse2**](ResponseBucketResponse2.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiV1AdminS3BucketsPost

> ResponseBucketResponse2 ApiV1AdminS3BucketsPost(ctx).CreateRequest(createRequest).Execute()

Create an S3 bucket configuration



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
	createRequest := *openapiclient.NewCreateRequest("AccessKeyId_example", "BucketName_example", "Endpoint_example", "Label_example", "Region_example", "SecretAccessKey_example") // CreateRequest | Bucket configuration including the secret access key

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.S3BucketsAPI.ApiV1AdminS3BucketsPost(context.Background()).CreateRequest(createRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `S3BucketsAPI.ApiV1AdminS3BucketsPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiV1AdminS3BucketsPost`: ResponseBucketResponse2
	fmt.Fprintf(os.Stdout, "Response from `S3BucketsAPI.ApiV1AdminS3BucketsPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiV1AdminS3BucketsPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createRequest** | [**CreateRequest**](CreateRequest.md) | Bucket configuration including the secret access key | 

### Return type

[**ResponseBucketResponse2**](ResponseBucketResponse2.md)

### Authorization

[apiKey](../README.md#apiKey), [session](../README.md#session), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

