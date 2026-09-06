# AbandonBackupStorageResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**After** | [**HistoryState**](HistoryState.md) |  | 
**Before** | [**HistoryState**](HistoryState.md) |  | 
**Complete** | **bool** |  | 
**Errors** | **[]string** |  | 

## Methods

### NewAbandonBackupStorageResult

`func NewAbandonBackupStorageResult(after HistoryState, before HistoryState, complete bool, errors []string, ) *AbandonBackupStorageResult`

NewAbandonBackupStorageResult instantiates a new AbandonBackupStorageResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAbandonBackupStorageResultWithDefaults

`func NewAbandonBackupStorageResultWithDefaults() *AbandonBackupStorageResult`

NewAbandonBackupStorageResultWithDefaults instantiates a new AbandonBackupStorageResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAfter

`func (o *AbandonBackupStorageResult) GetAfter() HistoryState`

GetAfter returns the After field if non-nil, zero value otherwise.

### GetAfterOk

`func (o *AbandonBackupStorageResult) GetAfterOk() (*HistoryState, bool)`

GetAfterOk returns a tuple with the After field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAfter

`func (o *AbandonBackupStorageResult) SetAfter(v HistoryState)`

SetAfter sets After field to given value.


### GetBefore

`func (o *AbandonBackupStorageResult) GetBefore() HistoryState`

GetBefore returns the Before field if non-nil, zero value otherwise.

### GetBeforeOk

`func (o *AbandonBackupStorageResult) GetBeforeOk() (*HistoryState, bool)`

GetBeforeOk returns a tuple with the Before field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBefore

`func (o *AbandonBackupStorageResult) SetBefore(v HistoryState)`

SetBefore sets Before field to given value.


### GetComplete

`func (o *AbandonBackupStorageResult) GetComplete() bool`

GetComplete returns the Complete field if non-nil, zero value otherwise.

### GetCompleteOk

`func (o *AbandonBackupStorageResult) GetCompleteOk() (*bool, bool)`

GetCompleteOk returns a tuple with the Complete field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComplete

`func (o *AbandonBackupStorageResult) SetComplete(v bool)`

SetComplete sets Complete field to given value.


### GetErrors

`func (o *AbandonBackupStorageResult) GetErrors() []string`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *AbandonBackupStorageResult) GetErrorsOk() (*[]string, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *AbandonBackupStorageResult) SetErrors(v []string)`

SetErrors sets Errors field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


