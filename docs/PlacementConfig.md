# PlacementConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Constraints** | Pointer to **[]string** |  | [optional] 
**Preferences** | Pointer to [**[]PlacementPreference**](PlacementPreference.md) |  | [optional] 

## Methods

### NewPlacementConfig

`func NewPlacementConfig() *PlacementConfig`

NewPlacementConfig instantiates a new PlacementConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPlacementConfigWithDefaults

`func NewPlacementConfigWithDefaults() *PlacementConfig`

NewPlacementConfigWithDefaults instantiates a new PlacementConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConstraints

`func (o *PlacementConfig) GetConstraints() []string`

GetConstraints returns the Constraints field if non-nil, zero value otherwise.

### GetConstraintsOk

`func (o *PlacementConfig) GetConstraintsOk() (*[]string, bool)`

GetConstraintsOk returns a tuple with the Constraints field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConstraints

`func (o *PlacementConfig) SetConstraints(v []string)`

SetConstraints sets Constraints field to given value.

### HasConstraints

`func (o *PlacementConfig) HasConstraints() bool`

HasConstraints returns a boolean if a field has been set.

### GetPreferences

`func (o *PlacementConfig) GetPreferences() []PlacementPreference`

GetPreferences returns the Preferences field if non-nil, zero value otherwise.

### GetPreferencesOk

`func (o *PlacementConfig) GetPreferencesOk() (*[]PlacementPreference, bool)`

GetPreferencesOk returns a tuple with the Preferences field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreferences

`func (o *PlacementConfig) SetPreferences(v []PlacementPreference)`

SetPreferences sets Preferences field to given value.

### HasPreferences

`func (o *PlacementConfig) HasPreferences() bool`

HasPreferences returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


