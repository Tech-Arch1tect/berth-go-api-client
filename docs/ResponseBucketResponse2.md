# ResponseBucketResponse2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**BucketResponse**](BucketResponse.md) |  | 
**Error** | Pointer to [**NullableError**](Error.md) |  | [optional] 
**Meta** | Pointer to [**NullableMeta**](Meta.md) |  | [optional] 
**Success** | **bool** |  | 

## Methods

### NewResponseBucketResponse2

`func NewResponseBucketResponse2(data BucketResponse, success bool, ) *ResponseBucketResponse2`

NewResponseBucketResponse2 instantiates a new ResponseBucketResponse2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResponseBucketResponse2WithDefaults

`func NewResponseBucketResponse2WithDefaults() *ResponseBucketResponse2`

NewResponseBucketResponse2WithDefaults instantiates a new ResponseBucketResponse2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *ResponseBucketResponse2) GetData() BucketResponse`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ResponseBucketResponse2) GetDataOk() (*BucketResponse, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ResponseBucketResponse2) SetData(v BucketResponse)`

SetData sets Data field to given value.


### GetError

`func (o *ResponseBucketResponse2) GetError() Error`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ResponseBucketResponse2) GetErrorOk() (*Error, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ResponseBucketResponse2) SetError(v Error)`

SetError sets Error field to given value.

### HasError

`func (o *ResponseBucketResponse2) HasError() bool`

HasError returns a boolean if a field has been set.

### SetErrorNil

`func (o *ResponseBucketResponse2) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *ResponseBucketResponse2) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetMeta

`func (o *ResponseBucketResponse2) GetMeta() Meta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *ResponseBucketResponse2) GetMetaOk() (*Meta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *ResponseBucketResponse2) SetMeta(v Meta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *ResponseBucketResponse2) HasMeta() bool`

HasMeta returns a boolean if a field has been set.

### SetMetaNil

`func (o *ResponseBucketResponse2) SetMetaNil(b bool)`

 SetMetaNil sets the value for Meta to be an explicit nil

### UnsetMeta
`func (o *ResponseBucketResponse2) UnsetMeta()`

UnsetMeta ensures that no value is present for Meta, not even an explicit nil
### GetSuccess

`func (o *ResponseBucketResponse2) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *ResponseBucketResponse2) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *ResponseBucketResponse2) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


