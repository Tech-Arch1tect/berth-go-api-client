# OperationLog

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Command** | **string** |  | 
**CreatedAt** | **time.Time** |  | 
**DeletedAt** | Pointer to [**DeletedAt**](DeletedAt.md) |  | [optional] 
**DurationMs** | Pointer to **NullableInt32** |  | [optional] 
**EndTime** | Pointer to **NullableTime** |  | [optional] 
**ExitCode** | Pointer to **NullableInt32** |  | [optional] 
**Id** | **int32** |  | 
**LastMessageAt** | Pointer to **NullableTime** |  | [optional] 
**OperationId** | **string** |  | 
**Options** | Pointer to **string** |  | [optional] 
**QueuedAt** | Pointer to **NullableTime** |  | [optional] 
**Server** | [**Server**](Server.md) |  | 
**ServerId** | **int32** |  | 
**Services** | Pointer to **string** |  | [optional] 
**StackName** | **string** |  | 
**StartTime** | Pointer to **time.Time** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**Success** | Pointer to **NullableBool** |  | [optional] 
**Summary** | Pointer to **string** |  | [optional] 
**UpdatedAt** | **time.Time** |  | 
**User** | [**User**](User.md) |  | 
**UserId** | **int32** |  | 

## Methods

### NewOperationLog

`func NewOperationLog(command string, createdAt time.Time, id int32, operationId string, server Server, serverId int32, stackName string, updatedAt time.Time, user User, userId int32, ) *OperationLog`

NewOperationLog instantiates a new OperationLog object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperationLogWithDefaults

`func NewOperationLogWithDefaults() *OperationLog`

NewOperationLogWithDefaults instantiates a new OperationLog object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCommand

`func (o *OperationLog) GetCommand() string`

GetCommand returns the Command field if non-nil, zero value otherwise.

### GetCommandOk

`func (o *OperationLog) GetCommandOk() (*string, bool)`

GetCommandOk returns a tuple with the Command field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommand

`func (o *OperationLog) SetCommand(v string)`

SetCommand sets Command field to given value.


### GetCreatedAt

