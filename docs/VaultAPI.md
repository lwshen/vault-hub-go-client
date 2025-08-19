# \VaultAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateVault**](VaultAPI.md#CreateVault) | **Post** /api/vaults | 
[**DeleteVault**](VaultAPI.md#DeleteVault) | **Delete** /api/vaults/{uniqueId} | 
[**GetVault**](VaultAPI.md#GetVault) | **Get** /api/vaults/{uniqueId} | 
[**GetVaults**](VaultAPI.md#GetVaults) | **Get** /api/vaults | 
[**UpdateVault**](VaultAPI.md#UpdateVault) | **Put** /api/vaults/{uniqueId} | 



## CreateVault

> Vault CreateVault(ctx).CreateVaultRequest(createVaultRequest).Execute()





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
	createVaultRequest := *openapiclient.NewCreateVaultRequest("Name_example", "Value_example") // CreateVaultRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.VaultAPI.CreateVault(context.Background()).CreateVaultRequest(createVaultRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VaultAPI.CreateVault``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateVault`: Vault
	fmt.Fprintf(os.Stdout, "Response from `VaultAPI.CreateVault`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateVaultRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createVaultRequest** | [**CreateVaultRequest**](CreateVaultRequest.md) |  | 

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


## DeleteVault

> DeleteVault(ctx, uniqueId).Execute()





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
	r, err := apiClient.VaultAPI.DeleteVault(context.Background(), uniqueId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VaultAPI.DeleteVault``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**uniqueId** | **string** | Vault Unique ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteVaultRequest struct via the builder pattern


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


## GetVault

> Vault GetVault(ctx, uniqueId).Execute()





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
	resp, r, err := apiClient.VaultAPI.GetVault(context.Background(), uniqueId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VaultAPI.GetVault``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetVault`: Vault
	fmt.Fprintf(os.Stdout, "Response from `VaultAPI.GetVault`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**uniqueId** | **string** | Vault Unique ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetVaultRequest struct via the builder pattern


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


## GetVaults

> []VaultLite GetVaults(ctx).Execute()





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
	resp, r, err := apiClient.VaultAPI.GetVaults(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VaultAPI.GetVaults``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetVaults`: []VaultLite
	fmt.Fprintf(os.Stdout, "Response from `VaultAPI.GetVaults`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetVaultsRequest struct via the builder pattern


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


## UpdateVault

> Vault UpdateVault(ctx, uniqueId).UpdateVaultRequest(updateVaultRequest).Execute()





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
	resp, r, err := apiClient.VaultAPI.UpdateVault(context.Background(), uniqueId).UpdateVaultRequest(updateVaultRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VaultAPI.UpdateVault``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateVault`: Vault
	fmt.Fprintf(os.Stdout, "Response from `VaultAPI.UpdateVault`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**uniqueId** | **string** | Vault Unique ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateVaultRequest struct via the builder pattern


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

