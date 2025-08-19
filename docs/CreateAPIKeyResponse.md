# CreateAPIKeyResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApiKey** | [**APIKey**](APIKey.md) |  | 
**Key** | **string** | The generated API key (only shown once) | 

## Methods

### NewCreateAPIKeyResponse

`func NewCreateAPIKeyResponse(apiKey APIKey, key string, ) *CreateAPIKeyResponse`

NewCreateAPIKeyResponse instantiates a new CreateAPIKeyResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateAPIKeyResponseWithDefaults

`func NewCreateAPIKeyResponseWithDefaults() *CreateAPIKeyResponse`

NewCreateAPIKeyResponseWithDefaults instantiates a new CreateAPIKeyResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApiKey

`func (o *CreateAPIKeyResponse) GetApiKey() APIKey`

GetApiKey returns the ApiKey field if non-nil, zero value otherwise.

### GetApiKeyOk

`func (o *CreateAPIKeyResponse) GetApiKeyOk() (*APIKey, bool)`

GetApiKeyOk returns a tuple with the ApiKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApiKey

`func (o *CreateAPIKeyResponse) SetApiKey(v APIKey)`

SetApiKey sets ApiKey field to given value.


### GetKey

`func (o *CreateAPIKeyResponse) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *CreateAPIKeyResponse) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *CreateAPIKeyResponse) SetKey(v string)`

SetKey sets Key field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


