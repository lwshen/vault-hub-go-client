# VaultAPIKey

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int64** | Unique API key ID | 
**Name** | **string** | Human-readable name for the API key | 
**Vaults** | Pointer to [**[]VaultLite**](VaultLite.md) | Array of vaults this key can access (null/empty &#x3D; all user&#39;s vaults) | [optional] 
**ExpiresAt** | Pointer to **time.Time** | Optional expiration date | [optional] 
**LastUsedAt** | Pointer to **time.Time** | When the key was last used | [optional] 
**IsActive** | **bool** | Whether the key is currently active | 
**CreatedAt** | **time.Time** | When the key was created | 
**UpdatedAt** | Pointer to **time.Time** | When the key was last updated | [optional] 

## Methods

### NewVaultAPIKey

`func NewVaultAPIKey(id int64, name string, isActive bool, createdAt time.Time, ) *VaultAPIKey`

NewVaultAPIKey instantiates a new VaultAPIKey object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVaultAPIKeyWithDefaults

`func NewVaultAPIKeyWithDefaults() *VaultAPIKey`

NewVaultAPIKeyWithDefaults instantiates a new VaultAPIKey object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *VaultAPIKey) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *VaultAPIKey) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *VaultAPIKey) SetId(v int64)`

SetId sets Id field to given value.


### GetName

`func (o *VaultAPIKey) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *VaultAPIKey) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *VaultAPIKey) SetName(v string)`

SetName sets Name field to given value.


### GetVaults

`func (o *VaultAPIKey) GetVaults() []VaultLite`

GetVaults returns the Vaults field if non-nil, zero value otherwise.

### GetVaultsOk

`func (o *VaultAPIKey) GetVaultsOk() (*[]VaultLite, bool)`

GetVaultsOk returns a tuple with the Vaults field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVaults

`func (o *VaultAPIKey) SetVaults(v []VaultLite)`

SetVaults sets Vaults field to given value.

### HasVaults

`func (o *VaultAPIKey) HasVaults() bool`

HasVaults returns a boolean if a field has been set.

### GetExpiresAt

`func (o *VaultAPIKey) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *VaultAPIKey) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *VaultAPIKey) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *VaultAPIKey) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.

### GetLastUsedAt

`func (o *VaultAPIKey) GetLastUsedAt() time.Time`

GetLastUsedAt returns the LastUsedAt field if non-nil, zero value otherwise.

### GetLastUsedAtOk

`func (o *VaultAPIKey) GetLastUsedAtOk() (*time.Time, bool)`

GetLastUsedAtOk returns a tuple with the LastUsedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastUsedAt

`func (o *VaultAPIKey) SetLastUsedAt(v time.Time)`

SetLastUsedAt sets LastUsedAt field to given value.

### HasLastUsedAt

`func (o *VaultAPIKey) HasLastUsedAt() bool`

HasLastUsedAt returns a boolean if a field has been set.

### GetIsActive

`func (o *VaultAPIKey) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *VaultAPIKey) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *VaultAPIKey) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.


### GetCreatedAt

`func (o *VaultAPIKey) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *VaultAPIKey) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *VaultAPIKey) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *VaultAPIKey) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *VaultAPIKey) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *VaultAPIKey) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *VaultAPIKey) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


