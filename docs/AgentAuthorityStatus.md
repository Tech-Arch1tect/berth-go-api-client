# AgentAuthorityStatus

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AgentsNeedingReissue** | **int32** |  | 
**AuthorityExpiresAt** | Pointer to **string** |  | [optional] 
**AuthorityFingerprint** | Pointer to **string** |  | [optional] 
**ClientExpiresAt** | Pointer to **string** |  | [optional] 
**ClientFingerprint** | Pointer to **string** |  | [optional] 
**Exists** | **bool** |  | 

## Methods

### NewAgentAuthorityStatus

`func NewAgentAuthorityStatus(agentsNeedingReissue int32, exists bool, ) *AgentAuthorityStatus`

NewAgentAuthorityStatus instantiates a new AgentAuthorityStatus object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAgentAuthorityStatusWithDefaults

`func NewAgentAuthorityStatusWithDefaults() *AgentAuthorityStatus`

NewAgentAuthorityStatusWithDefaults instantiates a new AgentAuthorityStatus object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAgentsNeedingReissue

`func (o *AgentAuthorityStatus) GetAgentsNeedingReissue() int32`

GetAgentsNeedingReissue returns the AgentsNeedingReissue field if non-nil, zero value otherwise.

### GetAgentsNeedingReissueOk

`func (o *AgentAuthorityStatus) GetAgentsNeedingReissueOk() (*int32, bool)`

GetAgentsNeedingReissueOk returns a tuple with the AgentsNeedingReissue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgentsNeedingReissue

`func (o *AgentAuthorityStatus) SetAgentsNeedingReissue(v int32)`

SetAgentsNeedingReissue sets AgentsNeedingReissue field to given value.


### GetAuthorityExpiresAt

`func (o *AgentAuthorityStatus) GetAuthorityExpiresAt() string`

GetAuthorityExpiresAt returns the AuthorityExpiresAt field if non-nil, zero value otherwise.

### GetAuthorityExpiresAtOk

`func (o *AgentAuthorityStatus) GetAuthorityExpiresAtOk() (*string, bool)`

GetAuthorityExpiresAtOk returns a tuple with the AuthorityExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthorityExpiresAt

`func (o *AgentAuthorityStatus) SetAuthorityExpiresAt(v string)`

SetAuthorityExpiresAt sets AuthorityExpiresAt field to given value.

### HasAuthorityExpiresAt

`func (o *AgentAuthorityStatus) HasAuthorityExpiresAt() bool`

HasAuthorityExpiresAt returns a boolean if a field has been set.

### GetAuthorityFingerprint

`func (o *AgentAuthorityStatus) GetAuthorityFingerprint() string`

GetAuthorityFingerprint returns the AuthorityFingerprint field if non-nil, zero value otherwise.

### GetAuthorityFingerprintOk

`func (o *AgentAuthorityStatus) GetAuthorityFingerprintOk() (*string, bool)`

GetAuthorityFingerprintOk returns a tuple with the AuthorityFingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthorityFingerprint

`func (o *AgentAuthorityStatus) SetAuthorityFingerprint(v string)`

SetAuthorityFingerprint sets AuthorityFingerprint field to given value.

### HasAuthorityFingerprint

`func (o *AgentAuthorityStatus) HasAuthorityFingerprint() bool`

HasAuthorityFingerprint returns a boolean if a field has been set.

### GetClientExpiresAt

`func (o *AgentAuthorityStatus) GetClientExpiresAt() string`

GetClientExpiresAt returns the ClientExpiresAt field if non-nil, zero value otherwise.

### GetClientExpiresAtOk

`func (o *AgentAuthorityStatus) GetClientExpiresAtOk() (*string, bool)`

GetClientExpiresAtOk returns a tuple with the ClientExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientExpiresAt

`func (o *AgentAuthorityStatus) SetClientExpiresAt(v string)`

SetClientExpiresAt sets ClientExpiresAt field to given value.

### HasClientExpiresAt

`func (o *AgentAuthorityStatus) HasClientExpiresAt() bool`

HasClientExpiresAt returns a boolean if a field has been set.

### GetClientFingerprint

`func (o *AgentAuthorityStatus) GetClientFingerprint() string`

GetClientFingerprint returns the ClientFingerprint field if non-nil, zero value otherwise.

### GetClientFingerprintOk

`func (o *AgentAuthorityStatus) GetClientFingerprintOk() (*string, bool)`

GetClientFingerprintOk returns a tuple with the ClientFingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientFingerprint

`func (o *AgentAuthorityStatus) SetClientFingerprint(v string)`

SetClientFingerprint sets ClientFingerprint field to given value.

### HasClientFingerprint

`func (o *AgentAuthorityStatus) HasClientFingerprint() bool`

HasClientFingerprint returns a boolean if a field has been set.

### GetExists

`func (o *AgentAuthorityStatus) GetExists() bool`

GetExists returns the Exists field if non-nil, zero value otherwise.

### GetExistsOk

`func (o *AgentAuthorityStatus) GetExistsOk() (*bool, bool)`

GetExistsOk returns a tuple with the Exists field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExists

`func (o *AgentAuthorityStatus) SetExists(v bool)`

SetExists sets Exists field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


