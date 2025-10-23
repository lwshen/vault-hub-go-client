# VaultsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Vaults** | [**[]VaultLite**](VaultLite.md) | Page of vault records for the authenticated user | 
**TotalCount** | **int32** | Total number of vaults available for pagination | 
**PageSize** | **int32** | Number of vaults returned per page | 
**PageIndex** | **int32** | Current page index (starting from 1) | 

## Methods

### NewVaultsResponse

`func NewVaultsResponse(vaults []VaultLite, totalCount int32, pageSize int32, pageIndex int32, ) *VaultsResponse`

NewVaultsResponse instantiates a new VaultsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVaultsResponseWithDefaults

`func NewVaultsResponseWithDefaults() *VaultsResponse`

NewVaultsResponseWithDefaults instantiates a new VaultsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetVaults

`func (o *VaultsResponse) GetVaults() []VaultLite`

GetVaults returns the Vaults field if non-nil, zero value otherwise.

### GetVaultsOk

`func (o *VaultsResponse) GetVaultsOk() (*[]VaultLite, bool)`

GetVaultsOk returns a tuple with the Vaults field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVaults

`func (o *VaultsResponse) SetVaults(v []VaultLite)`

SetVaults sets Vaults field to given value.


### GetTotalCount

`func (o *VaultsResponse) GetTotalCount() int32`

GetTotalCount returns the TotalCount field if non-nil, zero value otherwise.

### GetTotalCountOk

`func (o *VaultsResponse) GetTotalCountOk() (*int32, bool)`

GetTotalCountOk returns a tuple with the TotalCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCount

`func (o *VaultsResponse) SetTotalCount(v int32)`

SetTotalCount sets TotalCount field to given value.


### GetPageSize

`func (o *VaultsResponse) GetPageSize() int32`

GetPageSize returns the PageSize field if non-nil, zero value otherwise.

### GetPageSizeOk

`func (o *VaultsResponse) GetPageSizeOk() (*int32, bool)`

GetPageSizeOk returns a tuple with the PageSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageSize

`func (o *VaultsResponse) SetPageSize(v int32)`

SetPageSize sets PageSize field to given value.


### GetPageIndex

`func (o *VaultsResponse) GetPageIndex() int32`

GetPageIndex returns the PageIndex field if non-nil, zero value otherwise.

### GetPageIndexOk

`func (o *VaultsResponse) GetPageIndexOk() (*int32, bool)`

GetPageIndexOk returns a tuple with the PageIndex field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageIndex

`func (o *VaultsResponse) SetPageIndex(v int32)`

SetPageIndex sets PageIndex field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


