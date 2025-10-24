# \CliAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetVaultByAPIKey**](CliAPI.md#GetVaultByAPIKey) | **Get** /api/cli/vault/{uniqueId} | 
[**GetVaultByNameAPIKey**](CliAPI.md#GetVaultByNameAPIKey) | **Get** /api/cli/vault/name/{name} | 
[**GetVaultsByAPIKey**](CliAPI.md#GetVaultsByAPIKey) | **Get** /api/cli/vaults | 



## GetVaultByAPIKey

> Vault GetVaultByAPIKey(ctx, uniqueId).XEnableClientEncryption(xEnableClientEncryption).Execute()





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
	xEnableClientEncryption := "xEnableClientEncryption_example" // string | Enable client-side encryption (server returns encrypted value) (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CliAPI.GetVaultByAPIKey(context.Background(), uniqueId).XEnableClientEncryption(xEnableClientEncryption).Execute()
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

 **xEnableClientEncryption** | **string** | Enable client-side encryption (server returns encrypted value) | 

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

> Vault GetVaultByNameAPIKey(ctx, name).XEnableClientEncryption(xEnableClientEncryption).Execute()





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
	xEnableClientEncryption := "xEnableClientEncryption_example" // string | Enable client-side encryption (server returns encrypted value) (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CliAPI.GetVaultByNameAPIKey(context.Background(), name).XEnableClientEncryption(xEnableClientEncryption).Execute()
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

 **xEnableClientEncryption** | **string** | Enable client-side encryption (server returns encrypted value) | 

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

