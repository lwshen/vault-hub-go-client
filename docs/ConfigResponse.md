# ConfigResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OidcEnabled** | **bool** | Whether OIDC authentication is enabled | 
**EmailEnabled** | **bool** | Whether transactional email is enabled | 

## Methods

### NewConfigResponse

`func NewConfigResponse(oidcEnabled bool, emailEnabled bool, ) *ConfigResponse`

NewConfigResponse instantiates a new ConfigResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConfigResponseWithDefaults

`func NewConfigResponseWithDefaults() *ConfigResponse`

NewConfigResponseWithDefaults instantiates a new ConfigResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOidcEnabled

`func (o *ConfigResponse) GetOidcEnabled() bool`

GetOidcEnabled returns the OidcEnabled field if non-nil, zero value otherwise.

### GetOidcEnabledOk

`func (o *ConfigResponse) GetOidcEnabledOk() (*bool, bool)`

GetOidcEnabledOk returns a tuple with the OidcEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOidcEnabled

`func (o *ConfigResponse) SetOidcEnabled(v bool)`

SetOidcEnabled sets OidcEnabled field to given value.


### GetEmailEnabled

`func (o *ConfigResponse) GetEmailEnabled() bool`

GetEmailEnabled returns the EmailEnabled field if non-nil, zero value otherwise.

### GetEmailEnabledOk

`func (o *ConfigResponse) GetEmailEnabledOk() (*bool, bool)`

GetEmailEnabledOk returns a tuple with the EmailEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmailEnabled

`func (o *ConfigResponse) SetEmailEnabled(v bool)`

SetEmailEnabled sets EmailEnabled field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


