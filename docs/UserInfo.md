# UserInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CreatedAt** | **string** |  | 
**Email** | **string** |  | 
**EmailVerifiedAt** | Pointer to **NullableString** |  | [optional] 
**Id** | **int32** |  | 
**LastLoginAt** | Pointer to **NullableString** |  | [optional] 
**Roles** | Pointer to [**[]RoleInfo**](RoleInfo.md) |  | [optional] 
**TotpEnabled** | **bool** |  | 
**UpdatedAt** | **string** |  | 
**Username** | **string** |  | 

## Methods

### NewUserInfo

`func NewUserInfo(createdAt string, email string, id int32, totpEnabled bool, updatedAt string, username string, ) *UserInfo`

NewUserInfo instantiates a new UserInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserInfoWithDefaults

`func NewUserInfoWithDefaults() *UserInfo`

NewUserInfoWithDefaults instantiates a new UserInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreatedAt

`func (o *UserInfo) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *UserInfo) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *UserInfo) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetEmail

`func (o *UserInfo) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *UserInfo) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *UserInfo) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetEmailVerifiedAt

`func (o *UserInfo) GetEmailVerifiedAt() string`

GetEmailVerifiedAt returns the EmailVerifiedAt field if non-nil, zero value otherwise.

### GetEmailVerifiedAtOk

`func (o *UserInfo) GetEmailVerifiedAtOk() (*string, bool)`

GetEmailVerifiedAtOk returns a tuple with the EmailVerifiedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmailVerifiedAt

`func (o *UserInfo) SetEmailVerifiedAt(v string)`

SetEmailVerifiedAt sets EmailVerifiedAt field to given value.

### HasEmailVerifiedAt

`func (o *UserInfo) HasEmailVerifiedAt() bool`

HasEmailVerifiedAt returns a boolean if a field has been set.

### SetEmailVerifiedAtNil

`func (o *UserInfo) SetEmailVerifiedAtNil(b bool)`

 SetEmailVerifiedAtNil sets the value for EmailVerifiedAt to be an explicit nil

### UnsetEmailVerifiedAt
`func (o *UserInfo) UnsetEmailVerifiedAt()`

UnsetEmailVerifiedAt ensures that no value is present for EmailVerifiedAt, not even an explicit nil
### GetId

`func (o *UserInfo) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *UserInfo) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *UserInfo) SetId(v int32)`

SetId sets Id field to given value.


### GetLastLoginAt

`func (o *UserInfo) GetLastLoginAt() string`

GetLastLoginAt returns the LastLoginAt field if non-nil, zero value otherwise.

### GetLastLoginAtOk

`func (o *UserInfo) GetLastLoginAtOk() (*string, bool)`

GetLastLoginAtOk returns a tuple with the LastLoginAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastLoginAt

`func (o *UserInfo) SetLastLoginAt(v string)`

SetLastLoginAt sets LastLoginAt field to given value.

### HasLastLoginAt

`func (o *UserInfo) HasLastLoginAt() bool`

HasLastLoginAt returns a boolean if a field has been set.

### SetLastLoginAtNil

`func (o *UserInfo) SetLastLoginAtNil(b bool)`

 SetLastLoginAtNil sets the value for LastLoginAt to be an explicit nil

### UnsetLastLoginAt
`func (o *UserInfo) UnsetLastLoginAt()`

UnsetLastLoginAt ensures that no value is present for LastLoginAt, not even an explicit nil
### GetRoles

`func (o *UserInfo) GetRoles() []RoleInfo`

GetRoles returns the Roles field if non-nil, zero value otherwise.

### GetRolesOk

`func (o *UserInfo) GetRolesOk() (*[]RoleInfo, bool)`

GetRolesOk returns a tuple with the Roles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoles

`func (o *UserInfo) SetRoles(v []RoleInfo)`

SetRoles sets Roles field to given value.

### HasRoles

`func (o *UserInfo) HasRoles() bool`

HasRoles returns a boolean if a field has been set.

### GetTotpEnabled

`func (o *UserInfo) GetTotpEnabled() bool`

GetTotpEnabled returns the TotpEnabled field if non-nil, zero value otherwise.

### GetTotpEnabledOk

`func (o *UserInfo) GetTotpEnabledOk() (*bool, bool)`

GetTotpEnabledOk returns a tuple with the TotpEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotpEnabled

`func (o *UserInfo) SetTotpEnabled(v bool)`

SetTotpEnabled sets TotpEnabled field to given value.


### GetUpdatedAt

`func (o *UserInfo) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *UserInfo) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *UserInfo) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetUsername

`func (o *UserInfo) GetUsername() string`

GetUsername returns the Username field if non-nil, zero value otherwise.

### GetUsernameOk

`func (o *UserInfo) GetUsernameOk() (*string, bool)`

GetUsernameOk returns a tuple with the Username field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsername

`func (o *UserInfo) SetUsername(v string)`

SetUsername sets Username field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


