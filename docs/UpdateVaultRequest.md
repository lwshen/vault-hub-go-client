# UpdateVaultRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** | Human-readable name | [optional] 
**Value** | Pointer to **string** | Value to be encrypted and stored | [optional] 
**Description** | Pointer to **string** | Human-readable description | [optional] 
**Category** | Pointer to **string** | Category/type of vault | [optional] 

## Methods

### NewUpdateVaultRequest

`func NewUpdateVaultRequest() *UpdateVaultRequest`

NewUpdateVaultRequest instantiates a new UpdateVaultRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateVaultRequestWithDefaults

`func NewUpdateVaultRequestWithDefaults() *UpdateVaultRequest`

NewUpdateVaultRequestWithDefaults instantiates a new UpdateVaultRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *UpdateVaultRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UpdateVaultRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UpdateVaultRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *UpdateVaultRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetValue

`func (o *UpdateVaultRequest) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *UpdateVaultRequest) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *UpdateVaultRequest) SetValue(v string)`

SetValue sets Value field to given value.

### HasValue

`func (o *UpdateVaultRequest) HasValue() bool`

HasValue returns a boolean if a field has been set.

### GetDescription

`func (o *UpdateVaultRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *UpdateVaultRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *UpdateVaultRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *UpdateVaultRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetCategory

`func (o *UpdateVaultRequest) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *UpdateVaultRequest) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *UpdateVaultRequest) SetCategory(v string)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *UpdateVaultRequest) HasCategory() bool`

HasCategory returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


