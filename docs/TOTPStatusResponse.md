# TOTPStatusResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**TOTPStatusData**](TOTPStatusData.md) |  | 
**Success** | **bool** |  | 

## Methods

### NewTOTPStatusResponse

`func NewTOTPStatusResponse(data TOTPStatusData, success bool, ) *TOTPStatusResponse`

NewTOTPStatusResponse instantiates a new TOTPStatusResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTOTPStatusResponseWithDefaults

`func NewTOTPStatusResponseWithDefaults() *TOTPStatusResponse`

NewTOTPStatusResponseWithDefaults instantiates a new TOTPStatusResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *TOTPStatusResponse) GetData() TOTPStatusData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *TOTPStatusResponse) GetDataOk() (*TOTPStatusData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *TOTPStatusResponse) SetData(v TOTPStatusData)`

SetData sets Data field to given value.


### GetSuccess

`func (o *TOTPStatusResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *TOTPStatusResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *TOTPStatusResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


