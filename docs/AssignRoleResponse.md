# AssignRoleResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**MessageData**](MessageData.md) |  | 
**Success** | **bool** |  | 

## Methods

### NewAssignRoleResponse

`func NewAssignRoleResponse(data MessageData, success bool, ) *AssignRoleResponse`

NewAssignRoleResponse instantiates a new AssignRoleResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssignRoleResponseWithDefaults

`func NewAssignRoleResponseWithDefaults() *AssignRoleResponse`

NewAssignRoleResponseWithDefaults instantiates a new AssignRoleResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *AssignRoleResponse) GetData() MessageData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *AssignRoleResponse) GetDataOk() (*MessageData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *AssignRoleResponse) SetData(v MessageData)`

SetData sets Data field to given value.


### GetSuccess

`func (o *AssignRoleResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *AssignRoleResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *AssignRoleResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


