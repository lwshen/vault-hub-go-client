# APIKey

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

### NewAPIKey

`func NewAPIKey(id int64, name string, isActive bool, createdAt time.Time, ) *APIKey`

NewAPIKey instantiates a new APIKey object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAPIKeyWithDefaults

`func NewAPIKeyWithDefaults() *APIKey`

NewAPIKeyWithDefaults instantiates a new APIKey object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *APIKey) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *APIKey) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *APIKey) SetId(v int64)`

SetId sets Id field to given value.


### GetName

`func (o *APIKey) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *APIKey) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *APIKey) SetName(v string)`

SetName sets Name field to given value.


### GetVaults

`func (o *APIKey) GetVaults() []VaultLite`

GetVaults returns the Vaults field if non-nil, zero value otherwise.

### GetVaultsOk

`func (o *APIKey) GetVaultsOk() (*[]VaultLite, bool)`

GetVaultsOk returns a tuple with the Vaults field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVaults

`func (o *APIKey) SetVaults(v []VaultLite)`

SetVaults sets Vaults field to given value.

### HasVaults

`func (o *APIKey) HasVaults() bool`

HasVaults returns a boolean if a field has been set.

### GetExpiresAt

`func (o *APIKey) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *APIKey) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *APIKey) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *APIKey) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.

### GetLastUsedAt

`func (o *APIKey) GetLastUsedAt() time.Time`

GetLastUsedAt returns the LastUsedAt field if non-nil, zero value otherwise.

### GetLastUsedAtOk

`func (o *APIKey) GetLastUsedAtOk() (*time.Time, bool)`

GetLastUsedAtOk returns a tuple with the LastUsedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastUsedAt

`func (o *APIKey) SetLastUsedAt(v time.Time)`

SetLastUsedAt sets LastUsedAt field to given value.

### HasLastUsedAt

`func (o *APIKey) HasLastUsedAt() bool`

HasLastUsedAt returns a boolean if a field has been set.

### GetIsActive

`func (o *APIKey) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *APIKey) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *APIKey) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.


### GetCreatedAt

`func (o *APIKey) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *APIKey) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *APIKey) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *APIKey) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *APIKey) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *APIKey) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *APIKey) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