`func (o *OperationLog) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *OperationLog) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *OperationLog) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetDeletedAt

`func (o *OperationLog) GetDeletedAt() DeletedAt`

GetDeletedAt returns the DeletedAt field if non-nil, zero value otherwise.

### GetDeletedAtOk

`func (o *OperationLog) GetDeletedAtOk() (*DeletedAt, bool)`

GetDeletedAtOk returns a tuple with the DeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedAt

`func (o *OperationLog) SetDeletedAt(v DeletedAt)`

SetDeletedAt sets DeletedAt field to given value.

### HasDeletedAt

`func (o *OperationLog) HasDeletedAt() bool`

HasDeletedAt returns a boolean if a field has been set.

### GetDurationMs

`func (o *OperationLog) GetDurationMs() int32`

GetDurationMs returns the DurationMs field if non-nil, zero value otherwise.

### GetDurationMsOk

`func (o *OperationLog) GetDurationMsOk() (*int32, bool)`

GetDurationMsOk returns a tuple with the DurationMs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDurationMs

`func (o *OperationLog) SetDurationMs(v int32)`

SetDurationMs sets DurationMs field to given value.

### HasDurationMs

`func (o *OperationLog) HasDurationMs() bool`

HasDurationMs returns a boolean if a field has been set.

### SetDurationMsNil

`func (o *OperationLog) SetDurationMsNil(b bool)`

 SetDurationMsNil sets the value for DurationMs to be an explicit nil

### UnsetDurationMs
`func (o *OperationLog) UnsetDurationMs()`

UnsetDurationMs ensures that no value is present for DurationMs, not even an explicit nil
### GetEndTime

`func (o *OperationLog) GetEndTime() time.Time`

GetEndTime returns the EndTime field if non-nil, zero value otherwise.

### GetEndTimeOk

`func (o *OperationLog) GetEndTimeOk() (*time.Time, bool)`

GetEndTimeOk returns a tuple with the EndTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndTime

`func (o *OperationLog) SetEndTime(v time.Time)`

SetEndTime sets EndTime field to given value.

### HasEndTime

`func (o *OperationLog) HasEndTime() bool`

HasEndTime returns a boolean if a field has been set.

### SetEndTimeNil

`func (o *OperationLog) SetEndTimeNil(b bool)`

 SetEndTimeNil sets the value for EndTime to be an explicit nil

### UnsetEndTime
`func (o *OperationLog) UnsetEndTime()`

UnsetEndTime ensures that no value is present for EndTime, not even an explicit nil
### GetExitCode

`func (o *OperationLog) GetExitCode() int32`

GetExitCode returns the ExitCode field if non-nil, zero value otherwise.

### GetExitCodeOk

`func (o *OperationLog) GetExitCodeOk() (*int32, bool)`

GetExitCodeOk returns a tuple with the ExitCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExitCode

`func (o *OperationLog) SetExitCode(v int32)`

SetExitCode sets ExitCode field to given value.

### HasExitCode

`func (o *OperationLog) HasExitCode() bool`

HasExitCode returns a boolean if a field has been set.

### SetExitCodeNil

`func (o *OperationLog) SetExitCodeNil(b bool)`

 SetExitCodeNil sets the value for ExitCode to be an explicit nil

### UnsetExitCode
`func (o *OperationLog) UnsetExitCode()`

UnsetExitCode ensures that no value is present for ExitCode, not even an explicit nil
### GetId

`func (o *OperationLog) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *OperationLog) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *OperationLog) SetId(v int32)`

SetId sets Id field to given value.


### GetLastMessageAt

`func (o *OperationLog) GetLastMessageAt() time.Time`

GetLastMessageAt returns the LastMessageAt field if non-nil, zero value otherwise.

### GetLastMessageAtOk

`func (o *OperationLog) GetLastMessageAtOk() (*time.Time, bool)`

GetLastMessageAtOk returns a tuple with the LastMessageAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastMessageAt

`func (o *OperationLog) SetLastMessageAt(v time.Time)`

SetLastMessageAt sets LastMessageAt field to given value.

### HasLastMessageAt

`func (o *OperationLog) HasLastMessageAt() bool`

HasLastMessageAt returns a boolean if a field has been set.

### SetLastMessageAtNil

`func (o *OperationLog) SetLastMessageAtNil(b bool)`

 SetLastMessageAtNil sets the value for LastMessageAt to be an explicit nil

### UnsetLastMessageAt
`func (o *OperationLog) UnsetLastMessageAt()`

UnsetLastMessageAt ensures that no value is present for LastMessageAt, not even an explicit nil
### GetOperationId

`func (o *OperationLog) GetOperationId() string`

GetOperationId returns the OperationId field if non-nil, zero value otherwise.

### GetOperationIdOk

`func (o *OperationLog) GetOperationIdOk() (*string, bool)`

GetOperationIdOk returns a tuple with the OperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationId

`func (o *OperationLog) SetOperationId(v string)`

SetOperationId sets OperationId field to given value.


### GetOptions

`func (o *OperationLog) GetOptions() string`

GetOptions returns the Options field if non-nil, zero value otherwise.

### GetOptionsOk

`func (o *OperationLog) GetOptionsOk() (*string, bool)`

GetOptionsOk returns a tuple with the Options field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOptions

`func (o *OperationLog) SetOptions(v string)`

SetOptions sets Options field to given value.

### HasOptions

`func (o *OperationLog) HasOptions() bool`

HasOptions returns a boolean if a field has been set.

### GetQueuedAt

`func (o *OperationLog) GetQueuedAt() time.Time`

GetQueuedAt returns the QueuedAt field if non-nil, zero value otherwise.

### GetQueuedAtOk

`func (o *OperationLog) GetQueuedAtOk() (*time.Time, bool)`

GetQueuedAtOk returns a tuple with the QueuedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQueuedAt

`func (o *OperationLog) SetQueuedAt(v time.Time)`

SetQueuedAt sets QueuedAt field to given value.

### HasQueuedAt

`func (o *OperationLog) HasQueuedAt() bool`

HasQueuedAt returns a boolean if a field has been set.

### SetQueuedAtNil

`func (o *OperationLog) SetQueuedAtNil(b bool)`

 SetQueuedAtNil sets the value for QueuedAt to be an explicit nil

### UnsetQueuedAt
`func (o *OperationLog) UnsetQueuedAt()`

UnsetQueuedAt ensures that no value is present for QueuedAt, not even an explicit nil
### GetServer

`func (o *OperationLog) GetServer() Server`

GetServer returns the Server field if non-nil, zero value otherwise.

### GetServerOk

`func (o *OperationLog) GetServerOk() (*Server, bool)`

GetServerOk returns a tuple with the Server field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServer

`func (o *OperationLog) SetServer(v Server)`

SetServer sets Server field to given value.


### GetServerId

`func (o *OperationLog) GetServerId() int32`

GetServerId returns the ServerId field if non-nil, zero value otherwise.

### GetServerIdOk

`func (o *OperationLog) GetServerIdOk() (*int32, bool)`

GetServerIdOk returns a tuple with the ServerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerId

`func (o *OperationLog) SetServerId(v int32)`

SetServerId sets ServerId field to given value.


### GetServices

`func (o *OperationLog) GetServices() string`

GetServices returns the Services field if non-nil, zero value otherwise.

### GetServicesOk

`func (o *OperationLog) GetServicesOk() (*string, bool)`

GetServicesOk returns a tuple with the Services field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServices

`func (o *OperationLog) SetServices(v string)`

SetServices sets Services field to given value.

### HasServices

`func (o *OperationLog) HasServices() bool`

HasServices returns a boolean if a field has been set.

### GetStackName

`func (o *OperationLog) GetStackName() string`

GetStackName returns the StackName field if non-nil, zero value otherwise.

### GetStackNameOk

`func (o *OperationLog) GetStackNameOk() (*string, bool)`

GetStackNameOk returns a tuple with the StackName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStackName

`func (o *OperationLog) SetStackName(v string)`

SetStackName sets StackName field to given value.


### GetStartTime

`func (o *OperationLog) GetStartTime() time.Time`

GetStartTime returns the StartTime field if non-nil, zero value otherwise.

### GetStartTimeOk

`func (o *OperationLog) GetStartTimeOk() (*time.Time, bool)`

GetStartTimeOk returns a tuple with the StartTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartTime

`func (o *OperationLog) SetStartTime(v time.Time)`

SetStartTime sets StartTime field to given value.

### HasStartTime

`func (o *OperationLog) HasStartTime() bool`

HasStartTime returns a boolean if a field has been set.

### GetStatus

`func (o *OperationLog) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *OperationLog) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *OperationLog) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *OperationLog) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetSuccess

