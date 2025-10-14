# PasswordResetConfirmRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Token** | **string** |  | 
**NewPassword** | **string** |  | 

## Methods

### NewPasswordResetConfirmRequest

`func NewPasswordResetConfirmRequest(token string, newPassword string, ) *PasswordResetConfirmRequest`

NewPasswordResetConfirmRequest instantiates a new PasswordResetConfirmRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPasswordResetConfirmRequestWithDefaults

`func NewPasswordResetConfirmRequestWithDefaults() *PasswordResetConfirmRequest`

NewPasswordResetConfirmRequestWithDefaults instantiates a new PasswordResetConfirmRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetToken

`func (o *PasswordResetConfirmRequest) GetToken() string`

GetToken returns the Token field if non-nil, zero value otherwise.

### GetTokenOk

`func (o *PasswordResetConfirmRequest) GetTokenOk() (*string, bool)`

GetTokenOk returns a tuple with the Token field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToken

`func (o *PasswordResetConfirmRequest) SetToken(v string)`

SetToken sets Token field to given value.


### GetNewPassword

`func (o *PasswordResetConfirmRequest) GetNewPassword() string`

GetNewPassword returns the NewPassword field if non-nil, zero value otherwise.

### GetNewPasswordOk

`func (o *PasswordResetConfirmRequest) GetNewPasswordOk() (*string, bool)`

GetNewPasswordOk returns a tuple with the NewPassword field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewPassword

`func (o *PasswordResetConfirmRequest) SetNewPassword(v string)`

SetNewPassword sets NewPassword field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


