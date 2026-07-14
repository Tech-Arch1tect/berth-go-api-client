# Run

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Components** | [**[]Component**](Component.md) |  | 
**Error** | Pointer to **string** |  | [optional] 
**FinishedAt** | Pointer to **NullableTime** |  | [optional] 
**Id** | **string** |  | 
**RepoSizeBytes** | Pointer to **int32** |  | [optional] 
**ResticVersion** | Pointer to **string** |  | [optional] 
**Skipped** | Pointer to [**[]SkippedMount**](SkippedMount.md) |  | [optional] 
**StackName** | **string** |  | 
**StartedAt** | **time.Time** |  | 
**Status** | **string** |  | 
**StopMode** | Pointer to **string** |  | [optional] 
**Verified** | Pointer to **NullableBool** |  | [optional] 
**VerifyError** | Pointer to **string** |  | [optional] 

## Methods

### NewRun

`func NewRun(components []Component, id string, stackName string, startedAt time.Time, status string, ) *Run`

NewRun instantiates a new Run object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRunWithDefaults

`func NewRunWithDefaults() *Run`

NewRunWithDefaults instantiates a new Run object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetComponents

`func (o *Run) GetComponents() []Component`

GetComponents returns the Components field if non-nil, zero value otherwise.

### GetComponentsOk

`func (o *Run) GetComponentsOk() (*[]Component, bool)`

GetComponentsOk returns a tuple with the Components field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponents

`func (o *Run) SetComponents(v []Component)`

SetComponents sets Components field to given value.


### GetError

`func (o *Run) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *Run) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *Run) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *Run) HasError() bool`

HasError returns a boolean if a field has been set.

### GetFinishedAt

`func (o *Run) GetFinishedAt() time.Time`

GetFinishedAt returns the FinishedAt field if non-nil, zero value otherwise.

### GetFinishedAtOk

`func (o *Run) GetFinishedAtOk() (*time.Time, bool)`

GetFinishedAtOk returns a tuple with the FinishedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinishedAt

`func (o *Run) SetFinishedAt(v time.Time)`

SetFinishedAt sets FinishedAt field to given value.

### HasFinishedAt

`func (o *Run) HasFinishedAt() bool`

HasFinishedAt returns a boolean if a field has been set.

### SetFinishedAtNil

`func (o *Run) SetFinishedAtNil(b bool)`

 SetFinishedAtNil sets the value for FinishedAt to be an explicit nil

### UnsetFinishedAt
`func (o *Run) UnsetFinishedAt()`

UnsetFinishedAt ensures that no value is present for FinishedAt, not even an explicit nil
### GetId

`func (o *Run) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Run) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Run) SetId(v string)`

SetId sets Id field to given value.


### GetRepoSizeBytes

`func (o *Run) GetRepoSizeBytes() int32`

GetRepoSizeBytes returns the RepoSizeBytes field if non-nil, zero value otherwise.

### GetRepoSizeBytesOk

`func (o *Run) GetRepoSizeBytesOk() (*int32, bool)`

GetRepoSizeBytesOk returns a tuple with the RepoSizeBytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepoSizeBytes

`func (o *Run) SetRepoSizeBytes(v int32)`

SetRepoSizeBytes sets RepoSizeBytes field to given value.

### HasRepoSizeBytes

`func (o *Run) HasRepoSizeBytes() bool`

HasRepoSizeBytes returns a boolean if a field has been set.

### GetResticVersion

`func (o *Run) GetResticVersion() string`

GetResticVersion returns the ResticVersion field if non-nil, zero value otherwise.

### GetResticVersionOk

`func (o *Run) GetResticVersionOk() (*string, bool)`

GetResticVersionOk returns a tuple with the ResticVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResticVersion

`func (o *Run) SetResticVersion(v string)`

SetResticVersion sets ResticVersion field to given value.

### HasResticVersion

`func (o *Run) HasResticVersion() bool`

HasResticVersion returns a boolean if a field has been set.

### GetSkipped

`func (o *Run) GetSkipped() []SkippedMount`

GetSkipped returns the Skipped field if non-nil, zero value otherwise.

### GetSkippedOk

`func (o *Run) GetSkippedOk() (*[]SkippedMount, bool)`

GetSkippedOk returns a tuple with the Skipped field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSkipped

`func (o *Run) SetSkipped(v []SkippedMount)`

SetSkipped sets Skipped field to given value.

### HasSkipped

`func (o *Run) HasSkipped() bool`

HasSkipped returns a boolean if a field has been set.

### GetStackName

`func (o *Run) GetStackName() string`

GetStackName returns the StackName field if non-nil, zero value otherwise.

### GetStackNameOk

`func (o *Run) GetStackNameOk() (*string, bool)`

GetStackNameOk returns a tuple with the StackName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStackName

`func (o *Run) SetStackName(v string)`

SetStackName sets StackName field to given value.


### GetStartedAt

`func (o *Run) GetStartedAt() time.Time`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *Run) GetStartedAtOk() (*time.Time, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *Run) SetStartedAt(v time.Time)`

SetStartedAt sets StartedAt field to given value.


### GetStatus

`func (o *Run) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Run) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Run) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetStopMode

`func (o *Run) GetStopMode() string`

GetStopMode returns the StopMode field if non-nil, zero value otherwise.

### GetStopModeOk

`func (o *Run) GetStopModeOk() (*string, bool)`

GetStopModeOk returns a tuple with the StopMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStopMode

`func (o *Run) SetStopMode(v string)`

SetStopMode sets StopMode field to given value.

### HasStopMode

`func (o *Run) HasStopMode() bool`

HasStopMode returns a boolean if a field has been set.

### GetVerified

`func (o *Run) GetVerified() bool`

GetVerified returns the Verified field if non-nil, zero value otherwise.

### GetVerifiedOk

`func (o *Run) GetVerifiedOk() (*bool, bool)`

GetVerifiedOk returns a tuple with the Verified field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerified

`func (o *Run) SetVerified(v bool)`

SetVerified sets Verified field to given value.

### HasVerified

`func (o *Run) HasVerified() bool`

HasVerified returns a boolean if a field has been set.

### SetVerifiedNil

`func (o *Run) SetVerifiedNil(b bool)`

 SetVerifiedNil sets the value for Verified to be an explicit nil

### UnsetVerified
`func (o *Run) UnsetVerified()`

UnsetVerified ensures that no value is present for Verified, not even an explicit nil
### GetVerifyError

`func (o *Run) GetVerifyError() string`

GetVerifyError returns the VerifyError field if non-nil, zero value otherwise.

### GetVerifyErrorOk

`func (o *Run) GetVerifyErrorOk() (*string, bool)`

GetVerifyErrorOk returns a tuple with the VerifyError field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerifyError

`func (o *Run) SetVerifyError(v string)`

SetVerifyError sets VerifyError field to given value.

### HasVerifyError

`func (o *Run) HasVerifyError() bool`

HasVerifyError returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


