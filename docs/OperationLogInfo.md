# OperationLogInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Command** | **string** |  | 
**CreatedAt** | **time.Time** |  | 
**DeletedAt** | Pointer to [**DeletedAt**](DeletedAt.md) |  | [optional] 
**DurationMs** | Pointer to **NullableInt32** |  | [optional] 
**EndTime** | Pointer to **NullableTime** |  | [optional] 
**ExitCode** | Pointer to **NullableInt32** |  | [optional] 
**FormattedDate** | **string** |  | 
**Id** | **int32** |  | 
**IsIncomplete** | **bool** |  | 
**LastMessageAt** | Pointer to **NullableTime** |  | [optional] 
**MessageCount** | **int32** |  | 
**OperationId** | **string** |  | 
**Options** | Pointer to **string** |  | [optional] 
**PartialDurationMs** | Pointer to **NullableInt32** |  | [optional] 
**QueuedAt** | Pointer to **NullableTime** |  | [optional] 
**Server** | [**Server**](Server.md) |  | 
**ServerId** | **int32** |  | 
**ServerName** | **string** |  | 
**Services** | Pointer to **string** |  | [optional] 
**StackName** | **string** |  | 
**StartTime** | Pointer to **time.Time** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**Success** | Pointer to **NullableBool** |  | [optional] 
**Summary** | Pointer to **string** |  | [optional] 
**TriggerSource** | **string** |  | 
**UpdatedAt** | **time.Time** |  | 
**User** | [**User**](User.md) |  | 
**UserId** | **int32** |  | 
**UserName** | **string** |  | 

## Methods

### NewOperationLogInfo

`func NewOperationLogInfo(command string, createdAt time.Time, formattedDate string, id int32, isIncomplete bool, messageCount int32, operationId string, server Server, serverId int32, serverName string, stackName string, triggerSource string, updatedAt time.Time, user User, userId int32, userName string, ) *OperationLogInfo`

NewOperationLogInfo instantiates a new OperationLogInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperationLogInfoWithDefaults

`func NewOperationLogInfoWithDefaults() *OperationLogInfo`

NewOperationLogInfoWithDefaults instantiates a new OperationLogInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCommand

`func (o *OperationLogInfo) GetCommand() string`

GetCommand returns the Command field if non-nil, zero value otherwise.

### GetCommandOk

`func (o *OperationLogInfo) GetCommandOk() (*string, bool)`

GetCommandOk returns a tuple with the Command field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommand

`func (o *OperationLogInfo) SetCommand(v string)`

SetCommand sets Command field to given value.


### GetCreatedAt

