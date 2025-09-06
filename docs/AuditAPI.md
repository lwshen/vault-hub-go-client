# \AuditAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetAuditLogs**](AuditAPI.md#GetAuditLogs) | **Get** /api/audit-logs | 
[**GetAuditMetrics**](AuditAPI.md#GetAuditMetrics) | **Get** /api/audit-logs/metrics | 



## GetAuditLogs

> AuditLogsResponse GetAuditLogs(ctx).PageSize(pageSize).PageIndex(pageIndex).StartDate(startDate).EndDate(endDate).VaultUniqueId(vaultUniqueId).Execute()





### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/lwshen/vault-hub-go-client"
)

func main() {
	pageSize := int32(56) // int32 | Number of logs per page (default 100, max 1000) (default to 20)
	pageIndex := int32(56) // int32 | Page index, starting from 0 (default 0) (default to 1)
	startDate := time.Now() // time.Time | Filter logs from this date (ISO 8601 format) (optional)
	endDate := time.Now() // time.Time | Filter logs until this date (ISO 8601 format) (optional)
	vaultUniqueId := "vaultUniqueId_example" // string | Filter logs by vault unique ID (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuditAPI.GetAuditLogs(context.Background()).PageSize(pageSize).PageIndex(pageIndex).StartDate(startDate).EndDate(endDate).VaultUniqueId(vaultUniqueId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuditAPI.GetAuditLogs``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAuditLogs`: AuditLogsResponse
	fmt.Fprintf(os.Stdout, "Response from `AuditAPI.GetAuditLogs`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAuditLogsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **pageSize** | **int32** | Number of logs per page (default 100, max 1000) | [default to 20]
 **pageIndex** | **int32** | Page index, starting from 0 (default 0) | [default to 1]
 **startDate** | **time.Time** | Filter logs from this date (ISO 8601 format) | 
 **endDate** | **time.Time** | Filter logs until this date (ISO 8601 format) | 
 **vaultUniqueId** | **string** | Filter logs by vault unique ID | 

### Return type

[**AuditLogsResponse**](AuditLogsResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAuditMetrics

> AuditMetricsResponse GetAuditMetrics(ctx).Execute()





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
	resp, r, err := apiClient.AuditAPI.GetAuditMetrics(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuditAPI.GetAuditMetrics``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAuditMetrics`: AuditMetricsResponse
	fmt.Fprintf(os.Stdout, "Response from `AuditAPI.GetAuditMetrics`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetAuditMetricsRequest struct via the builder pattern


### Return type

[**AuditMetricsResponse**](AuditMetricsResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

