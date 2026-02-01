# PermissionInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Action** | **string** |  | 
**Description** | **string** |  | 
**Id** | **int32** |  | 
**IsApiKeyOnly** | **bool** |  | 
**Name** | **string** |  | 
**Resource** | **string** |  | 

## Methods

### NewPermissionInfo

`func NewPermissionInfo(action string, description string, id int32, isApiKeyOnly bool, name string, resource string, ) *PermissionInfo`

NewPermissionInfo instantiates a new PermissionInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPermissionInfoWithDefaults

`func NewPermissionInfoWithDefaults() *PermissionInfo`

NewPermissionInfoWithDefaults instantiates a new PermissionInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAction

`func (o *PermissionInfo) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *PermissionInfo) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *PermissionInfo) SetAction(v string)`

SetAction sets Action field to given value.


### GetDescription

`func (o *PermissionInfo) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *PermissionInfo) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *PermissionInfo) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetId

`func (o *PermissionInfo) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PermissionInfo) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PermissionInfo) SetId(v int32)`

SetId sets Id field to given value.


### GetIsApiKeyOnly

`func (o *PermissionInfo) GetIsApiKeyOnly() bool`

GetIsApiKeyOnly returns the IsApiKeyOnly field if non-nil, zero value otherwise.

### GetIsApiKeyOnlyOk

`func (o *PermissionInfo) GetIsApiKeyOnlyOk() (*bool, bool)`

GetIsApiKeyOnlyOk returns a tuple with the IsApiKeyOnly field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsApiKeyOnly

`func (o *PermissionInfo) SetIsApiKeyOnly(v bool)`

SetIsApiKeyOnly sets IsApiKeyOnly field to given value.


### GetName

`func (o *PermissionInfo) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PermissionInfo) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PermissionInfo) SetName(v string)`

SetName sets Name field to given value.


### GetResource

`func (o *PermissionInfo) GetResource() string`

GetResource returns the Resource field if non-nil, zero value otherwise.

### GetResourceOk

`func (o *PermissionInfo) GetResourceOk() (*string, bool)`

GetResourceOk returns a tuple with the Resource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResource

`func (o *PermissionInfo) SetResource(v string)`

SetResource sets Resource field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


