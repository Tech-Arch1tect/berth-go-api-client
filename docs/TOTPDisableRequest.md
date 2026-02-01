# TOTPDisableRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | **string** |  | 
**Password** | **string** |  | 

## Methods

### NewTOTPDisableRequest

`func NewTOTPDisableRequest(code string, password string, ) *TOTPDisableRequest`

NewTOTPDisableRequest instantiates a new TOTPDisableRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTOTPDisableRequestWithDefaults

`func NewTOTPDisableRequestWithDefaults() *TOTPDisableRequest`

NewTOTPDisableRequestWithDefaults instantiates a new TOTPDisableRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *TOTPDisableRequest) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *TOTPDisableRequest) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *TOTPDisableRequest) SetCode(v string)`

SetCode sets Code field to given value.


### GetPassword

`func (o *TOTPDisableRequest) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *TOTPDisableRequest) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *TOTPDisableRequest) SetPassword(v string)`

SetPassword sets Password field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


