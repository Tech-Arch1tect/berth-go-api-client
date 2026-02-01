# Port

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Private** | **int32** |  | 
**Public** | Pointer to **int32** |  | [optional] 
**Type** | **string** |  | 

## Methods

### NewPort

`func NewPort(private int32, type_ string, ) *Port`

NewPort instantiates a new Port object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPortWithDefaults

`func NewPortWithDefaults() *Port`

NewPortWithDefaults instantiates a new Port object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPrivate

`func (o *Port) GetPrivate() int32`

GetPrivate returns the Private field if non-nil, zero value otherwise.

### GetPrivateOk

`func (o *Port) GetPrivateOk() (*int32, bool)`

GetPrivateOk returns a tuple with the Private field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrivate

`func (o *Port) SetPrivate(v int32)`

SetPrivate sets Private field to given value.


### GetPublic

`func (o *Port) GetPublic() int32`

GetPublic returns the Public field if non-nil, zero value otherwise.

### GetPublicOk

`func (o *Port) GetPublicOk() (*int32, bool)`

GetPublicOk returns a tuple with the Public field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublic

`func (o *Port) SetPublic(v int32)`

SetPublic sets Public field to given value.

### HasPublic

`func (o *Port) HasPublic() bool`

HasPublic returns a boolean if a field has been set.

### GetType

`func (o *Port) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Port) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Port) SetType(v string)`

SetType sets Type field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


