# VaultFilterOptionsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Vaults** | [**[]VaultFilterOption**](VaultFilterOption.md) | List of vaults for filter dropdowns | 

## Methods

### NewVaultFilterOptionsResponse

`func NewVaultFilterOptionsResponse(vaults []VaultFilterOption, ) *VaultFilterOptionsResponse`

NewVaultFilterOptionsResponse instantiates a new VaultFilterOptionsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVaultFilterOptionsResponseWithDefaults

`func NewVaultFilterOptionsResponseWithDefaults() *VaultFilterOptionsResponse`

NewVaultFilterOptionsResponseWithDefaults instantiates a new VaultFilterOptionsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetVaults

`func (o *VaultFilterOptionsResponse) GetVaults() []VaultFilterOption`

GetVaults returns the Vaults field if non-nil, zero value otherwise.

### GetVaultsOk

`func (o *VaultFilterOptionsResponse) GetVaultsOk() (*[]VaultFilterOption, bool)`

GetVaultsOk returns a tuple with the Vaults field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVaults

`func (o *VaultFilterOptionsResponse) SetVaults(v []VaultFilterOption)`

SetVaults sets Vaults field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


