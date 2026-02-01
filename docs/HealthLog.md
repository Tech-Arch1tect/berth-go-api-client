# HealthLog

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**End** | Pointer to **string** |  | [optional] 
**ExitCode** | **int32** |  | 
**Output** | **string** |  | 
**Start** | **string** |  | 

## Methods

### NewHealthLog

`func NewHealthLog(exitCode int32, output string, start string, ) *HealthLog`

NewHealthLog instantiates a new HealthLog object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHealthLogWithDefaults

`func NewHealthLogWithDefaults() *HealthLog`

NewHealthLogWithDefaults instantiates a new HealthLog object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnd

`func (o *HealthLog) GetEnd() string`

GetEnd returns the End field if non-nil, zero value otherwise.

### GetEndOk

`func (o *HealthLog) GetEndOk() (*string, bool)`

GetEndOk returns a tuple with the End field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnd

`func (o *HealthLog) SetEnd(v string)`

SetEnd sets End field to given value.

### HasEnd

`func (o *HealthLog) HasEnd() bool`

HasEnd returns a boolean if a field has been set.

### GetExitCode

`func (o *HealthLog) GetExitCode() int32`

GetExitCode returns the ExitCode field if non-nil, zero value otherwise.

### GetExitCodeOk

`func (o *HealthLog) GetExitCodeOk() (*int32, bool)`

GetExitCodeOk returns a tuple with the ExitCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExitCode

`func (o *HealthLog) SetExitCode(v int32)`

SetExitCode sets ExitCode field to given value.


### GetOutput

`func (o *HealthLog) GetOutput() string`

GetOutput returns the Output field if non-nil, zero value otherwise.

### GetOutputOk

`func (o *HealthLog) GetOutputOk() (*string, bool)`

GetOutputOk returns a tuple with the Output field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutput

`func (o *HealthLog) SetOutput(v string)`

SetOutput sets Output field to given value.


### GetStart

`func (o *HealthLog) GetStart() string`

GetStart returns the Start field if non-nil, zero value otherwise.

### GetStartOk

`func (o *HealthLog) GetStartOk() (*string, bool)`

GetStartOk returns a tuple with the Start field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStart

`func (o *HealthLog) SetStart(v string)`

SetStart sets Start field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


