# CreateUserResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**UserInfo**](UserInfo.md) |  | 
**Success** | **bool** |  | 

## Methods

### NewCreateUserResponse

`func NewCreateUserResponse(data UserInfo, success bool, ) *CreateUserResponse`

NewCreateUserResponse instantiates a new CreateUserResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateUserResponseWithDefaults

`func NewCreateUserResponseWithDefaults() *CreateUserResponse`

NewCreateUserResponseWithDefaults instantiates a new CreateUserResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *CreateUserResponse) GetData() UserInfo`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *CreateUserResponse) GetDataOk() (*UserInfo, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *CreateUserResponse) SetData(v UserInfo)`

SetData sets Data field to given value.


### GetSuccess

`func (o *CreateUserResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *CreateUserResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *CreateUserResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


