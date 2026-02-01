# ContainerImageDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ContainerName** | **string** |  | 
**ImageHistory** | [**[]ImageHistoryLayer**](ImageHistoryLayer.md) |  | 
**ImageId** | **string** |  | 
**ImageInfo** | [**ImageInspectInfo**](ImageInspectInfo.md) |  | 
**ImageName** | **string** |  | 

## Methods

### NewContainerImageDetails

`func NewContainerImageDetails(containerName string, imageHistory []ImageHistoryLayer, imageId string, imageInfo ImageInspectInfo, imageName string, ) *ContainerImageDetails`

NewContainerImageDetails instantiates a new ContainerImageDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContainerImageDetailsWithDefaults

`func NewContainerImageDetailsWithDefaults() *ContainerImageDetails`

NewContainerImageDetailsWithDefaults instantiates a new ContainerImageDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContainerName

`func (o *ContainerImageDetails) GetContainerName() string`

GetContainerName returns the ContainerName field if non-nil, zero value otherwise.

### GetContainerNameOk

`func (o *ContainerImageDetails) GetContainerNameOk() (*string, bool)`

GetContainerNameOk returns a tuple with the ContainerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainerName

`func (o *ContainerImageDetails) SetContainerName(v string)`

SetContainerName sets ContainerName field to given value.


### GetImageHistory

`func (o *ContainerImageDetails) GetImageHistory() []ImageHistoryLayer`

GetImageHistory returns the ImageHistory field if non-nil, zero value otherwise.

### GetImageHistoryOk

`func (o *ContainerImageDetails) GetImageHistoryOk() (*[]ImageHistoryLayer, bool)`

GetImageHistoryOk returns a tuple with the ImageHistory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageHistory

`func (o *ContainerImageDetails) SetImageHistory(v []ImageHistoryLayer)`

SetImageHistory sets ImageHistory field to given value.


### GetImageId

`func (o *ContainerImageDetails) GetImageId() string`

GetImageId returns the ImageId field if non-nil, zero value otherwise.

### GetImageIdOk

`func (o *ContainerImageDetails) GetImageIdOk() (*string, bool)`

GetImageIdOk returns a tuple with the ImageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageId

`func (o *ContainerImageDetails) SetImageId(v string)`

SetImageId sets ImageId field to given value.


### GetImageInfo

`func (o *ContainerImageDetails) GetImageInfo() ImageInspectInfo`

GetImageInfo returns the ImageInfo field if non-nil, zero value otherwise.

### GetImageInfoOk

`func (o *ContainerImageDetails) GetImageInfoOk() (*ImageInspectInfo, bool)`

GetImageInfoOk returns a tuple with the ImageInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageInfo

`func (o *ContainerImageDetails) SetImageInfo(v ImageInspectInfo)`

SetImageInfo sets ImageInfo field to given value.


### GetImageName

`func (o *ContainerImageDetails) GetImageName() string`

GetImageName returns the ImageName field if non-nil, zero value otherwise.

### GetImageNameOk

`func (o *ContainerImageDetails) GetImageNameOk() (*string, bool)`

GetImageNameOk returns a tuple with the ImageName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageName

`func (o *ContainerImageDetails) SetImageName(v string)`

SetImageName sets ImageName field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


