# CanCreateStackResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**CanCreateStackData**](CanCreateStackData.md) |  | 
**Success** | **bool** |  | 

## Methods

### NewCanCreateStackResponse

`func NewCanCreateStackResponse(data CanCreateStackData, success bool, ) *CanCreateStackResponse`

NewCanCreateStackResponse instantiates a new CanCreateStackResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCanCreateStackResponseWithDefaults

`func NewCanCreateStackResponseWithDefaults() *CanCreateStackResponse`

NewCanCreateStackResponseWithDefaults instantiates a new CanCreateStackResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *CanCreateStackResponse) GetData() CanCreateStackData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *CanCreateStackResponse) GetDataOk() (*CanCreateStackData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *CanCreateStackResponse) SetData(v CanCreateStackData)`

SetData sets Data field to given value.


### GetSuccess

`func (o *CanCreateStackResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *CanCreateStackResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *CanCreateStackResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


