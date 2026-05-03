# CreateAPIKeyData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApiKey** | [**APIKeyInfo**](APIKeyInfo.md) |  | 
**Message** | Pointer to **string** |  | [optional] 
**PlainKey** | **string** |  | 

## Methods

### NewCreateAPIKeyData

`func NewCreateAPIKeyData(apiKey APIKeyInfo, plainKey string, ) *CreateAPIKeyData`

NewCreateAPIKeyData instantiates a new CreateAPIKeyData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateAPIKeyDataWithDefaults

`func NewCreateAPIKeyDataWithDefaults() *CreateAPIKeyData`

NewCreateAPIKeyDataWithDefaults instantiates a new CreateAPIKeyData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApiKey

`func (o *CreateAPIKeyData) GetApiKey() APIKeyInfo`

GetApiKey returns the ApiKey field if non-nil, zero value otherwise.

### GetApiKeyOk

`func (o *CreateAPIKeyData) GetApiKeyOk() (*APIKeyInfo, bool)`

GetApiKeyOk returns a tuple with the ApiKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApiKey

`func (o *CreateAPIKeyData) SetApiKey(v APIKeyInfo)`

SetApiKey sets ApiKey field to given value.


### GetMessage

`func (o *CreateAPIKeyData) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *CreateAPIKeyData) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *CreateAPIKeyData) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *CreateAPIKeyData) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetPlainKey

`func (o *CreateAPIKeyData) GetPlainKey() string`

GetPlainKey returns the PlainKey field if non-nil, zero value otherwise.

### GetPlainKeyOk

`func (o *CreateAPIKeyData) GetPlainKeyOk() (*string, bool)`

GetPlainKeyOk returns a tuple with the PlainKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlainKey

`func (o *CreateAPIKeyData) SetPlainKey(v string)`

SetPlainKey sets PlainKey field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


