# PermissionsResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Maintenance** | [**MaintenancePermissions**](MaintenancePermissions.md) |  | 

## Methods

### NewPermissionsResponseData

`func NewPermissionsResponseData(maintenance MaintenancePermissions, ) *PermissionsResponseData`

NewPermissionsResponseData instantiates a new PermissionsResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPermissionsResponseDataWithDefaults

`func NewPermissionsResponseDataWithDefaults() *PermissionsResponseData`

NewPermissionsResponseDataWithDefaults instantiates a new PermissionsResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMaintenance

`func (o *PermissionsResponseData) GetMaintenance() MaintenancePermissions`

GetMaintenance returns the Maintenance field if non-nil, zero value otherwise.

### GetMaintenanceOk

`func (o *PermissionsResponseData) GetMaintenanceOk() (*MaintenancePermissions, bool)`

GetMaintenanceOk returns a tuple with the Maintenance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaintenance

`func (o *PermissionsResponseData) SetMaintenance(v MaintenancePermissions)`

SetMaintenance sets Maintenance field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


