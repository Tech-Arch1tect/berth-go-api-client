# StackBackupSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**LatestRun** | Pointer to [**NullableRunSummary**](RunSummary.md) |  | [optional] 
**RepoSizeBytes** | Pointer to **int32** |  | [optional] 
**RunCount** | **int32** |  | 
**StackExists** | **bool** |  | 
**StackName** | **string** |  | 

## Methods

### NewStackBackupSummary

`func NewStackBackupSummary(runCount int32, stackExists bool, stackName string, ) *StackBackupSummary`

NewStackBackupSummary instantiates a new StackBackupSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStackBackupSummaryWithDefaults

`func NewStackBackupSummaryWithDefaults() *StackBackupSummary`

NewStackBackupSummaryWithDefaults instantiates a new StackBackupSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLatestRun

`func (o *StackBackupSummary) GetLatestRun() RunSummary`

GetLatestRun returns the LatestRun field if non-nil, zero value otherwise.

### GetLatestRunOk

`func (o *StackBackupSummary) GetLatestRunOk() (*RunSummary, bool)`

GetLatestRunOk returns a tuple with the LatestRun field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatestRun

`func (o *StackBackupSummary) SetLatestRun(v RunSummary)`

SetLatestRun sets LatestRun field to given value.

### HasLatestRun

`func (o *StackBackupSummary) HasLatestRun() bool`

HasLatestRun returns a boolean if a field has been set.

### SetLatestRunNil

`func (o *StackBackupSummary) SetLatestRunNil(b bool)`

 SetLatestRunNil sets the value for LatestRun to be an explicit nil

### UnsetLatestRun
`func (o *StackBackupSummary) UnsetLatestRun()`

UnsetLatestRun ensures that no value is present for LatestRun, not even an explicit nil
### GetRepoSizeBytes

`func (o *StackBackupSummary) GetRepoSizeBytes() int32`

GetRepoSizeBytes returns the RepoSizeBytes field if non-nil, zero value otherwise.

### GetRepoSizeBytesOk

`func (o *StackBackupSummary) GetRepoSizeBytesOk() (*int32, bool)`

GetRepoSizeBytesOk returns a tuple with the RepoSizeBytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepoSizeBytes

`func (o *StackBackupSummary) SetRepoSizeBytes(v int32)`

SetRepoSizeBytes sets RepoSizeBytes field to given value.

### HasRepoSizeBytes

`func (o *StackBackupSummary) HasRepoSizeBytes() bool`

HasRepoSizeBytes returns a boolean if a field has been set.

### GetRunCount

`func (o *StackBackupSummary) GetRunCount() int32`

GetRunCount returns the RunCount field if non-nil, zero value otherwise.

### GetRunCountOk

`func (o *StackBackupSummary) GetRunCountOk() (*int32, bool)`

GetRunCountOk returns a tuple with the RunCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunCount

`func (o *StackBackupSummary) SetRunCount(v int32)`

SetRunCount sets RunCount field to given value.


### GetStackExists

`func (o *StackBackupSummary) GetStackExists() bool`

GetStackExists returns the StackExists field if non-nil, zero value otherwise.

### GetStackExistsOk

`func (o *StackBackupSummary) GetStackExistsOk() (*bool, bool)`

GetStackExistsOk returns a tuple with the StackExists field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStackExists

`func (o *StackBackupSummary) SetStackExists(v bool)`

SetStackExists sets StackExists field to given value.


### GetStackName

`func (o *StackBackupSummary) GetStackName() string`

GetStackName returns the StackName field if non-nil, zero value otherwise.

### GetStackNameOk

`func (o *StackBackupSummary) GetStackNameOk() (*string, bool)`

GetStackNameOk returns a tuple with the StackName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStackName

`func (o *StackBackupSummary) SetStackName(v string)`

SetStackName sets StackName field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


