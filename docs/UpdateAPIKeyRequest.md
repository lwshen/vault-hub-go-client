# UpdateAPIKeyRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** | Human-readable name for the API key | [optional] 
**VaultUniqueIds** | Pointer to **[]string** | Array of vault unique IDs this key can access (empty &#x3D; all user&#39;s vaults) | [optional] 
**ExpiresAt** | Pointer to **time.Time** | Optional expiration date | [optional] 
**IsActive** | Pointer to **bool** | Enable or disable the API key | [optional] 

## Methods

### NewUpdateAPIKeyRequest

`func NewUpdateAPIKeyRequest() *UpdateAPIKeyRequest`

NewUpdateAPIKeyRequest instantiates a new UpdateAPIKeyRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateAPIKeyRequestWithDefaults

`func NewUpdateAPIKeyRequestWithDefaults() *UpdateAPIKeyRequest`

NewUpdateAPIKeyRequestWithDefaults instantiates a new UpdateAPIKeyRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *UpdateAPIKeyRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UpdateAPIKeyRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UpdateAPIKeyRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *UpdateAPIKeyRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetVaultUniqueIds

`func (o *UpdateAPIKeyRequest) GetVaultUniqueIds() []string`

GetVaultUniqueIds returns the VaultUniqueIds field if non-nil, zero value otherwise.

### GetVaultUniqueIdsOk

`func (o *UpdateAPIKeyRequest) GetVaultUniqueIdsOk() (*[]string, bool)`

GetVaultUniqueIdsOk returns a tuple with the VaultUniqueIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVaultUniqueIds

`func (o *UpdateAPIKeyRequest) SetVaultUniqueIds(v []string)`

SetVaultUniqueIds sets VaultUniqueIds field to given value.

### HasVaultUniqueIds

`func (o *UpdateAPIKeyRequest) HasVaultUniqueIds() bool`

HasVaultUniqueIds returns a boolean if a field has been set.

### GetExpiresAt

`func (o *UpdateAPIKeyRequest) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *UpdateAPIKeyRequest) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *UpdateAPIKeyRequest) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *UpdateAPIKeyRequest) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.

### GetIsActive

`func (o *UpdateAPIKeyRequest) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *UpdateAPIKeyRequest) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *UpdateAPIKeyRequest) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.

### HasIsActive

`func (o *UpdateAPIKeyRequest) HasIsActive() bool`

HasIsActive returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


