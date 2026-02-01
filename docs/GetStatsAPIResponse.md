# GetStatsAPIResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**StatsResponseData**](StatsResponseData.md) |  | 
**Success** | **bool** |  | 

## Methods

### NewGetStatsAPIResponse

`func NewGetStatsAPIResponse(data StatsResponseData, success bool, ) *GetStatsAPIResponse`

NewGetStatsAPIResponse instantiates a new GetStatsAPIResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetStatsAPIResponseWithDefaults

`func NewGetStatsAPIResponseWithDefaults() *GetStatsAPIResponse`

NewGetStatsAPIResponseWithDefaults instantiates a new GetStatsAPIResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *GetStatsAPIResponse) GetData() StatsResponseData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetStatsAPIResponse) GetDataOk() (*StatsResponseData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetStatsAPIResponse) SetData(v StatsResponseData)`

SetData sets Data field to given value.


### GetSuccess

`func (o *GetStatsAPIResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *GetStatsAPIResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *GetStatsAPIResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