`func (o *OperationLogInfo) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *OperationLogInfo) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *OperationLogInfo) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetDeletedAt

`func (o *OperationLogInfo) GetDeletedAt() DeletedAt`

GetDeletedAt returns the DeletedAt field if non-nil, zero value otherwise.

### GetDeletedAtOk

`func (o *OperationLogInfo) GetDeletedAtOk() (*DeletedAt, bool)`

GetDeletedAtOk returns a tuple with the DeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedAt

`func (o *OperationLogInfo) SetDeletedAt(v DeletedAt)`

SetDeletedAt sets DeletedAt field to given value.

### HasDeletedAt

`func (o *OperationLogInfo) HasDeletedAt() bool`

HasDeletedAt returns a boolean if a field has been set.

### GetDurationMs

`func (o *OperationLogInfo) GetDurationMs() int32`

GetDurationMs returns the DurationMs field if non-nil, zero value otherwise.

### GetDurationMsOk

`func (o *OperationLogInfo) GetDurationMsOk() (*int32, bool)`

GetDurationMsOk returns a tuple with the DurationMs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDurationMs

`func (o *OperationLogInfo) SetDurationMs(v int32)`

SetDurationMs sets DurationMs field to given value.

### HasDurationMs

`func (o *OperationLogInfo) HasDurationMs() bool`

HasDurationMs returns a boolean if a field has been set.

### SetDurationMsNil

`func (o *OperationLogInfo) SetDurationMsNil(b bool)`

 SetDurationMsNil sets the value for DurationMs to be an explicit nil

### UnsetDurationMs
`func (o *OperationLogInfo) UnsetDurationMs()`

UnsetDurationMs ensures that no value is present for DurationMs, not even an explicit nil
### GetEndTime

`func (o *OperationLogInfo) GetEndTime() time.Time`

GetEndTime returns the EndTime field if non-nil, zero value otherwise.

### GetEndTimeOk

`func (o *OperationLogInfo) GetEndTimeOk() (*time.Time, bool)`

GetEndTimeOk returns a tuple with the EndTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndTime

`func (o *OperationLogInfo) SetEndTime(v time.Time)`

SetEndTime sets EndTime field to given value.

### HasEndTime

`func (o *OperationLogInfo) HasEndTime() bool`

HasEndTime returns a boolean if a field has been set.

### SetEndTimeNil

`func (o *OperationLogInfo) SetEndTimeNil(b bool)`

 SetEndTimeNil sets the value for EndTime to be an explicit nil

### UnsetEndTime
`func (o *OperationLogInfo) UnsetEndTime()`

UnsetEndTime ensures that no value is present for EndTime, not even an explicit nil
### GetExitCode

`func (o *OperationLogInfo) GetExitCode() int32`

GetExitCode returns the ExitCode field if non-nil, zero value otherwise.

### GetExitCodeOk

`func (o *OperationLogInfo) GetExitCodeOk() (*int32, bool)`

GetExitCodeOk returns a tuple with the ExitCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExitCode

`func (o *OperationLogInfo) SetExitCode(v int32)`

SetExitCode sets ExitCode field to given value.

### HasExitCode

`func (o *OperationLogInfo) HasExitCode() bool`

HasExitCode returns a boolean if a field has been set.

### SetExitCodeNil

`func (o *OperationLogInfo) SetExitCodeNil(b bool)`

 SetExitCodeNil sets the value for ExitCode to be an explicit nil

### UnsetExitCode
`func (o *OperationLogInfo) UnsetExitCode()`

UnsetExitCode ensures that no value is present for ExitCode, not even an explicit nil
### GetFormattedDate

`func (o *OperationLogInfo) GetFormattedDate() string`

GetFormattedDate returns the FormattedDate field if non-nil, zero value otherwise.

### GetFormattedDateOk

`func (o *OperationLogInfo) GetFormattedDateOk() (*string, bool)`

GetFormattedDateOk returns a tuple with the FormattedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormattedDate

`func (o *OperationLogInfo) SetFormattedDate(v string)`

SetFormattedDate sets FormattedDate field to given value.


### GetId

`func (o *OperationLogInfo) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *OperationLogInfo) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *OperationLogInfo) SetId(v int32)`

SetId sets Id field to given value.


### GetIsIncomplete

`func (o *OperationLogInfo) GetIsIncomplete() bool`

GetIsIncomplete returns the IsIncomplete field if non-nil, zero value otherwise.

### GetIsIncompleteOk

`func (o *OperationLogInfo) GetIsIncompleteOk() (*bool, bool)`

GetIsIncompleteOk returns a tuple with the IsIncomplete field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsIncomplete

`func (o *OperationLogInfo) SetIsIncomplete(v bool)`

SetIsIncomplete sets IsIncomplete field to given value.


### GetLastMessageAt

`func (o *OperationLogInfo) GetLastMessageAt() time.Time`

GetLastMessageAt returns the LastMessageAt field if non-nil, zero value otherwise.

### GetLastMessageAtOk

`func (o *OperationLogInfo) GetLastMessageAtOk() (*time.Time, bool)`

GetLastMessageAtOk returns a tuple with the LastMessageAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastMessageAt

`func (o *OperationLogInfo) SetLastMessageAt(v time.Time)`

SetLastMessageAt sets LastMessageAt field to given value.

### HasLastMessageAt

`func (o *OperationLogInfo) HasLastMessageAt() bool`

HasLastMessageAt returns a boolean if a field has been set.

### SetLastMessageAtNil

`func (o *OperationLogInfo) SetLastMessageAtNil(b bool)`

 SetLastMessageAtNil sets the value for LastMessageAt to be an explicit nil

### UnsetLastMessageAt
`func (o *OperationLogInfo) UnsetLastMessageAt()`

UnsetLastMessageAt ensures that no value is present for LastMessageAt, not even an explicit nil
### GetMessageCount

`func (o *OperationLogInfo) GetMessageCount() int32`

GetMessageCount returns the MessageCount field if non-nil, zero value otherwise.

### GetMessageCountOk

`func (o *OperationLogInfo) GetMessageCountOk() (*int32, bool)`

GetMessageCountOk returns a tuple with the MessageCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageCount

`func (o *OperationLogInfo) SetMessageCount(v int32)`

SetMessageCount sets MessageCount field to given value.


### GetOperationId

`func (o *OperationLogInfo) GetOperationId() string`

GetOperationId returns the OperationId field if non-nil, zero value otherwise.

### GetOperationIdOk

`func (o *OperationLogInfo) GetOperationIdOk() (*string, bool)`

GetOperationIdOk returns a tuple with the OperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationId

`func (o *OperationLogInfo) SetOperationId(v string)`

SetOperationId sets OperationId field to given value.


### GetOptions

`func (o *OperationLogInfo) GetOptions() string`

GetOptions returns the Options field if non-nil, zero value otherwise.

### GetOptionsOk

`func (o *OperationLogInfo) GetOptionsOk() (*string, bool)`

GetOptionsOk returns a tuple with the Options field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOptions

`func (o *OperationLogInfo) SetOptions(v string)`

SetOptions sets Options field to given value.

### HasOptions

`func (o *OperationLogInfo) HasOptions() bool`

HasOptions returns a boolean if a field has been set.

### GetPartialDurationMs

`func (o *OperationLogInfo) GetPartialDurationMs() int32`

GetPartialDurationMs returns the PartialDurationMs field if non-nil, zero value otherwise.

### GetPartialDurationMsOk

`func (o *OperationLogInfo) GetPartialDurationMsOk() (*int32, bool)`

GetPartialDurationMsOk returns a tuple with the PartialDurationMs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartialDurationMs

`func (o *OperationLogInfo) SetPartialDurationMs(v int32)`

SetPartialDurationMs sets PartialDurationMs field to given value.

### HasPartialDurationMs

`func (o *OperationLogInfo) HasPartialDurationMs() bool`

HasPartialDurationMs returns a boolean if a field has been set.

### SetPartialDurationMsNil

`func (o *OperationLogInfo) SetPartialDurationMsNil(b bool)`

 SetPartialDurationMsNil sets the value for PartialDurationMs to be an explicit nil

### UnsetPartialDurationMs
`func (o *OperationLogInfo) UnsetPartialDurationMs()`

UnsetPartialDurationMs ensures that no value is present for PartialDurationMs, not even an explicit nil
### GetQueuedAt

`func (o *OperationLogInfo) GetQueuedAt() time.Time`

GetQueuedAt returns the QueuedAt field if non-nil, zero value otherwise.

### GetQueuedAtOk

`func (o *OperationLogInfo) GetQueuedAtOk() (*time.Time, bool)`

GetQueuedAtOk returns a tuple with the QueuedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQueuedAt

`func (o *OperationLogInfo) SetQueuedAt(v time.Time)`

SetQueuedAt sets QueuedAt field to given value.

### HasQueuedAt

`func (o *OperationLogInfo) HasQueuedAt() bool`

HasQueuedAt returns a boolean if a field has been set.

### SetQueuedAtNil

`func (o *OperationLogInfo) SetQueuedAtNil(b bool)`

 SetQueuedAtNil sets the value for QueuedAt to be an explicit nil

### UnsetQueuedAt
`func (o *OperationLogInfo) UnsetQueuedAt()`

UnsetQueuedAt ensures that no value is present for QueuedAt, not even an explicit nil
### GetServer

`func (o *OperationLogInfo) GetServer() Server`

GetServer returns the Server field if non-nil, zero value otherwise.

### GetServerOk

`func (o *OperationLogInfo) GetServerOk() (*Server, bool)`

GetServerOk returns a tuple with the Server field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServer

`func (o *OperationLogInfo) SetServer(v Server)`

SetServer sets Server field to given value.


### GetServerId

`func (o *OperationLogInfo) GetServerId() int32`

GetServerId returns the ServerId field if non-nil, zero value otherwise.

### GetServerIdOk

`func (o *OperationLogInfo) GetServerIdOk() (*int32, bool)`

GetServerIdOk returns a tuple with the ServerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerId

`func (o *OperationLogInfo) SetServerId(v int32)`

SetServerId sets ServerId field to given value.


### GetServerName

`func (o *OperationLogInfo) GetServerName() string`

GetServerName returns the ServerName field if non-nil, zero value otherwise.

### GetServerNameOk

`func (o *OperationLogInfo) GetServerNameOk() (*string, bool)`

GetServerNameOk returns a tuple with the ServerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerName

`func (o *OperationLogInfo) SetServerName(v string)`

SetServerName sets ServerName field to given value.


### GetServices

`func (o *OperationLogInfo) GetServices() string`

GetServices returns the Services field if non-nil, zero value otherwise.

### GetServicesOk

`func (o *OperationLogInfo) GetServicesOk() (*string, bool)`

GetServicesOk returns a tuple with the Services field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServices

`func (o *OperationLogInfo) SetServices(v string)`

SetServices sets Services field to given value.

### HasServices

`func (o *OperationLogInfo) HasServices() bool`

HasServices returns a boolean if a field has been set.

### GetStackName

`func (o *OperationLogInfo) GetStackName() string`

GetStackName returns the StackName field if non-nil, zero value otherwise.

### GetStackNameOk

`func (o *OperationLogInfo) GetStackNameOk() (*string, bool)`

GetStackNameOk returns a tuple with the StackName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStackName

`func (o *OperationLogInfo) SetStackName(v string)`

SetStackName sets StackName field to given value.


### GetStartTime

`func (o *OperationLogInfo) GetStartTime() time.Time`

GetStartTime returns the StartTime field if non-nil, zero value otherwise.

### GetStartTimeOk

`func (o *OperationLogInfo) GetStartTimeOk() (*time.Time, bool)`

GetStartTimeOk returns a tuple with the StartTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartTime

`func (o *OperationLogInfo) SetStartTime(v time.Time)`

SetStartTime sets StartTime field to given value.

### HasStartTime

`func (o *OperationLogInfo) HasStartTime() bool`

HasStartTime returns a boolean if a field has been set.

### GetStatus

`func (o *OperationLogInfo) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *OperationLogInfo) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *OperationLogInfo) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *OperationLogInfo) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetSuccess

