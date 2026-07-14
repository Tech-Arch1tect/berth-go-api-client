# RunSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AddedBytes** | **int32** |  | 
**ComponentCount** | **int32** |  | 
**ComponentsWithErrors** | **int32** |  | 
**FinishedAt** | Pointer to **NullableTime** |  | [optional] 
**Id** | **string** |  | 
**RepoSizeBytes** | Pointer to **int32** |  | [optional] 
**SizeBytes** | **int32** |  | 
**StackName** | **string** |  | 
**StartedAt** | **time.Time** |  | 
**Status** | **string** |  | 
**StopMode** | Pointer to **string** |  | [optional] 
**Verified** | Pointer to **NullableBool** |  | [optional] 

## Methods

### NewRunSummary

`func NewRunSummary(addedBytes int32, componentCount int32, componentsWithErrors int32, id string, sizeBytes int32, stackName string, startedAt time.Time, status string, ) *RunSummary`

NewRunSummary instantiates a new RunSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRunSummaryWithDefaults

`func NewRunSummaryWithDefaults() *RunSummary`

NewRunSummaryWithDefaults instantiates a new RunSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddedBytes

`func (o *RunSummary) GetAddedBytes() int32`

GetAddedBytes returns the AddedBytes field if non-nil, zero value otherwise.

### GetAddedBytesOk

`func (o *RunSummary) GetAddedBytesOk() (*int32, bool)`

GetAddedBytesOk returns a tuple with the AddedBytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddedBytes

`func (o *RunSummary) SetAddedBytes(v int32)`

SetAddedBytes sets AddedBytes field to given value.


### GetComponentCount

`func (o *RunSummary) GetComponentCount() int32`

GetComponentCount returns the ComponentCount field if non-nil, zero value otherwise.

### GetComponentCountOk

`func (o *RunSummary) GetComponentCountOk() (*int32, bool)`

GetComponentCountOk returns a tuple with the ComponentCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponentCount

`func (o *RunSummary) SetComponentCount(v int32)`

SetComponentCount sets ComponentCount field to given value.


### GetComponentsWithErrors

`func (o *RunSummary) GetComponentsWithErrors() int32`

GetComponentsWithErrors returns the ComponentsWithErrors field if non-nil, zero value otherwise.

### GetComponentsWithErrorsOk

`func (o *RunSummary) GetComponentsWithErrorsOk() (*int32, bool)`

GetComponentsWithErrorsOk returns a tuple with the ComponentsWithErrors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponentsWithErrors

`func (o *RunSummary) SetComponentsWithErrors(v int32)`

SetComponentsWithErrors sets ComponentsWithErrors field to given value.


### GetFinishedAt

`func (o *RunSummary) GetFinishedAt() time.Time`

GetFinishedAt returns the FinishedAt field if non-nil, zero value otherwise.

### GetFinishedAtOk

`func (o *RunSummary) GetFinishedAtOk() (*time.Time, bool)`

GetFinishedAtOk returns a tuple with the FinishedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinishedAt

`func (o *RunSummary) SetFinishedAt(v time.Time)`

SetFinishedAt sets FinishedAt field to given value.

### HasFinishedAt

`func (o *RunSummary) HasFinishedAt() bool`

HasFinishedAt returns a boolean if a field has been set.

### SetFinishedAtNil

`func (o *RunSummary) SetFinishedAtNil(b bool)`

 SetFinishedAtNil sets the value for FinishedAt to be an explicit nil

### UnsetFinishedAt
`func (o *RunSummary) UnsetFinishedAt()`

UnsetFinishedAt ensures that no value is present for FinishedAt, not even an explicit nil
### GetId

`func (o *RunSummary) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RunSummary) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RunSummary) SetId(v string)`

SetId sets Id field to given value.


### GetRepoSizeBytes

`func (o *RunSummary) GetRepoSizeBytes() int32`

GetRepoSizeBytes returns the RepoSizeBytes field if non-nil, zero value otherwise.

### GetRepoSizeBytesOk

`func (o *RunSummary) GetRepoSizeBytesOk() (*int32, bool)`

GetRepoSizeBytesOk returns a tuple with the RepoSizeBytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepoSizeBytes

`func (o *RunSummary) SetRepoSizeBytes(v int32)`

SetRepoSizeBytes sets RepoSizeBytes field to given value.

### HasRepoSizeBytes

`func (o *RunSummary) HasRepoSizeBytes() bool`

HasRepoSizeBytes returns a boolean if a field has been set.

### GetSizeBytes

`func (o *RunSummary) GetSizeBytes() int32`

GetSizeBytes returns the SizeBytes field if non-nil, zero value otherwise.

### GetSizeBytesOk

`func (o *RunSummary) GetSizeBytesOk() (*int32, bool)`

GetSizeBytesOk returns a tuple with the SizeBytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSizeBytes

`func (o *RunSummary) SetSizeBytes(v int32)`

SetSizeBytes sets SizeBytes field to given value.


### GetStackName

`func (o *RunSummary) GetStackName() string`

GetStackName returns the StackName field if non-nil, zero value otherwise.

### GetStackNameOk

`func (o *RunSummary) GetStackNameOk() (*string, bool)`

GetStackNameOk returns a tuple with the StackName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStackName

`func (o *RunSummary) SetStackName(v string)`

SetStackName sets StackName field to given value.


### GetStartedAt

`func (o *RunSummary) GetStartedAt() time.Time`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *RunSummary) GetStartedAtOk() (*time.Time, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *RunSummary) SetStartedAt(v time.Time)`

SetStartedAt sets StartedAt field to given value.


### GetStatus

`func (o *RunSummary) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *RunSummary) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *RunSummary) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetStopMode

`func (o *RunSummary) GetStopMode() string`

GetStopMode returns the StopMode field if non-nil, zero value otherwise.

### GetStopModeOk

`func (o *RunSummary) GetStopModeOk() (*string, bool)`

GetStopModeOk returns a tuple with the StopMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStopMode

`func (o *RunSummary) SetStopMode(v string)`

SetStopMode sets StopMode field to given value.

### HasStopMode

`func (o *RunSummary) HasStopMode() bool`

HasStopMode returns a boolean if a field has been set.

### GetVerified

`func (o *RunSummary) GetVerified() bool`

GetVerified returns the Verified field if non-nil, zero value otherwise.

### GetVerifiedOk

`func (o *RunSummary) GetVerifiedOk() (*bool, bool)`

GetVerifiedOk returns a tuple with the Verified field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerified

`func (o *RunSummary) SetVerified(v bool)`

SetVerified sets Verified field to given value.

### HasVerified

`func (o *RunSummary) HasVerified() bool`

HasVerified returns a boolean if a field has been set.

### SetVerifiedNil

`func (o *RunSummary) SetVerifiedNil(b bool)`

 SetVerifiedNil sets the value for Verified to be an explicit nil

### UnsetVerified
`func (o *RunSummary) UnsetVerified()`

UnsetVerified ensures that no value is present for Verified, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


