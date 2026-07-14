# ListResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Configured** | **bool** |  | 
**Runs** | [**[]Run**](Run.md) |  | 

## Methods

### NewListResponse

`func NewListResponse(configured bool, runs []Run, ) *ListResponse`

NewListResponse instantiates a new ListResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListResponseWithDefaults

`func NewListResponseWithDefaults() *ListResponse`

NewListResponseWithDefaults instantiates a new ListResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConfigured

`func (o *ListResponse) GetConfigured() bool`

GetConfigured returns the Configured field if non-nil, zero value otherwise.

### GetConfiguredOk

`func (o *ListResponse) GetConfiguredOk() (*bool, bool)`

GetConfiguredOk returns a tuple with the Configured field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfigured

`func (o *ListResponse) SetConfigured(v bool)`

SetConfigured sets Configured field to given value.


### GetRuns

`func (o *ListResponse) GetRuns() []Run`

GetRuns returns the Runs field if non-nil, zero value otherwise.

### GetRunsOk

`func (o *ListResponse) GetRunsOk() (*[]Run, bool)`

GetRunsOk returns a tuple with the Runs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRuns

`func (o *ListResponse) SetRuns(v []Run)`

SetRuns sets Runs field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


