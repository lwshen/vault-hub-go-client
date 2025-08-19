# AuditLogsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AuditLogs** | [**[]AuditLog**](AuditLog.md) |  | 
**TotalCount** | **int32** | Total number of logs matching the filter criteria | 
**PageSize** | **int32** | Number of logs per page | 
**PageIndex** | **int32** | Current page index (starting from 0) | 

## Methods

### NewAuditLogsResponse

`func NewAuditLogsResponse(auditLogs []AuditLog, totalCount int32, pageSize int32, pageIndex int32, ) *AuditLogsResponse`

NewAuditLogsResponse instantiates a new AuditLogsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAuditLogsResponseWithDefaults

`func NewAuditLogsResponseWithDefaults() *AuditLogsResponse`

NewAuditLogsResponseWithDefaults instantiates a new AuditLogsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAuditLogs

`func (o *AuditLogsResponse) GetAuditLogs() []AuditLog`

GetAuditLogs returns the AuditLogs field if non-nil, zero value otherwise.

### GetAuditLogsOk

`func (o *AuditLogsResponse) GetAuditLogsOk() (*[]AuditLog, bool)`

GetAuditLogsOk returns a tuple with the AuditLogs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuditLogs

`func (o *AuditLogsResponse) SetAuditLogs(v []AuditLog)`

SetAuditLogs sets AuditLogs field to given value.


### GetTotalCount

`func (o *AuditLogsResponse) GetTotalCount() int32`

GetTotalCount returns the TotalCount field if non-nil, zero value otherwise.

### GetTotalCountOk

`func (o *AuditLogsResponse) GetTotalCountOk() (*int32, bool)`

GetTotalCountOk returns a tuple with the TotalCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCount

`func (o *AuditLogsResponse) SetTotalCount(v int32)`

SetTotalCount sets TotalCount field to given value.


### GetPageSize

`func (o *AuditLogsResponse) GetPageSize() int32`

GetPageSize returns the PageSize field if non-nil, zero value otherwise.

### GetPageSizeOk

`func (o *AuditLogsResponse) GetPageSizeOk() (*int32, bool)`

GetPageSizeOk returns a tuple with the PageSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageSize

`func (o *AuditLogsResponse) SetPageSize(v int32)`

SetPageSize sets PageSize field to given value.


### GetPageIndex

`func (o *AuditLogsResponse) GetPageIndex() int32`

GetPageIndex returns the PageIndex field if non-nil, zero value otherwise.

### GetPageIndexOk

`func (o *AuditLogsResponse) GetPageIndexOk() (*int32, bool)`

GetPageIndexOk returns a tuple with the PageIndex field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageIndex

`func (o *AuditLogsResponse) SetPageIndex(v int32)`

SetPageIndex sets PageIndex field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


