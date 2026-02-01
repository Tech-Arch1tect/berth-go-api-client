# TOTPSetupResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**TOTPSetupData**](TOTPSetupData.md) |  | 
**Success** | **bool** |  | 

## Methods

### NewTOTPSetupResponse

`func NewTOTPSetupResponse(data TOTPSetupData, success bool, ) *TOTPSetupResponse`

NewTOTPSetupResponse instantiates a new TOTPSetupResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTOTPSetupResponseWithDefaults

`func NewTOTPSetupResponseWithDefaults() *TOTPSetupResponse`

NewTOTPSetupResponseWithDefaults instantiates a new TOTPSetupResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *TOTPSetupResponse) GetData() TOTPSetupData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *TOTPSetupResponse) GetDataOk() (*TOTPSetupData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *TOTPSetupResponse) SetData(v TOTPSetupData)`

SetData sets Data field to given value.


### GetSuccess

`func (o *TOTPSetupResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *TOTPSetupResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *TOTPSetupResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


