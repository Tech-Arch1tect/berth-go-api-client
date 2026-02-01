# Server

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CreatedAt** | **time.Time** |  | 
**DeletedAt** | Pointer to [**DeletedAt**](DeletedAt.md) |  | [optional] 
**Description** | **string** |  | 
**Host** | **string** |  | 
**Id** | **int32** |  | 
**IsActive** | **bool** |  | 
**Name** | **string** |  | 
**Port** | **int32** |  | 
**SkipSslVerification** | Pointer to **NullableBool** |  | [optional] 
**UpdatedAt** | **time.Time** |  | 

## Methods

### NewServer

`func NewServer(createdAt time.Time, description string, host string, id int32, isActive bool, name string, port int32, updatedAt time.Time, ) *Server`

NewServer instantiates a new Server object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewServerWithDefaults

`func NewServerWithDefaults() *Server`

NewServerWithDefaults instantiates a new Server object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreatedAt

`func (o *Server) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Server) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Server) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetDeletedAt

`func (o *Server) GetDeletedAt() DeletedAt`

GetDeletedAt returns the DeletedAt field if non-nil, zero value otherwise.

### GetDeletedAtOk

`func (o *Server) GetDeletedAtOk() (*DeletedAt, bool)`

GetDeletedAtOk returns a tuple with the DeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedAt

`func (o *Server) SetDeletedAt(v DeletedAt)`

SetDeletedAt sets DeletedAt field to given value.

### HasDeletedAt

`func (o *Server) HasDeletedAt() bool`

HasDeletedAt returns a boolean if a field has been set.

### GetDescription

`func (o *Server) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *Server) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *Server) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetHost

`func (o *Server) GetHost() string`

GetHost returns the Host field if non-nil, zero value otherwise.

### GetHostOk

`func (o *Server) GetHostOk() (*string, bool)`

GetHostOk returns a tuple with the Host field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHost

`func (o *Server) SetHost(v string)`

SetHost sets Host field to given value.


### GetId

`func (o *Server) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Server) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Server) SetId(v int32)`

SetId sets Id field to given value.


### GetIsActive

`func (o *Server) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *Server) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *Server) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.


### GetName

`func (o *Server) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Server) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Server) SetName(v string)`

SetName sets Name field to given value.


### GetPort

`func (o *Server) GetPort() int32`

GetPort returns the Port field if non-nil, zero value otherwise.

### GetPortOk

`func (o *Server) GetPortOk() (*int32, bool)`

GetPortOk returns a tuple with the Port field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPort

`func (o *Server) SetPort(v int32)`

SetPort sets Port field to given value.


### GetSkipSslVerification

`func (o *Server) GetSkipSslVerification() bool`

GetSkipSslVerification returns the SkipSslVerification field if non-nil, zero value otherwise.

### GetSkipSslVerificationOk

`func (o *Server) GetSkipSslVerificationOk() (*bool, bool)`

GetSkipSslVerificationOk returns a tuple with the SkipSslVerification field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSkipSslVerification

`func (o *Server) SetSkipSslVerification(v bool)`

SetSkipSslVerification sets SkipSslVerification field to given value.

### HasSkipSslVerification

`func (o *Server) HasSkipSslVerification() bool`

HasSkipSslVerification returns a boolean if a field has been set.

### SetSkipSslVerificationNil

`func (o *Server) SetSkipSslVerificationNil(b bool)`

 SetSkipSslVerificationNil sets the value for SkipSslVerification to be an explicit nil

### UnsetSkipSslVerification
`func (o *Server) UnsetSkipSslVerification()`

UnsetSkipSslVerification ensures that no value is present for SkipSslVerification, not even an explicit nil
### GetUpdatedAt

`func (o *Server) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Server) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Server) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


