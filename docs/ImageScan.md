# ImageScan

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AgentScanId** | **string** |  | 
**CompletedAt** | Pointer to **NullableTime** |  | [optional] 
**CreatedAt** | **time.Time** |  | 
**DeletedAt** | Pointer to [**DeletedAt**](DeletedAt.md) |  | [optional] 
**ErrorMessage** | Pointer to **string** |  | [optional] 
**Id** | **int32** |  | 
**LastPollError** | Pointer to **string** |  | [optional] 
**LastPolledAt** | Pointer to **NullableTime** |  | [optional] 
**PollFailures** | **int32** |  | 
**ScannedImages** | **int32** |  | 
**Scopes** | Pointer to [**[]ScanScope**](ScanScope.md) |  | [optional] 
**ServerId** | **int32** |  | 
**ServiceFilter** | Pointer to **string** |  | [optional] 
**StackName** | **string** |  | 
**StartedAt** | **time.Time** |  | 
**Status** | **string** |  | 
**TotalImages** | **int32** |  | 
**UpdatedAt** | **time.Time** |  | 
**Vulnerabilities** | Pointer to [**[]ImageVulnerability**](ImageVulnerability.md) |  | [optional] 

## Methods

### NewImageScan

`func NewImageScan(agentScanId string, createdAt time.Time, id int32, pollFailures int32, scannedImages int32, serverId int32, stackName string, startedAt time.Time, status string, totalImages int32, updatedAt time.Time, ) *ImageScan`

NewImageScan instantiates a new ImageScan object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImageScanWithDefaults

`func NewImageScanWithDefaults() *ImageScan`

NewImageScanWithDefaults instantiates a new ImageScan object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAgentScanId

`func (o *ImageScan) GetAgentScanId() string`

GetAgentScanId returns the AgentScanId field if non-nil, zero value otherwise.

### GetAgentScanIdOk

`func (o *ImageScan) GetAgentScanIdOk() (*string, bool)`

GetAgentScanIdOk returns a tuple with the AgentScanId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgentScanId

`func (o *ImageScan) SetAgentScanId(v string)`

SetAgentScanId sets AgentScanId field to given value.


### GetCompletedAt

`func (o *ImageScan) GetCompletedAt() time.Time`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *ImageScan) GetCompletedAtOk() (*time.Time, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *ImageScan) SetCompletedAt(v time.Time)`

SetCompletedAt sets CompletedAt field to given value.

### HasCompletedAt

`func (o *ImageScan) HasCompletedAt() bool`

HasCompletedAt returns a boolean if a field has been set.

### SetCompletedAtNil

`func (o *ImageScan) SetCompletedAtNil(b bool)`

 SetCompletedAtNil sets the value for CompletedAt to be an explicit nil

### UnsetCompletedAt
`func (o *ImageScan) UnsetCompletedAt()`

UnsetCompletedAt ensures that no value is present for CompletedAt, not even an explicit nil
### GetCreatedAt

`func (o *ImageScan) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ImageScan) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ImageScan) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetDeletedAt

`func (o *ImageScan) GetDeletedAt() DeletedAt`

GetDeletedAt returns the DeletedAt field if non-nil, zero value otherwise.

### GetDeletedAtOk

`func (o *ImageScan) GetDeletedAtOk() (*DeletedAt, bool)`

GetDeletedAtOk returns a tuple with the DeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedAt

`func (o *ImageScan) SetDeletedAt(v DeletedAt)`

SetDeletedAt sets DeletedAt field to given value.

### HasDeletedAt

`func (o *ImageScan) HasDeletedAt() bool`

HasDeletedAt returns a boolean if a field has been set.

### GetErrorMessage

`func (o *ImageScan) GetErrorMessage() string`

GetErrorMessage returns the ErrorMessage field if non-nil, zero value otherwise.

### GetErrorMessageOk

`func (o *ImageScan) GetErrorMessageOk() (*string, bool)`

GetErrorMessageOk returns a tuple with the ErrorMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorMessage

`func (o *ImageScan) SetErrorMessage(v string)`

SetErrorMessage sets ErrorMessage field to given value.

### HasErrorMessage

`func (o *ImageScan) HasErrorMessage() bool`

HasErrorMessage returns a boolean if a field has been set.

### GetId

`func (o *ImageScan) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ImageScan) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ImageScan) SetId(v int32)`

SetId sets Id field to given value.


### GetLastPollError

`func (o *ImageScan) GetLastPollError() string`

GetLastPollError returns the LastPollError field if non-nil, zero value otherwise.

### GetLastPollErrorOk

`func (o *ImageScan) GetLastPollErrorOk() (*string, bool)`

GetLastPollErrorOk returns a tuple with the LastPollError field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastPollError

`func (o *ImageScan) SetLastPollError(v string)`

SetLastPollError sets LastPollError field to given value.

### HasLastPollError

`func (o *ImageScan) HasLastPollError() bool`

HasLastPollError returns a boolean if a field has been set.

### GetLastPolledAt

`func (o *ImageScan) GetLastPolledAt() time.Time`

GetLastPolledAt returns the LastPolledAt field if non-nil, zero value otherwise.

### GetLastPolledAtOk

`func (o *ImageScan) GetLastPolledAtOk() (*time.Time, bool)`

