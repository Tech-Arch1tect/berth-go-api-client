# CreateAPIKeyResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApiKey** | [**APIKeyInfo**](APIKeyInfo.md) |  | 
**Message** | Pointer to **string** |  | [optional] 
**PlainKey** | **string** |  | 

## Methods

### NewCreateAPIKeyResponseData

`func NewCreateAPIKeyResponseData(apiKey APIKeyInfo, plainKey string, ) *CreateAPIKeyResponseData`

NewCreateAPIKeyResponseData instantiates a new CreateAPIKeyResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateAPIKeyResponseDataWithDefaults

`func NewCreateAPIKeyResponseDataWithDefaults() *CreateAPIKeyResponseData`

NewCreateAPIKeyResponseDataWithDefaults instantiates a new CreateAPIKeyResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApiKey

`func (o *CreateAPIKeyResponseData) GetApiKey() APIKeyInfo`

GetApiKey returns the ApiKey field if non-nil, zero value otherwise.

### GetApiKeyOk

`func (o *CreateAPIKeyResponseData) GetApiKeyOk() (*APIKeyInfo, bool)`

GetApiKeyOk returns a tuple with the ApiKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApiKey

`func (o *CreateAPIKeyResponseData) SetApiKey(v APIKeyInfo)`

SetApiKey sets ApiKey field to given value.


### GetMessage

`func (o *CreateAPIKeyResponseData) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *CreateAPIKeyResponseData) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *CreateAPIKeyResponseData) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *CreateAPIKeyResponseData) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetPlainKey

`func (o *CreateAPIKeyResponseData) GetPlainKey() string`

GetPlainKey returns the PlainKey field if non-nil, zero value otherwise.

### GetPlainKeyOk

`func (o *CreateAPIKeyResponseData) GetPlainKeyOk() (*string, bool)`

GetPlainKeyOk returns a tuple with the PlainKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlainKey

`func (o *CreateAPIKeyResponseData) SetPlainKey(v string)`

SetPlainKey sets PlainKey field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


