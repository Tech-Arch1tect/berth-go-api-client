# SecurityAuditLogInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ActorIp** | **string** |  | 
**ActorUserAgent** | **string** |  | 
**ActorUserId** | **NullableInt32** |  | 
**ActorUsername** | **string** |  | 
**CreatedAt** | **time.Time** |  | 
**EventCategory** | **string** |  | 
**EventType** | **string** |  | 
**FailureReason** | **string** |  | 
**Id** | **int32** |  | 
**Metadata** | **string** |  | 
**ServerId** | **NullableInt32** |  | 
**SessionId** | **string** |  | 
**Severity** | **string** |  | 
**StackName** | **string** |  | 
**Success** | **bool** |  | 
**TargetId** | **NullableInt32** |  | 
**TargetName** | **string** |  | 
**TargetType** | **string** |  | 
**TargetUserId** | **NullableInt32** |  | 
**UpdatedAt** | **time.Time** |  | 

## Methods

### NewSecurityAuditLogInfo

`func NewSecurityAuditLogInfo(actorIp string, actorUserAgent string, actorUserId NullableInt32, actorUsername string, createdAt time.Time, eventCategory string, eventType string, failureReason string, id int32, metadata string, serverId NullableInt32, sessionId string, severity string, stackName string, success bool, targetId NullableInt32, targetName string, targetType string, targetUserId NullableInt32, updatedAt time.Time, ) *SecurityAuditLogInfo`

NewSecurityAuditLogInfo instantiates a new SecurityAuditLogInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSecurityAuditLogInfoWithDefaults

`func NewSecurityAuditLogInfoWithDefaults() *SecurityAuditLogInfo`

NewSecurityAuditLogInfoWithDefaults instantiates a new SecurityAuditLogInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActorIp

`func (o *SecurityAuditLogInfo) GetActorIp() string`

GetActorIp returns the ActorIp field if non-nil, zero value otherwise.

### GetActorIpOk

`func (o *SecurityAuditLogInfo) GetActorIpOk() (*string, bool)`

GetActorIpOk returns a tuple with the ActorIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActorIp

`func (o *SecurityAuditLogInfo) SetActorIp(v string)`

SetActorIp sets ActorIp field to given value.


### GetActorUserAgent

`func (o *SecurityAuditLogInfo) GetActorUserAgent() string`

GetActorUserAgent returns the ActorUserAgent field if non-nil, zero value otherwise.

### GetActorUserAgentOk

`func (o *SecurityAuditLogInfo) GetActorUserAgentOk() (*string, bool)`

GetActorUserAgentOk returns a tuple with the ActorUserAgent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActorUserAgent

`func (o *SecurityAuditLogInfo) SetActorUserAgent(v string)`

SetActorUserAgent sets ActorUserAgent field to given value.


### GetActorUserId

`func (o *SecurityAuditLogInfo) GetActorUserId() int32`

GetActorUserId returns the ActorUserId field if non-nil, zero value otherwise.

### GetActorUserIdOk

`func (o *SecurityAuditLogInfo) GetActorUserIdOk() (*int32, bool)`

GetActorUserIdOk returns a tuple with the ActorUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActorUserId

`func (o *SecurityAuditLogInfo) SetActorUserId(v int32)`

SetActorUserId sets ActorUserId field to given value.


### SetActorUserIdNil

`func (o *SecurityAuditLogInfo) SetActorUserIdNil(b bool)`

 SetActorUserIdNil sets the value for ActorUserId to be an explicit nil

### UnsetActorUserId
`func (o *SecurityAuditLogInfo) UnsetActorUserId()`

UnsetActorUserId ensures that no value is present for ActorUserId, not even an explicit nil
### GetActorUsername

`func (o *SecurityAuditLogInfo) GetActorUsername() string`

GetActorUsername returns the ActorUsername field if non-nil, zero value otherwise.

### GetActorUsernameOk

`func (o *SecurityAuditLogInfo) GetActorUsernameOk() (*string, bool)`

GetActorUsernameOk returns a tuple with the ActorUsername field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActorUsername

`func (o *SecurityAuditLogInfo) SetActorUsername(v string)`

SetActorUsername sets ActorUsername field to given value.


### GetCreatedAt

`func (o *SecurityAuditLogInfo) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *SecurityAuditLogInfo) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *SecurityAuditLogInfo) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetEventCategory

`func (o *SecurityAuditLogInfo) GetEventCategory() string`

GetEventCategory returns the EventCategory field if non-nil, zero value otherwise.

### GetEventCategoryOk

`func (o *SecurityAuditLogInfo) GetEventCategoryOk() (*string, bool)`

GetEventCategoryOk returns a tuple with the EventCategory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventCategory

`func (o *SecurityAuditLogInfo) SetEventCategory(v string)`

SetEventCategory sets EventCategory field to given value.


### GetEventType

`func (o *SecurityAuditLogInfo) GetEventType() string`

GetEventType returns the EventType field if non-nil, zero value otherwise.

### GetEventTypeOk

`func (o *SecurityAuditLogInfo) GetEventTypeOk() (*string, bool)`

GetEventTypeOk returns a tuple with the EventType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventType

`func (o *SecurityAuditLogInfo) SetEventType(v string)`

SetEventType sets EventType field to given value.


### GetFailureReason

`func (o *SecurityAuditLogInfo) GetFailureReason() string`

GetFailureReason returns the FailureReason field if non-nil, zero value otherwise.

### GetFailureReasonOk

`func (o *SecurityAuditLogInfo) GetFailureReasonOk() (*string, bool)`

GetFailureReasonOk returns a tuple with the FailureReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureReason

`func (o *SecurityAuditLogInfo) SetFailureReason(v string)`

SetFailureReason sets FailureReason field to given value.


### GetId

`func (o *SecurityAuditLogInfo) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SecurityAuditLogInfo) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SecurityAuditLogInfo) SetId(v int32)`

SetId sets Id field to given value.


### GetMetadata

`func (o *SecurityAuditLogInfo) GetMetadata() string`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *SecurityAuditLogInfo) GetMetadataOk() (*string, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *SecurityAuditLogInfo) SetMetadata(v string)`