`func (o *OperationLogInfo) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *OperationLogInfo) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *OperationLogInfo) SetSuccess(v bool)`

SetSuccess sets Success field to given value.

### HasSuccess

`func (o *OperationLogInfo) HasSuccess() bool`

HasSuccess returns a boolean if a field has been set.

### SetSuccessNil

`func (o *OperationLogInfo) SetSuccessNil(b bool)`

 SetSuccessNil sets the value for Success to be an explicit nil

### UnsetSuccess
`func (o *OperationLogInfo) UnsetSuccess()`

UnsetSuccess ensures that no value is present for Success, not even an explicit nil
### GetSummary

`func (o *OperationLogInfo) GetSummary() string`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *OperationLogInfo) GetSummaryOk() (*string, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *OperationLogInfo) SetSummary(v string)`

SetSummary sets Summary field to given value.

### HasSummary

`func (o *OperationLogInfo) HasSummary() bool`

HasSummary returns a boolean if a field has been set.

### GetTriggerSource

`func (o *OperationLogInfo) GetTriggerSource() string`

GetTriggerSource returns the TriggerSource field if non-nil, zero value otherwise.

### GetTriggerSourceOk

`func (o *OperationLogInfo) GetTriggerSourceOk() (*string, bool)`

GetTriggerSourceOk returns a tuple with the TriggerSource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTriggerSource

`func (o *OperationLogInfo) SetTriggerSource(v string)`

SetTriggerSource sets TriggerSource field to given value.


### GetUpdatedAt

`func (o *OperationLogInfo) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *OperationLogInfo) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *OperationLogInfo) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetUser

`func (o *OperationLogInfo) GetUser() User`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *OperationLogInfo) GetUserOk() (*User, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *OperationLogInfo) SetUser(v User)`

SetUser sets User field to given value.


### GetUserId

`func (o *OperationLogInfo) GetUserId() int32`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *OperationLogInfo) GetUserIdOk() (*int32, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *OperationLogInfo) SetUserId(v int32)`

SetUserId sets UserId field to given value.


### GetUserName

`func (o *OperationLogInfo) GetUserName() string`

GetUserName returns the UserName field if non-nil, zero value otherwise.

### GetUserNameOk

`func (o *OperationLogInfo) GetUserNameOk() (*string, bool)`

GetUserNameOk returns a tuple with the UserName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserName

`func (o *OperationLogInfo) SetUserName(v string)`

SetUserName sets UserName field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


