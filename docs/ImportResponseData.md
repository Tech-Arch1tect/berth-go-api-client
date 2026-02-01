# ImportResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EncryptionSecret** | **string** |  | 
**Summary** | [**ImportSummary**](ImportSummary.md) |  | 

## Methods

### NewImportResponseData

`func NewImportResponseData(encryptionSecret string, summary ImportSummary, ) *ImportResponseData`

NewImportResponseData instantiates a new ImportResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImportResponseDataWithDefaults

`func NewImportResponseDataWithDefaults() *ImportResponseData`

NewImportResponseDataWithDefaults instantiates a new ImportResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEncryptionSecret

`func (o *ImportResponseData) GetEncryptionSecret() string`

GetEncryptionSecret returns the EncryptionSecret field if non-nil, zero value otherwise.

### GetEncryptionSecretOk

`func (o *ImportResponseData) GetEncryptionSecretOk() (*string, bool)`

GetEncryptionSecretOk returns a tuple with the EncryptionSecret field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEncryptionSecret

`func (o *ImportResponseData) SetEncryptionSecret(v string)`

SetEncryptionSecret sets EncryptionSecret field to given value.


### GetSummary

`func (o *ImportResponseData) GetSummary() ImportSummary`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *ImportResponseData) GetSummaryOk() (*ImportSummary, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *ImportResponseData) SetSummary(v ImportSummary)`

SetSummary sets Summary field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


