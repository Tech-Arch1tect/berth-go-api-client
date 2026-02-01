# GetUserRolesResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**GetUserRolesResponseData**](GetUserRolesResponseData.md) |  | 
**Success** | **bool** |  | 

## Methods

### NewGetUserRolesResponse

`func NewGetUserRolesResponse(data GetUserRolesResponseData, success bool, ) *GetUserRolesResponse`

NewGetUserRolesResponse instantiates a new GetUserRolesResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetUserRolesResponseWithDefaults

`func NewGetUserRolesResponseWithDefaults() *GetUserRolesResponse`

NewGetUserRolesResponseWithDefaults instantiates a new GetUserRolesResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *GetUserRolesResponse) GetData() GetUserRolesResponseData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetUserRolesResponse) GetDataOk() (*GetUserRolesResponseData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetUserRolesResponse) SetData(v GetUserRolesResponseData)`

SetData sets Data field to given value.


### GetSuccess

`func (o *GetUserRolesResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *GetUserRolesResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *GetUserRolesResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


