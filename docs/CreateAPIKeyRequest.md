# CreateAPIKeyRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | Human-readable name for the API key | 
**VaultUniqueIds** | Pointer to **[]string** | Array of vault unique IDs this key can access (empty &#x3D; all user&#39;s vaults) | [optional] 
**ExpiresAt** | Pointer to **time.Time** | Optional expiration date | [optional] 

## Methods

### NewCreateAPIKeyRequest

`func NewCreateAPIKeyRequest(name string, ) *CreateAPIKeyRequest`

NewCreateAPIKeyRequest instantiates a new CreateAPIKeyRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateAPIKeyRequestWithDefaults

`func NewCreateAPIKeyRequestWithDefaults() *CreateAPIKeyRequest`

NewCreateAPIKeyRequestWithDefaults instantiates a new CreateAPIKeyRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateAPIKeyRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateAPIKeyRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateAPIKeyRequest) SetName(v string)`

SetName sets Name field to given value.


### GetVaultUniqueIds

`func (o *CreateAPIKeyRequest) GetVaultUniqueIds() []string`

GetVaultUniqueIds returns the VaultUniqueIds field if non-nil, zero value otherwise.

### GetVaultUniqueIdsOk

`func (o *CreateAPIKeyRequest) GetVaultUniqueIdsOk() (*[]string, bool)`

GetVaultUniqueIdsOk returns a tuple with the VaultUniqueIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVaultUniqueIds

`func (o *CreateAPIKeyRequest) SetVaultUniqueIds(v []string)`

SetVaultUniqueIds sets VaultUniqueIds field to given value.

### HasVaultUniqueIds

`func (o *CreateAPIKeyRequest) HasVaultUniqueIds() bool`

HasVaultUniqueIds returns a boolean if a field has been set.

### GetExpiresAt

`func (o *CreateAPIKeyRequest) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *CreateAPIKeyRequest) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *CreateAPIKeyRequest) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *CreateAPIKeyRequest) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


