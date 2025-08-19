# \APIKeyAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateAPIKey**](APIKeyAPI.md#CreateAPIKey) | **Post** /api/api-keys | 
[**DeleteAPIKey**](APIKeyAPI.md#DeleteAPIKey) | **Delete** /api/api-keys/{id} | 
[**GetAPIKeys**](APIKeyAPI.md#GetAPIKeys) | **Get** /api/api-keys | 
[**GetVaultByAPIKey**](APIKeyAPI.md#GetVaultByAPIKey) | **Get** /api/cli/vault/{uniqueId} | 
[**GetVaultByNameAPIKey**](APIKeyAPI.md#GetVaultByNameAPIKey) | **Get** /api/cli/vault/name/{name} | 
[**GetVaultsByAPIKey**](APIKeyAPI.md#GetVaultsByAPIKey) | **Get** /api/cli/vaults | 
[**UpdateAPIKey**](APIKeyAPI.md#UpdateAPIKey) | **Patch** /api/api-keys/{id} | 



## CreateAPIKey

> CreateAPIKeyResponse CreateAPIKey(ctx).CreateAPIKeyRequest(createAPIKeyRequest).Execute()





### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/lwshen/vault-hub-go-client"
)

func main() {
	createAPIKeyRequest := *openapiclient.NewCreateAPIKeyRequest("Name_example") // CreateAPIKeyRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.APIKeyAPI.CreateAPIKey(context.Background()).CreateAPIKeyRequest(createAPIKeyRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `APIKeyAPI.CreateAPIKey``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateAPIKey`: CreateAPIKeyResponse
	fmt.Fprintf(os.Stdout, "Response from `APIKeyAPI.CreateAPIKey`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateAPIKeyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createAPIKeyRequest** | [**CreateAPIKeyRequest**](CreateAPIKeyRequest.md) |  | 

### Return type

[**CreateAPIKeyResponse**](CreateAPIKeyResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteAPIKey

> DeleteAPIKey(ctx, id).Execute()





### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/lwshen/vault-hub-go-client"
)

func main() {
	id := int64(789) // int64 | API Key ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.APIKeyAPI.DeleteAPIKey(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `APIKeyAPI.DeleteAPIKey``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int64** | API Key ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteAPIKeyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAPIKeys

> APIKeysResponse GetAPIKeys(ctx).PageSize(pageSize).PageIndex(pageIndex).Execute()





### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/lwshen/vault-hub-go-client"
)

func main() {
	pageSize := int32(56) // int32 | Number of API keys per page (default 20, max 1000) (default to 20)
	pageIndex := int32(56) // int32 | Page index, starting from 1 (default 1) (default to 1)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.APIKeyAPI.GetAPIKeys(context.Background()).PageSize(pageSize).PageIndex(pageIndex).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `APIKeyAPI.GetAPIKeys``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAPIKeys`: APIKeysResponse
	fmt.Fprintf(os.Stdout, "Response from `APIKeyAPI.GetAPIKeys`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAPIKeysRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **pageSize** | **int32** | Number of API keys per page (default 20, max 1000) | [default to 20]
 **pageIndex** | **int32** | Page index, starting from 1 (default 1) | [default to 1]

### Return type

[**APIKeysResponse**](APIKeysResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetVaultByAPIKey

> Vault GetVaultByAPIKey(ctx, uniqueId).Execute()





### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/lwshen/vault-hub-go-client"
)

func main() {
	uniqueId := "uniqueId_example" // string | Vault Unique ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.APIKeyAPI.GetVaultByAPIKey(context.Background(), uniqueId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `APIKeyAPI.GetVaultByAPIKey``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetVaultByAPIKey`: Vault
	fmt.Fprintf(os.Stdout, "Response from `APIKeyAPI.GetVaultByAPIKey`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**uniqueId** | **string** | Vault Unique ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetVaultByAPIKeyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Vault**](Vault.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetVaultByNameAPIKey

> Vault GetVaultByNameAPIKey(ctx, name).Execute()





### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/lwshen/vault-hub-go-client"
)

func main() {
	name := "name_example" // string | Vault name

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.APIKeyAPI.GetVaultByNameAPIKey(context.Background(), name).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `APIKeyAPI.GetVaultByNameAPIKey``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetVaultByNameAPIKey`: Vault
	fmt.Fprintf(os.Stdout, "Response from `APIKeyAPI.GetVaultByNameAPIKey`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**name** | **string** | Vault name | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetVaultByNameAPIKeyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Vault**](Vault.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetVaultsByAPIKey

> []VaultLite GetVaultsByAPIKey(ctx).Execute()





### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/lwshen/vault-hub-go-client"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.APIKeyAPI.GetVaultsByAPIKey(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `APIKeyAPI.GetVaultsByAPIKey``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetVaultsByAPIKey`: []VaultLite
	fmt.Fprintf(os.Stdout, "Response from `APIKeyAPI.GetVaultsByAPIKey`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetVaultsByAPIKeyRequest struct via the builder pattern


### Return type

[**[]VaultLite**](VaultLite.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateAPIKey

> VaultAPIKey UpdateAPIKey(ctx, id).UpdateAPIKeyRequest(updateAPIKeyRequest).Execute()





### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/lwshen/vault-hub-go-client"
)

func main() {
	id := int64(789) // int64 | API Key ID
	updateAPIKeyRequest := *openapiclient.NewUpdateAPIKeyRequest() // UpdateAPIKeyRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.APIKeyAPI.UpdateAPIKey(context.Background(), id).UpdateAPIKeyRequest(updateAPIKeyRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `APIKeyAPI.UpdateAPIKey``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateAPIKey`: VaultAPIKey
	fmt.Fprintf(os.Stdout, "Response from `APIKeyAPI.UpdateAPIKey`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int64** | API Key ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateAPIKeyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateAPIKeyRequest** | [**UpdateAPIKeyRequest**](UpdateAPIKeyRequest.md) |  | 

### Return type

[**VaultAPIKey**](VaultAPIKey.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

