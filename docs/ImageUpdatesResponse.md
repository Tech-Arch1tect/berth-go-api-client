# ImageUpdatesResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**ImageUpdatesDataInner**](ImageUpdatesDataInner.md) |  | 
**Success** | **bool** |  | 

## Methods

### NewImageUpdatesResponse

`func NewImageUpdatesResponse(data ImageUpdatesDataInner, success bool, ) *ImageUpdatesResponse`

NewImageUpdatesResponse instantiates a new ImageUpdatesResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImageUpdatesResponseWithDefaults

`func NewImageUpdatesResponseWithDefaults() *ImageUpdatesResponse`

NewImageUpdatesResponseWithDefaults instantiates a new ImageUpdatesResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *ImageUpdatesResponse) GetData() ImageUpdatesDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ImageUpdatesResponse) GetDataOk() (*ImageUpdatesDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ImageUpdatesResponse) SetData(v ImageUpdatesDataInner)`

SetData sets Data field to given value.


### GetSuccess

`func (o *ImageUpdatesResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *ImageUpdatesResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *ImageUpdatesResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


