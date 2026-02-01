# RestartPolicy

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MaximumRetryCount** | Pointer to **int32** |  | [optional] 
**Name** | **string** |  | 

## Methods

### NewRestartPolicy

`func NewRestartPolicy(name string, ) *RestartPolicy`

NewRestartPolicy instantiates a new RestartPolicy object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRestartPolicyWithDefaults

`func NewRestartPolicyWithDefaults() *RestartPolicy`

NewRestartPolicyWithDefaults instantiates a new RestartPolicy object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMaximumRetryCount

`func (o *RestartPolicy) GetMaximumRetryCount() int32`

GetMaximumRetryCount returns the MaximumRetryCount field if non-nil, zero value otherwise.

### GetMaximumRetryCountOk

`func (o *RestartPolicy) GetMaximumRetryCountOk() (*int32, bool)`

GetMaximumRetryCountOk returns a tuple with the MaximumRetryCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaximumRetryCount

`func (o *RestartPolicy) SetMaximumRetryCount(v int32)`

SetMaximumRetryCount sets MaximumRetryCount field to given value.

### HasMaximumRetryCount

`func (o *RestartPolicy) HasMaximumRetryCount() bool`

HasMaximumRetryCount returns a boolean if a field has been set.

### GetName

`func (o *RestartPolicy) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *RestartPolicy) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *RestartPolicy) SetName(v string)`

SetName sets Name field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


