# EmailTokenResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** | Indicates whether the email token request was accepted | 
**Code** | **string** | Machine-readable status code describing the outcome | 

## Methods

### NewEmailTokenResponse

`func NewEmailTokenResponse(success bool, code string, ) *EmailTokenResponse`

NewEmailTokenResponse instantiates a new EmailTokenResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEmailTokenResponseWithDefaults

`func NewEmailTokenResponseWithDefaults() *EmailTokenResponse`

NewEmailTokenResponseWithDefaults instantiates a new EmailTokenResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *EmailTokenResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *EmailTokenResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *EmailTokenResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetCode

`func (o *EmailTokenResponse) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *EmailTokenResponse) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *EmailTokenResponse) SetCode(v string)`

SetCode sets Code field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


