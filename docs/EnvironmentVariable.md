# EnvironmentVariable

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**IsFromContainer** | **bool** |  | 
**IsSensitive** | **bool** |  | 
**Key** | **string** |  | 
**Source** | **string** |  | 
**Value** | **string** |  | 

## Methods

### NewEnvironmentVariable

`func NewEnvironmentVariable(isFromContainer bool, isSensitive bool, key string, source string, value string, ) *EnvironmentVariable`

NewEnvironmentVariable instantiates a new EnvironmentVariable object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEnvironmentVariableWithDefaults

`func NewEnvironmentVariableWithDefaults() *EnvironmentVariable`

NewEnvironmentVariableWithDefaults instantiates a new EnvironmentVariable object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIsFromContainer

`func (o *EnvironmentVariable) GetIsFromContainer() bool`

GetIsFromContainer returns the IsFromContainer field if non-nil, zero value otherwise.

### GetIsFromContainerOk

`func (o *EnvironmentVariable) GetIsFromContainerOk() (*bool, bool)`

GetIsFromContainerOk returns a tuple with the IsFromContainer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsFromContainer

`func (o *EnvironmentVariable) SetIsFromContainer(v bool)`

SetIsFromContainer sets IsFromContainer field to given value.


### GetIsSensitive

`func (o *EnvironmentVariable) GetIsSensitive() bool`

GetIsSensitive returns the IsSensitive field if non-nil, zero value otherwise.

### GetIsSensitiveOk

`func (o *EnvironmentVariable) GetIsSensitiveOk() (*bool, bool)`

GetIsSensitiveOk returns a tuple with the IsSensitive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsSensitive

`func (o *EnvironmentVariable) SetIsSensitive(v bool)`

SetIsSensitive sets IsSensitive field to given value.


### GetKey

`func (o *EnvironmentVariable) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *EnvironmentVariable) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *EnvironmentVariable) SetKey(v string)`

SetKey sets Key field to given value.


### GetSource

`func (o *EnvironmentVariable) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *EnvironmentVariable) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *EnvironmentVariable) SetSource(v string)`

SetSource sets Source field to given value.


### GetValue

`func (o *EnvironmentVariable) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *EnvironmentVariable) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *EnvironmentVariable) SetValue(v string)`

SetValue sets Value field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


