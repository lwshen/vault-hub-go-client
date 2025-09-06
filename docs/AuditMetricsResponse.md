# AuditMetricsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TotalEventsLast30Days** | **int32** | Total number of audit events in the last 30 days | 
**EventsCountLast24Hours** | **int32** | Number of audit events in the last 24 hours | 
**VaultEventsLast30Days** | **int32** | Number of vault-related events in the last 30 days | 
**ApiKeyEventsLast30Days** | **int32** | Number of API key-related events in the last 30 days | 

## Methods

### NewAuditMetricsResponse

`func NewAuditMetricsResponse(totalEventsLast30Days int32, eventsCountLast24Hours int32, vaultEventsLast30Days int32, apiKeyEventsLast30Days int32, ) *AuditMetricsResponse`

NewAuditMetricsResponse instantiates a new AuditMetricsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAuditMetricsResponseWithDefaults

`func NewAuditMetricsResponseWithDefaults() *AuditMetricsResponse`

NewAuditMetricsResponseWithDefaults instantiates a new AuditMetricsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTotalEventsLast30Days

`func (o *AuditMetricsResponse) GetTotalEventsLast30Days() int32`

GetTotalEventsLast30Days returns the TotalEventsLast30Days field if non-nil, zero value otherwise.

### GetTotalEventsLast30DaysOk

`func (o *AuditMetricsResponse) GetTotalEventsLast30DaysOk() (*int32, bool)`

GetTotalEventsLast30DaysOk returns a tuple with the TotalEventsLast30Days field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalEventsLast30Days

`func (o *AuditMetricsResponse) SetTotalEventsLast30Days(v int32)`

SetTotalEventsLast30Days sets TotalEventsLast30Days field to given value.


### GetEventsCountLast24Hours

`func (o *AuditMetricsResponse) GetEventsCountLast24Hours() int32`

GetEventsCountLast24Hours returns the EventsCountLast24Hours field if non-nil, zero value otherwise.

### GetEventsCountLast24HoursOk

`func (o *AuditMetricsResponse) GetEventsCountLast24HoursOk() (*int32, bool)`

GetEventsCountLast24HoursOk returns a tuple with the EventsCountLast24Hours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventsCountLast24Hours

`func (o *AuditMetricsResponse) SetEventsCountLast24Hours(v int32)`

SetEventsCountLast24Hours sets EventsCountLast24Hours field to given value.


### GetVaultEventsLast30Days

`func (o *AuditMetricsResponse) GetVaultEventsLast30Days() int32`

GetVaultEventsLast30Days returns the VaultEventsLast30Days field if non-nil, zero value otherwise.

### GetVaultEventsLast30DaysOk

`func (o *AuditMetricsResponse) GetVaultEventsLast30DaysOk() (*int32, bool)`

GetVaultEventsLast30DaysOk returns a tuple with the VaultEventsLast30Days field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVaultEventsLast30Days

`func (o *AuditMetricsResponse) SetVaultEventsLast30Days(v int32)`

SetVaultEventsLast30Days sets VaultEventsLast30Days field to given value.


### GetApiKeyEventsLast30Days

`func (o *AuditMetricsResponse) GetApiKeyEventsLast30Days() int32`

GetApiKeyEventsLast30Days returns the ApiKeyEventsLast30Days field if non-nil, zero value otherwise.

### GetApiKeyEventsLast30DaysOk

`func (o *AuditMetricsResponse) GetApiKeyEventsLast30DaysOk() (*int32, bool)`

GetApiKeyEventsLast30DaysOk returns a tuple with the ApiKeyEventsLast30Days field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApiKeyEventsLast30Days

`func (o *AuditMetricsResponse) SetApiKeyEventsLast30Days(v int32)`

SetApiKeyEventsLast30Days sets ApiKeyEventsLast30Days field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


