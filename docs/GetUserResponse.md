# GetUserResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Email** | **string** |  | 
**Name** | Pointer to **string** |  | [optional] 
**Avatar** | Pointer to **string** |  | [optional] 

## Methods

### NewGetUserResponse

`func NewGetUserResponse(email string, ) *GetUserResponse`

NewGetUserResponse instantiates a new GetUserResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetUserResponseWithDefaults

`func NewGetUserResponseWithDefaults() *GetUserResponse`

NewGetUserResponseWithDefaults instantiates a new GetUserResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEmail

`func (o *GetUserResponse) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *GetUserResponse) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *GetUserResponse) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetName

`func (o *GetUserResponse) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *GetUserResponse) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *GetUserResponse) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *GetUserResponse) HasName() bool`

HasName returns a boolean if a field has been set.

### GetAvatar

`func (o *GetUserResponse) GetAvatar() string`

GetAvatar returns the Avatar field if non-nil, zero value otherwise.

### GetAvatarOk

`func (o *GetUserResponse) GetAvatarOk() (*string, bool)`

GetAvatarOk returns a tuple with the Avatar field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvatar

`func (o *GetUserResponse) SetAvatar(v string)`

SetAvatar sets Avatar field to given value.

### HasAvatar

`func (o *GetUserResponse) HasAvatar() bool`

HasAvatar returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


