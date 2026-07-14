# Component

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BytesAdded** | **int32** |  | 
**BytesProcessed** | **int32** |  | 
**DurationSecs** | **float32** |  | 
**Error** | Pointer to **string** |  | [optional] 
**Excludes** | Pointer to **[]string** |  | [optional] 
**FilesChanged** | **int32** |  | 
**FilesNew** | **int32** |  | 
**FilesUnmodified** | **int32** |  | 
**Id** | **string** |  | 
**Kind** | **string** |  | 
**Service** | Pointer to **string** |  | [optional] 
**SnapshotId** | Pointer to **string** |  | [optional] 
**SourcePath** | Pointer to **string** |  | [optional] 
**Target** | Pointer to **string** |  | [optional] 
**VolumeName** | Pointer to **string** |  | [optional] 

## Methods

### NewComponent

`func NewComponent(bytesAdded int32, bytesProcessed int32, durationSecs float32, filesChanged int32, filesNew int32, filesUnmodified int32, id string, kind string, ) *Component`

NewComponent instantiates a new Component object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewComponentWithDefaults

`func NewComponentWithDefaults() *Component`

NewComponentWithDefaults instantiates a new Component object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBytesAdded

`func (o *Component) GetBytesAdded() int32`

GetBytesAdded returns the BytesAdded field if non-nil, zero value otherwise.

### GetBytesAddedOk

`func (o *Component) GetBytesAddedOk() (*int32, bool)`

GetBytesAddedOk returns a tuple with the BytesAdded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBytesAdded

`func (o *Component) SetBytesAdded(v int32)`

SetBytesAdded sets BytesAdded field to given value.


### GetBytesProcessed

`func (o *Component) GetBytesProcessed() int32`

GetBytesProcessed returns the BytesProcessed field if non-nil, zero value otherwise.

### GetBytesProcessedOk

`func (o *Component) GetBytesProcessedOk() (*int32, bool)`

GetBytesProcessedOk returns a tuple with the BytesProcessed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBytesProcessed

`func (o *Component) SetBytesProcessed(v int32)`

SetBytesProcessed sets BytesProcessed field to given value.


### GetDurationSecs

`func (o *Component) GetDurationSecs() float32`

GetDurationSecs returns the DurationSecs field if non-nil, zero value otherwise.

### GetDurationSecsOk

`func (o *Component) GetDurationSecsOk() (*float32, bool)`

GetDurationSecsOk returns a tuple with the DurationSecs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDurationSecs

`func (o *Component) SetDurationSecs(v float32)`

SetDurationSecs sets DurationSecs field to given value.


### GetError

`func (o *Component) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *Component) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *Component) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *Component) HasError() bool`

HasError returns a boolean if a field has been set.

### GetExcludes

`func (o *Component) GetExcludes() []string`

GetExcludes returns the Excludes field if non-nil, zero value otherwise.

### GetExcludesOk

`func (o *Component) GetExcludesOk() (*[]string, bool)`

GetExcludesOk returns a tuple with the Excludes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExcludes

`func (o *Component) SetExcludes(v []string)`

SetExcludes sets Excludes field to given value.

### HasExcludes

`func (o *Component) HasExcludes() bool`

HasExcludes returns a boolean if a field has been set.

### GetFilesChanged

`func (o *Component) GetFilesChanged() int32`

GetFilesChanged returns the FilesChanged field if non-nil, zero value otherwise.

### GetFilesChangedOk

`func (o *Component) GetFilesChangedOk() (*int32, bool)`

GetFilesChangedOk returns a tuple with the FilesChanged field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilesChanged

`func (o *Component) SetFilesChanged(v int32)`

SetFilesChanged sets FilesChanged field to given value.


### GetFilesNew

`func (o *Component) GetFilesNew() int32`

GetFilesNew returns the FilesNew field if non-nil, zero value otherwise.

### GetFilesNewOk

`func (o *Component) GetFilesNewOk() (*int32, bool)`

GetFilesNewOk returns a tuple with the FilesNew field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilesNew

`func (o *Component) SetFilesNew(v int32)`

SetFilesNew sets FilesNew field to given value.


### GetFilesUnmodified

`func (o *Component) GetFilesUnmodified() int32`

GetFilesUnmodified returns the FilesUnmodified field if non-nil, zero value otherwise.

### GetFilesUnmodifiedOk

`func (o *Component) GetFilesUnmodifiedOk() (*int32, bool)`

GetFilesUnmodifiedOk returns a tuple with the FilesUnmodified field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilesUnmodified

`func (o *Component) SetFilesUnmodified(v int32)`

SetFilesUnmodified sets FilesUnmodified field to given value.


### GetId

`func (o *Component) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Component) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Component) SetId(v string)`

SetId sets Id field to given value.


### GetKind

`func (o *Component) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *Component) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *Component) SetKind(v string)`

SetKind sets Kind field to given value.


### GetService

`func (o *Component) GetService() string`

GetService returns the Service field if non-nil, zero value otherwise.

### GetServiceOk

`func (o *Component) GetServiceOk() (*string, bool)`

GetServiceOk returns a tuple with the Service field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetService

`func (o *Component) SetService(v string)`

SetService sets Service field to given value.

### HasService

`func (o *Component) HasService() bool`

HasService returns a boolean if a field has been set.

### GetSnapshotId

`func (o *Component) GetSnapshotId() string`

GetSnapshotId returns the SnapshotId field if non-nil, zero value otherwise.

### GetSnapshotIdOk

`func (o *Component) GetSnapshotIdOk() (*string, bool)`

GetSnapshotIdOk returns a tuple with the SnapshotId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnapshotId

`func (o *Component) SetSnapshotId(v string)`

SetSnapshotId sets SnapshotId field to given value.

### HasSnapshotId

`func (o *Component) HasSnapshotId() bool`

HasSnapshotId returns a boolean if a field has been set.

### GetSourcePath

`func (o *Component) GetSourcePath() string`

GetSourcePath returns the SourcePath field if non-nil, zero value otherwise.

### GetSourcePathOk

`func (o *Component) GetSourcePathOk() (*string, bool)`

GetSourcePathOk returns a tuple with the SourcePath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourcePath

`func (o *Component) SetSourcePath(v string)`

SetSourcePath sets SourcePath field to given value.

### HasSourcePath

`func (o *Component) HasSourcePath() bool`

HasSourcePath returns a boolean if a field has been set.

### GetTarget

`func (o *Component) GetTarget() string`

GetTarget returns the Target field if non-nil, zero value otherwise.

### GetTargetOk

`func (o *Component) GetTargetOk() (*string, bool)`

GetTargetOk returns a tuple with the Target field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTarget

`func (o *Component) SetTarget(v string)`

SetTarget sets Target field to given value.

### HasTarget

`func (o *Component) HasTarget() bool`

HasTarget returns a boolean if a field has been set.

### GetVolumeName

`func (o *Component) GetVolumeName() string`

GetVolumeName returns the VolumeName field if non-nil, zero value otherwise.

### GetVolumeNameOk

`func (o *Component) GetVolumeNameOk() (*string, bool)`

GetVolumeNameOk returns a tuple with the VolumeName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVolumeName

`func (o *Component) SetVolumeName(v string)`

SetVolumeName sets VolumeName field to given value.

### HasVolumeName

`func (o *Component) HasVolumeName() bool`

HasVolumeName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