`func (o *OperationLog) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *OperationLog) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *OperationLog) SetSuccess(v bool)`

SetSuccess sets Success field to given value.

### HasSuccess

`func (o *OperationLog) HasSuccess() bool`

HasSuccess returns a boolean if a field has been set.

### SetSuccessNil

`func (o *OperationLog) SetSuccessNil(b bool)`

 SetSuccessNil sets the value for Success to be an explicit nil

### UnsetSuccess
`func (o *OperationLog) UnsetSuccess()`

UnsetSuccess ensures that no value is present for Success, not even an explicit nil
### GetSummary

`func (o *OperationLog) GetSummary() string`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *OperationLog) GetSummaryOk() (*string, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *OperationLog) SetSummary(v string)`

SetSummary sets Summary field to given value.

### HasSummary

`func (o *OperationLog) HasSummary() bool`

HasSummary returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *OperationLog) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *OperationLog) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *OperationLog) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetUser

`func (o *OperationLog) GetUser() User`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *OperationLog) GetUserOk() (*User, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *OperationLog) SetUser(v User)`

SetUser sets User field to given value.


### GetUserId

`func (o *OperationLog) GetUserId() int32`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *OperationLog) GetUserIdOk() (*int32, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *OperationLog) SetUserId(v int32)`

SetUserId sets UserId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


