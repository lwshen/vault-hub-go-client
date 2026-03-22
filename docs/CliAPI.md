# \CliAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetVaultByAPIKey**](CliAPI.md#GetVaultByAPIKey) | **Get** /api/cli/vault/{uniqueId} | 
[**GetVaultByNameAPIKey**](CliAPI.md#GetVaultByNameAPIKey) | **Get** /api/cli/vault/name/{name} | 
[**GetVaultsByAPIKey**](CliAPI.md#GetVaultsByAPIKey) | **Get** /api/cli/vaults | 
[**UpdateVaultByAPIKey**](CliAPI.md#UpdateVaultByAPIKey) | **Put** /api/cli/vault/{uniqueId} | 
[**UpdateVaultByNameAPIKey**](CliAPI.md#UpdateVaultByNameAPIKey) | **Put** /api/cli/vault/name/{name} | 



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
	resp, r, err := apiClient.CliAPI.GetVaultByAPIKey(context.Background(), uniqueId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CliAPI.GetVaultByAPIKey``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetVaultByAPIKey`: Vault
	fmt.Fprintf(os.Stdout, "Response from `CliAPI.GetVaultByAPIKey`: %v\n", resp)
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
	resp, r, err := apiClient.CliAPI.GetVaultByNameAPIKey(context.Background(), name).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CliAPI.GetVaultByNameAPIKey``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetVaultByNameAPIKey`: Vault
	fmt.Fprintf(os.Stdout, "Response from `CliAPI.GetVaultByNameAPIKey`: %v\n", resp)
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
	resp, r, err := apiClient.CliAPI.GetVaultsByAPIKey(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CliAPI.GetVaultsByAPIKey``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetVaultsByAPIKey`: []VaultLite
	fmt.Fprintf(os.Stdout, "Response from `CliAPI.GetVaultsByAPIKey`: %v\n", resp)
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


## UpdateVaultByAPIKey

> Vault UpdateVaultByAPIKey(ctx, uniqueId).UpdateVaultRequest(updateVaultRequest).Execute()





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
	updateVaultRequest := *openapiclient.NewUpdateVaultRequest() // UpdateVaultRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CliAPI.UpdateVaultByAPIKey(context.Background(), uniqueId).UpdateVaultRequest(updateVaultRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CliAPI.UpdateVaultByAPIKey``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateVaultByAPIKey`: Vault
	fmt.Fprintf(os.Stdout, "Response from `CliAPI.UpdateVaultByAPIKey`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**uniqueId** | **string** | Vault Unique ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateVaultByAPIKeyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateVaultRequest** | [**UpdateVaultRequest**](UpdateVaultRequest.md) |  | 

### Return type

[**Vault**](Vault.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateVaultByNameAPIKey

> Vault UpdateVaultByNameAPIKey(ctx, name).UpdateVaultRequest(updateVaultRequest).Execute()





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
	updateVaultRequest := *openapiclient.NewUpdateVaultRequest() // UpdateVaultRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CliAPI.UpdateVaultByNameAPIKey(context.Background(), name).UpdateVaultRequest(updateVaultRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CliAPI.UpdateVaultByNameAPIKey``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateVaultByNameAPIKey`: Vault
	fmt.Fprintf(os.Stdout, "Response from `CliAPI.UpdateVaultByNameAPIKey`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**name** | **string** | Vault name | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateVaultByNameAPIKeyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateVaultRequest** | [**UpdateVaultRequest**](UpdateVaultRequest.md) |  | 

### Return type

[**Vault**](Vault.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

