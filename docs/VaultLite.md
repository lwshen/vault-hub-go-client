# VaultLite

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**UniqueId** | **string** | Unique identifier for the vault | 
**Name** | **string** | Human-readable name | 
**Description** | Pointer to **string** | Human-readable description | [optional] 
**Category** | Pointer to **string** | Category/type of vault | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewVaultLite

`func NewVaultLite(uniqueId string, name string, ) *VaultLite`

NewVaultLite instantiates a new VaultLite object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVaultLiteWithDefaults

`func NewVaultLiteWithDefaults() *VaultLite`

NewVaultLiteWithDefaults instantiates a new VaultLite object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUniqueId

`func (o *VaultLite) GetUniqueId() string`

GetUniqueId returns the UniqueId field if non-nil, zero value otherwise.

### GetUniqueIdOk

`func (o *VaultLite) GetUniqueIdOk() (*string, bool)`

GetUniqueIdOk returns a tuple with the UniqueId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUniqueId

`func (o *VaultLite) SetUniqueId(v string)`

SetUniqueId sets UniqueId field to given value.


### GetName

`func (o *VaultLite) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *VaultLite) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *VaultLite) SetName(v string)`

SetName sets Name field to given value.


### GetDescription

`func (o *VaultLite) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *VaultLite) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *VaultLite) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *VaultLite) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetCategory

`func (o *VaultLite) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *VaultLite) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *VaultLite) SetCategory(v string)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *VaultLite) HasCategory() bool`

HasCategory returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *VaultLite) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *VaultLite) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *VaultLite) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *VaultLite) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


