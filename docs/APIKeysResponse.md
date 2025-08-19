# APIKeysResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApiKeys** | [**[]APIKey**](APIKey.md) |  | 
**TotalCount** | **int32** | Total number of API keys | 
**PageSize** | **int32** | Number of API keys per page | 
**PageIndex** | **int32** | Current page index (starting from 1) | 

## Methods

### NewAPIKeysResponse

`func NewAPIKeysResponse(apiKeys []APIKey, totalCount int32, pageSize int32, pageIndex int32, ) *APIKeysResponse`

NewAPIKeysResponse instantiates a new APIKeysResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAPIKeysResponseWithDefaults

`func NewAPIKeysResponseWithDefaults() *APIKeysResponse`

NewAPIKeysResponseWithDefaults instantiates a new APIKeysResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApiKeys

`func (o *APIKeysResponse) GetApiKeys() []APIKey`

GetApiKeys returns the ApiKeys field if non-nil, zero value otherwise.

### GetApiKeysOk

`func (o *APIKeysResponse) GetApiKeysOk() (*[]APIKey, bool)`

GetApiKeysOk returns a tuple with the ApiKeys field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApiKeys

`func (o *APIKeysResponse) SetApiKeys(v []APIKey)`

SetApiKeys sets ApiKeys field to given value.


### GetTotalCount

`func (o *APIKeysResponse) GetTotalCount() int32`

GetTotalCount returns the TotalCount field if non-nil, zero value otherwise.

### GetTotalCountOk

`func (o *APIKeysResponse) GetTotalCountOk() (*int32, bool)`

GetTotalCountOk returns a tuple with the TotalCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCount

`func (o *APIKeysResponse) SetTotalCount(v int32)`

SetTotalCount sets TotalCount field to given value.


### GetPageSize

`func (o *APIKeysResponse) GetPageSize() int32`

GetPageSize returns the PageSize field if non-nil, zero value otherwise.

### GetPageSizeOk

`func (o *APIKeysResponse) GetPageSizeOk() (*int32, bool)`

GetPageSizeOk returns a tuple with the PageSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageSize

`func (o *APIKeysResponse) SetPageSize(v int32)`

SetPageSize sets PageSize field to given value.


### GetPageIndex

`func (o *APIKeysResponse) GetPageIndex() int32`

GetPageIndex returns the PageIndex field if non-nil, zero value otherwise.

### GetPageIndexOk

`func (o *APIKeysResponse) GetPageIndexOk() (*int32, bool)`

GetPageIndexOk returns a tuple with the PageIndex field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageIndex

`func (o *APIKeysResponse) SetPageIndex(v int32)`

SetPageIndex sets PageIndex field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