GetLastPolledAtOk returns a tuple with the LastPolledAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastPolledAt

`func (o *ImageScan) SetLastPolledAt(v time.Time)`

SetLastPolledAt sets LastPolledAt field to given value.

### HasLastPolledAt

`func (o *ImageScan) HasLastPolledAt() bool`

HasLastPolledAt returns a boolean if a field has been set.

### SetLastPolledAtNil

`func (o *ImageScan) SetLastPolledAtNil(b bool)`

 SetLastPolledAtNil sets the value for LastPolledAt to be an explicit nil

### UnsetLastPolledAt
`func (o *ImageScan) UnsetLastPolledAt()`

UnsetLastPolledAt ensures that no value is present for LastPolledAt, not even an explicit nil
### GetPollFailures

`func (o *ImageScan) GetPollFailures() int32`

GetPollFailures returns the PollFailures field if non-nil, zero value otherwise.

### GetPollFailuresOk

`func (o *ImageScan) GetPollFailuresOk() (*int32, bool)`

GetPollFailuresOk returns a tuple with the PollFailures field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPollFailures

`func (o *ImageScan) SetPollFailures(v int32)`

SetPollFailures sets PollFailures field to given value.


### GetScannedImages

`func (o *ImageScan) GetScannedImages() int32`

GetScannedImages returns the ScannedImages field if non-nil, zero value otherwise.

### GetScannedImagesOk

`func (o *ImageScan) GetScannedImagesOk() (*int32, bool)`

GetScannedImagesOk returns a tuple with the ScannedImages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScannedImages

`func (o *ImageScan) SetScannedImages(v int32)`

SetScannedImages sets ScannedImages field to given value.


### GetScopes

`func (o *ImageScan) GetScopes() []ScanScope`

GetScopes returns the Scopes field if non-nil, zero value otherwise.

### GetScopesOk

`func (o *ImageScan) GetScopesOk() (*[]ScanScope, bool)`

GetScopesOk returns a tuple with the Scopes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScopes

`func (o *ImageScan) SetScopes(v []ScanScope)`

SetScopes sets Scopes field to given value.

### HasScopes

`func (o *ImageScan) HasScopes() bool`

HasScopes returns a boolean if a field has been set.

### GetServerId

`func (o *ImageScan) GetServerId() int32`

GetServerId returns the ServerId field if non-nil, zero value otherwise.

### GetServerIdOk

`func (o *ImageScan) GetServerIdOk() (*int32, bool)`

GetServerIdOk returns a tuple with the ServerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerId

`func (o *ImageScan) SetServerId(v int32)`

SetServerId sets ServerId field to given value.


### GetServiceFilter

`func (o *ImageScan) GetServiceFilter() string`

GetServiceFilter returns the ServiceFilter field if non-nil, zero value otherwise.

### GetServiceFilterOk

`func (o *ImageScan) GetServiceFilterOk() (*string, bool)`

GetServiceFilterOk returns a tuple with the ServiceFilter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceFilter

`func (o *ImageScan) SetServiceFilter(v string)`

SetServiceFilter sets ServiceFilter field to given value.

### HasServiceFilter

`func (o *ImageScan) HasServiceFilter() bool`

HasServiceFilter returns a boolean if a field has been set.

### GetStackName

`func (o *ImageScan) GetStackName() string`

GetStackName returns the StackName field if non-nil, zero value otherwise.

### GetStackNameOk

`func (o *ImageScan) GetStackNameOk() (*string, bool)`

GetStackNameOk returns a tuple with the StackName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStackName

`func (o *ImageScan) SetStackName(v string)`

SetStackName sets StackName field to given value.


### GetStartedAt

`func (o *ImageScan) GetStartedAt() time.Time`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *ImageScan) GetStartedAtOk() (*time.Time, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *ImageScan) SetStartedAt(v time.Time)`

SetStartedAt sets StartedAt field to given value.


### GetStatus

`func (o *ImageScan) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ImageScan) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ImageScan) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetTotalImages

`func (o *ImageScan) GetTotalImages() int32`

GetTotalImages returns the TotalImages field if non-nil, zero value otherwise.

### GetTotalImagesOk

`func (o *ImageScan) GetTotalImagesOk() (*int32, bool)`

GetTotalImagesOk returns a tuple with the TotalImages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalImages

`func (o *ImageScan) SetTotalImages(v int32)`

SetTotalImages sets TotalImages field to given value.


### GetUpdatedAt

`func (o *ImageScan) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ImageScan) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ImageScan) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetVulnerabilities

`func (o *ImageScan) GetVulnerabilities() []ImageVulnerability`

GetVulnerabilities returns the Vulnerabilities field if non-nil, zero value otherwise.

### GetVulnerabilitiesOk

`func (o *ImageScan) GetVulnerabilitiesOk() (*[]ImageVulnerability, bool)`

GetVulnerabilitiesOk returns a tuple with the Vulnerabilities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVulnerabilities

`func (o *ImageScan) SetVulnerabilities(v []ImageVulnerability)`

SetVulnerabilities sets Vulnerabilities field to given value.

### HasVulnerabilities

`func (o *ImageScan) HasVulnerabilities() bool`

HasVulnerabilities returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


