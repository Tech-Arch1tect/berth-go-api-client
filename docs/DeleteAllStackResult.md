# DeleteAllStackResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Attempted** | **bool** |  | 
**Errors** | **[]string** |  | 
**PruneStatus** | **string** |  | 
**RecordsBefore** | **int32** |  | 
**RecordsDeleted** | **int32** |  | 
**RecordsRemaining** | **int32** |  | 
**SnapshotsForgotten** | **int32** |  | 
**StackName** | **string** |  | 

## Methods

### NewDeleteAllStackResult

`func NewDeleteAllStackResult(attempted bool, errors []string, pruneStatus string, recordsBefore int32, recordsDeleted int32, recordsRemaining int32, snapshotsForgotten int32, stackName string, ) *DeleteAllStackResult`

NewDeleteAllStackResult instantiates a new DeleteAllStackResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeleteAllStackResultWithDefaults

`func NewDeleteAllStackResultWithDefaults() *DeleteAllStackResult`

NewDeleteAllStackResultWithDefaults instantiates a new DeleteAllStackResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAttempted

`func (o *DeleteAllStackResult) GetAttempted() bool`

GetAttempted returns the Attempted field if non-nil, zero value otherwise.

### GetAttemptedOk

`func (o *DeleteAllStackResult) GetAttemptedOk() (*bool, bool)`

GetAttemptedOk returns a tuple with the Attempted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttempted

`func (o *DeleteAllStackResult) SetAttempted(v bool)`

SetAttempted sets Attempted field to given value.


### GetErrors

`func (o *DeleteAllStackResult) GetErrors() []string`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *DeleteAllStackResult) GetErrorsOk() (*[]string, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *DeleteAllStackResult) SetErrors(v []string)`

SetErrors sets Errors field to given value.


### GetPruneStatus

`func (o *DeleteAllStackResult) GetPruneStatus() string`

GetPruneStatus returns the PruneStatus field if non-nil, zero value otherwise.

### GetPruneStatusOk

`func (o *DeleteAllStackResult) GetPruneStatusOk() (*string, bool)`

GetPruneStatusOk returns a tuple with the PruneStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPruneStatus

`func (o *DeleteAllStackResult) SetPruneStatus(v string)`

SetPruneStatus sets PruneStatus field to given value.


### GetRecordsBefore

`func (o *DeleteAllStackResult) GetRecordsBefore() int32`

GetRecordsBefore returns the RecordsBefore field if non-nil, zero value otherwise.

### GetRecordsBeforeOk

`func (o *DeleteAllStackResult) GetRecordsBeforeOk() (*int32, bool)`

GetRecordsBeforeOk returns a tuple with the RecordsBefore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecordsBefore

`func (o *DeleteAllStackResult) SetRecordsBefore(v int32)`

SetRecordsBefore sets RecordsBefore field to given value.


### GetRecordsDeleted

`func (o *DeleteAllStackResult) GetRecordsDeleted() int32`

GetRecordsDeleted returns the RecordsDeleted field if non-nil, zero value otherwise.

### GetRecordsDeletedOk

`func (o *DeleteAllStackResult) GetRecordsDeletedOk() (*int32, bool)`

GetRecordsDeletedOk returns a tuple with the RecordsDeleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecordsDeleted

`func (o *DeleteAllStackResult) SetRecordsDeleted(v int32)`

SetRecordsDeleted sets RecordsDeleted field to given value.


### GetRecordsRemaining

`func (o *DeleteAllStackResult) GetRecordsRemaining() int32`

GetRecordsRemaining returns the RecordsRemaining field if non-nil, zero value otherwise.

### GetRecordsRemainingOk

`func (o *DeleteAllStackResult) GetRecordsRemainingOk() (*int32, bool)`

GetRecordsRemainingOk returns a tuple with the RecordsRemaining field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecordsRemaining

`func (o *DeleteAllStackResult) SetRecordsRemaining(v int32)`

SetRecordsRemaining sets RecordsRemaining field to given value.


### GetSnapshotsForgotten

`func (o *DeleteAllStackResult) GetSnapshotsForgotten() int32`

GetSnapshotsForgotten returns the SnapshotsForgotten field if non-nil, zero value otherwise.

### GetSnapshotsForgottenOk

`func (o *DeleteAllStackResult) GetSnapshotsForgottenOk() (*int32, bool)`

GetSnapshotsForgottenOk returns a tuple with the SnapshotsForgotten field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnapshotsForgotten

`func (o *DeleteAllStackResult) SetSnapshotsForgotten(v int32)`

SetSnapshotsForgotten sets SnapshotsForgotten field to given value.


### GetStackName

`func (o *DeleteAllStackResult) GetStackName() string`

GetStackName returns the StackName field if non-nil, zero value otherwise.

### GetStackNameOk

`func (o *DeleteAllStackResult) GetStackNameOk() (*string, bool)`

GetStackNameOk returns a tuple with the StackName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStackName

`func (o *DeleteAllStackResult) SetStackName(v string)`

SetStackName sets StackName field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


