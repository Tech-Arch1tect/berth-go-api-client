# AdminDeleteServerResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**AdminDeleteServerResponseData**](AdminDeleteServerResponseData.md) |  | 
**Success** | **bool** |  | 

## Methods

### NewAdminDeleteServerResponse

`func NewAdminDeleteServerResponse(data AdminDeleteServerResponseData, success bool, ) *AdminDeleteServerResponse`

NewAdminDeleteServerResponse instantiates a new AdminDeleteServerResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAdminDeleteServerResponseWithDefaults

`func NewAdminDeleteServerResponseWithDefaults() *AdminDeleteServerResponse`

NewAdminDeleteServerResponseWithDefaults instantiates a new AdminDeleteServerResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *AdminDeleteServerResponse) GetData() AdminDeleteServerResponseData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *AdminDeleteServerResponse) GetDataOk() (*AdminDeleteServerResponseData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *AdminDeleteServerResponse) SetData(v AdminDeleteServerResponseData)`

SetData sets Data field to given value.


### GetSuccess

`func (o *AdminDeleteServerResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *AdminDeleteServerResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *AdminDeleteServerResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


