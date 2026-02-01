# GetVersionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**VersionData**](VersionData.md) |  | 
**Success** | **bool** |  | 

## Methods

### NewGetVersionResponse

`func NewGetVersionResponse(data VersionData, success bool, ) *GetVersionResponse`

NewGetVersionResponse instantiates a new GetVersionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetVersionResponseWithDefaults

`func NewGetVersionResponseWithDefaults() *GetVersionResponse`

NewGetVersionResponseWithDefaults instantiates a new GetVersionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *GetVersionResponse) GetData() VersionData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetVersionResponse) GetDataOk() (*VersionData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetVersionResponse) SetData(v VersionData)`

SetData sets Data field to given value.


### GetSuccess

`func (o *GetVersionResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *GetVersionResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *GetVersionResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


