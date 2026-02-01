# AdminCreateServerResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**AdminCreateServerResponseData**](AdminCreateServerResponseData.md) |  | 
**Success** | **bool** |  | 

## Methods

### NewAdminCreateServerResponse

`func NewAdminCreateServerResponse(data AdminCreateServerResponseData, success bool, ) *AdminCreateServerResponse`

NewAdminCreateServerResponse instantiates a new AdminCreateServerResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAdminCreateServerResponseWithDefaults

`func NewAdminCreateServerResponseWithDefaults() *AdminCreateServerResponse`

NewAdminCreateServerResponseWithDefaults instantiates a new AdminCreateServerResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *AdminCreateServerResponse) GetData() AdminCreateServerResponseData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *AdminCreateServerResponse) GetDataOk() (*AdminCreateServerResponseData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *AdminCreateServerResponse) SetData(v AdminCreateServerResponseData)`

SetData sets Data field to given value.


### GetSuccess

`func (o *AdminCreateServerResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *AdminCreateServerResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *AdminCreateServerResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


