# RevokeRoleResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**MessageData**](MessageData.md) |  | 
**Success** | **bool** |  | 

## Methods

### NewRevokeRoleResponse

`func NewRevokeRoleResponse(data MessageData, success bool, ) *RevokeRoleResponse`

NewRevokeRoleResponse instantiates a new RevokeRoleResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRevokeRoleResponseWithDefaults

`func NewRevokeRoleResponseWithDefaults() *RevokeRoleResponse`

NewRevokeRoleResponseWithDefaults instantiates a new RevokeRoleResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *RevokeRoleResponse) GetData() MessageData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *RevokeRoleResponse) GetDataOk() (*MessageData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *RevokeRoleResponse) SetData(v MessageData)`

SetData sets Data field to given value.


### GetSuccess

`func (o *RevokeRoleResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *RevokeRoleResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *RevokeRoleResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