SetMetadata sets Metadata field to given value.


### GetServerId

`func (o *SecurityAuditLogInfo) GetServerId() int32`

GetServerId returns the ServerId field if non-nil, zero value otherwise.

### GetServerIdOk

`func (o *SecurityAuditLogInfo) GetServerIdOk() (*int32, bool)`

GetServerIdOk returns a tuple with the ServerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerId

`func (o *SecurityAuditLogInfo) SetServerId(v int32)`

SetServerId sets ServerId field to given value.


### SetServerIdNil

`func (o *SecurityAuditLogInfo) SetServerIdNil(b bool)`

 SetServerIdNil sets the value for ServerId to be an explicit nil

### UnsetServerId
`func (o *SecurityAuditLogInfo) UnsetServerId()`

UnsetServerId ensures that no value is present for ServerId, not even an explicit nil
### GetSessionId

`func (o *SecurityAuditLogInfo) GetSessionId() string`

GetSessionId returns the SessionId field if non-nil, zero value otherwise.

### GetSessionIdOk

`func (o *SecurityAuditLogInfo) GetSessionIdOk() (*string, bool)`

GetSessionIdOk returns a tuple with the SessionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSessionId

`func (o *SecurityAuditLogInfo) SetSessionId(v string)`

SetSessionId sets SessionId field to given value.


### GetSeverity

`func (o *SecurityAuditLogInfo) GetSeverity() string`

GetSeverity returns the Severity field if non-nil, zero value otherwise.

### GetSeverityOk

`func (o *SecurityAuditLogInfo) GetSeverityOk() (*string, bool)`

GetSeverityOk returns a tuple with the Severity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeverity

`func (o *SecurityAuditLogInfo) SetSeverity(v string)`

SetSeverity sets Severity field to given value.


### GetStackName

`func (o *SecurityAuditLogInfo) GetStackName() string`

GetStackName returns the StackName field if non-nil, zero value otherwise.

### GetStackNameOk

`func (o *SecurityAuditLogInfo) GetStackNameOk() (*string, bool)`

GetStackNameOk returns a tuple with the StackName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStackName

`func (o *SecurityAuditLogInfo) SetStackName(v string)`

SetStackName sets StackName field to given value.


### GetSuccess

`func (o *SecurityAuditLogInfo) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *SecurityAuditLogInfo) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *SecurityAuditLogInfo) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetTargetId

`func (o *SecurityAuditLogInfo) GetTargetId() int32`

GetTargetId returns the TargetId field if non-nil, zero value otherwise.

### GetTargetIdOk

`func (o *SecurityAuditLogInfo) GetTargetIdOk() (*int32, bool)`

GetTargetIdOk returns a tuple with the TargetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetId

`func (o *SecurityAuditLogInfo) SetTargetId(v int32)`

SetTargetId sets TargetId field to given value.


### SetTargetIdNil

`func (o *SecurityAuditLogInfo) SetTargetIdNil(b bool)`

 SetTargetIdNil sets the value for TargetId to be an explicit nil

### UnsetTargetId
`func (o *SecurityAuditLogInfo) UnsetTargetId()`

UnsetTargetId ensures that no value is present for TargetId, not even an explicit nil
### GetTargetName

`func (o *SecurityAuditLogInfo) GetTargetName() string`

GetTargetName returns the TargetName field if non-nil, zero value otherwise.

### GetTargetNameOk

`func (o *SecurityAuditLogInfo) GetTargetNameOk() (*string, bool)`

GetTargetNameOk returns a tuple with the TargetName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetName

`func (o *SecurityAuditLogInfo) SetTargetName(v string)`

SetTargetName sets TargetName field to given value.


### GetTargetType

`func (o *SecurityAuditLogInfo) GetTargetType() string`

GetTargetType returns the TargetType field if non-nil, zero value otherwise.

### GetTargetTypeOk

`func (o *SecurityAuditLogInfo) GetTargetTypeOk() (*string, bool)`

GetTargetTypeOk returns a tuple with the TargetType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetType

`func (o *SecurityAuditLogInfo) SetTargetType(v string)`

SetTargetType sets TargetType field to given value.


### GetTargetUserId

`func (o *SecurityAuditLogInfo) GetTargetUserId() int32`

GetTargetUserId returns the TargetUserId field if non-nil, zero value otherwise.

### GetTargetUserIdOk

`func (o *SecurityAuditLogInfo) GetTargetUserIdOk() (*int32, bool)`

GetTargetUserIdOk returns a tuple with the TargetUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetUserId

`func (o *SecurityAuditLogInfo) SetTargetUserId(v int32)`

SetTargetUserId sets TargetUserId field to given value.


### SetTargetUserIdNil

`func (o *SecurityAuditLogInfo) SetTargetUserIdNil(b bool)`

 SetTargetUserIdNil sets the value for TargetUserId to be an explicit nil

### UnsetTargetUserId
`func (o *SecurityAuditLogInfo) UnsetTargetUserId()`

UnsetTargetUserId ensures that no value is present for TargetUserId, not even an explicit nil
### GetUpdatedAt

`func (o *SecurityAuditLogInfo) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *SecurityAuditLogInfo) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *SecurityAuditLogInfo) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


