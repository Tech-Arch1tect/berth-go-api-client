# PermissionsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**PermissionsResponseData**](PermissionsResponseData.md) |  | 
**Success** | **bool** |  | 

## Methods

### NewPermissionsResponse

`func NewPermissionsResponse(data PermissionsResponseData, success bool, ) *PermissionsResponse`

NewPermissionsResponse instantiates a new PermissionsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPermissionsResponseWithDefaults

`func NewPermissionsResponseWithDefaults() *PermissionsResponse`

NewPermissionsResponseWithDefaults instantiates a new PermissionsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *PermissionsResponse) GetData() PermissionsResponseData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *PermissionsResponse) GetDataOk() (*PermissionsResponseData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *PermissionsResponse) SetData(v PermissionsResponseData)`

SetData sets Data field to given value.


### GetSuccess

`func (o *PermissionsResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *PermissionsResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *PermissionsResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


