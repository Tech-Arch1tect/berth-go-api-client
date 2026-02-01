# ServerStatisticsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**ServerStatisticsResponseData**](ServerStatisticsResponseData.md) |  | 
**Success** | **bool** |  | 

## Methods

### NewServerStatisticsResponse

`func NewServerStatisticsResponse(data ServerStatisticsResponseData, success bool, ) *ServerStatisticsResponse`

NewServerStatisticsResponse instantiates a new ServerStatisticsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewServerStatisticsResponseWithDefaults

`func NewServerStatisticsResponseWithDefaults() *ServerStatisticsResponse`

NewServerStatisticsResponseWithDefaults instantiates a new ServerStatisticsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *ServerStatisticsResponse) GetData() ServerStatisticsResponseData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ServerStatisticsResponse) GetDataOk() (*ServerStatisticsResponseData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ServerStatisticsResponse) SetData(v ServerStatisticsResponseData)`

SetData sets Data field to given value.


### GetSuccess

`func (o *ServerStatisticsResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *ServerStatisticsResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *ServerStatisticsResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


