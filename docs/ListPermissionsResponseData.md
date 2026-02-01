# ListPermissionsResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Permissions** | [**[]PermissionInfo**](PermissionInfo.md) |  | 

## Methods

### NewListPermissionsResponseData

`func NewListPermissionsResponseData(permissions []PermissionInfo, ) *ListPermissionsResponseData`

NewListPermissionsResponseData instantiates a new ListPermissionsResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListPermissionsResponseDataWithDefaults

`func NewListPermissionsResponseDataWithDefaults() *ListPermissionsResponseData`

NewListPermissionsResponseDataWithDefaults instantiates a new ListPermissionsResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPermissions

`func (o *ListPermissionsResponseData) GetPermissions() []PermissionInfo`

GetPermissions returns the Permissions field if non-nil, zero value otherwise.

### GetPermissionsOk

`func (o *ListPermissionsResponseData) GetPermissionsOk() (*[]PermissionInfo, bool)`

GetPermissionsOk returns a tuple with the Permissions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissions

`func (o *ListPermissionsResponseData) SetPermissions(v []PermissionInfo)`

SetPermissions sets Permissions field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


