# CreateVaultRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | Human-readable name | 
**Value** | **string** | Value to be encrypted and stored | 
**Description** | Pointer to **string** | Human-readable description | [optional] 
**Category** | Pointer to **string** | Category/type of vault | [optional] 
**Favourite** | Pointer to **bool** | Favourite flag | [optional] [default to false]

## Methods

### NewCreateVaultRequest

`func NewCreateVaultRequest(name string, value string, ) *CreateVaultRequest`

NewCreateVaultRequest instantiates a new CreateVaultRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateVaultRequestWithDefaults

`func NewCreateVaultRequestWithDefaults() *CreateVaultRequest`

NewCreateVaultRequestWithDefaults instantiates a new CreateVaultRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateVaultRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateVaultRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateVaultRequest) SetName(v string)`

SetName sets Name field to given value.


### GetValue

`func (o *CreateVaultRequest) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *CreateVaultRequest) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *CreateVaultRequest) SetValue(v string)`

SetValue sets Value field to given value.


### GetDescription

`func (o *CreateVaultRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreateVaultRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreateVaultRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CreateVaultRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetCategory

`func (o *CreateVaultRequest) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *CreateVaultRequest) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *CreateVaultRequest) SetCategory(v string)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *CreateVaultRequest) HasCategory() bool`

HasCategory returns a boolean if a field has been set.

### GetFavourite

`func (o *CreateVaultRequest) GetFavourite() bool`

GetFavourite returns the Favourite field if non-nil, zero value otherwise.

### GetFavouriteOk

`func (o *CreateVaultRequest) GetFavouriteOk() (*bool, bool)`

GetFavouriteOk returns a tuple with the Favourite field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFavourite

`func (o *CreateVaultRequest) SetFavourite(v bool)`

SetFavourite sets Favourite field to given value.

### HasFavourite

`func (o *CreateVaultRequest) HasFavourite() bool`

HasFavourite returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


