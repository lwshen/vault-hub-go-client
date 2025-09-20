# StatusResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Version** | **string** | Application version | 
**Commit** | **string** | Git commit hash | 
**SystemStatus** | **string** | System operational status | 
**DatabaseStatus** | **string** | Database connection status | 

## Methods

### NewStatusResponse

`func NewStatusResponse(version string, commit string, systemStatus string, databaseStatus string, ) *StatusResponse`

NewStatusResponse instantiates a new StatusResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStatusResponseWithDefaults

`func NewStatusResponseWithDefaults() *StatusResponse`

NewStatusResponseWithDefaults instantiates a new StatusResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetVersion

`func (o *StatusResponse) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *StatusResponse) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *StatusResponse) SetVersion(v string)`

SetVersion sets Version field to given value.


### GetCommit

`func (o *StatusResponse) GetCommit() string`

GetCommit returns the Commit field if non-nil, zero value otherwise.

### GetCommitOk

`func (o *StatusResponse) GetCommitOk() (*string, bool)`

GetCommitOk returns a tuple with the Commit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommit

`func (o *StatusResponse) SetCommit(v string)`

SetCommit sets Commit field to given value.


### GetSystemStatus

`func (o *StatusResponse) GetSystemStatus() string`

GetSystemStatus returns the SystemStatus field if non-nil, zero value otherwise.

### GetSystemStatusOk

`func (o *StatusResponse) GetSystemStatusOk() (*string, bool)`

GetSystemStatusOk returns a tuple with the SystemStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSystemStatus

`func (o *StatusResponse) SetSystemStatus(v string)`

SetSystemStatus sets SystemStatus field to given value.


### GetDatabaseStatus

`func (o *StatusResponse) GetDatabaseStatus() string`

GetDatabaseStatus returns the DatabaseStatus field if non-nil, zero value otherwise.

### GetDatabaseStatusOk

`func (o *StatusResponse) GetDatabaseStatusOk() (*string, bool)`

GetDatabaseStatusOk returns a tuple with the DatabaseStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatabaseStatus

`func (o *StatusResponse) SetDatabaseStatus(v string)`

SetDatabaseStatus sets DatabaseStatus field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


