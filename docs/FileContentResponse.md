# FileContentResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**FileContent**](FileContent.md) |  | 
**Success** | **bool** |  | 

## Methods

### NewFileContentResponse

`func NewFileContentResponse(data FileContent, success bool, ) *FileContentResponse`

NewFileContentResponse instantiates a new FileContentResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFileContentResponseWithDefaults

`func NewFileContentResponseWithDefaults() *FileContentResponse`

NewFileContentResponseWithDefaults instantiates a new FileContentResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *FileContentResponse) GetData() FileContent`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *FileContentResponse) GetDataOk() (*FileContent, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *FileContentResponse) SetData(v FileContent)`

SetData sets Data field to given value.


### GetSuccess

`func (o *FileContentResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *FileContentResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *FileContentResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


