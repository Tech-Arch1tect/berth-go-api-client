# StartScanResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**StartScanData**](StartScanData.md) |  | 
**Success** | **bool** |  | 

## Methods

### NewStartScanResponse

`func NewStartScanResponse(data StartScanData, success bool, ) *StartScanResponse`

NewStartScanResponse instantiates a new StartScanResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStartScanResponseWithDefaults

`func NewStartScanResponseWithDefaults() *StartScanResponse`

NewStartScanResponseWithDefaults instantiates a new StartScanResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *StartScanResponse) GetData() StartScanData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *StartScanResponse) GetDataOk() (*StartScanData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *StartScanResponse) SetData(v StartScanData)`

SetData sets Data field to given value.


### GetSuccess

`func (o *StartScanResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *StartScanResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *StartScanResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


