# SessionItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Bot** | **bool** |  | 
**Browser** | **string** |  | 
**CreatedAt** | **time.Time** |  | 
**Current** | **bool** |  | 
**Desktop** | **bool** |  | 
**Device** | **string** |  | 
**DeviceType** | **string** |  | 
**ExpiresAt** | **time.Time** |  | 
**Id** | **int32** |  | 
**IpAddress** | **string** |  | 
**LastUsed** | **time.Time** |  | 
**Location** | **string** |  | 
**Mobile** | **bool** |  | 
**Os** | **string** |  | 
**Tablet** | **bool** |  | 
**Token** | **string** |  | 
**Type** | **string** |  | 
**UserAgent** | **string** |  | 
**UserId** | **int32** |  | 

## Methods

### NewSessionItem

`func NewSessionItem(bot bool, browser string, createdAt time.Time, current bool, desktop bool, device string, deviceType string, expiresAt time.Time, id int32, ipAddress string, lastUsed time.Time, location string, mobile bool, os string, tablet bool, token string, type_ string, userAgent string, userId int32, ) *SessionItem`

NewSessionItem instantiates a new SessionItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSessionItemWithDefaults

`func NewSessionItemWithDefaults() *SessionItem`

NewSessionItemWithDefaults instantiates a new SessionItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBot

`func (o *SessionItem) GetBot() bool`

GetBot returns the Bot field if non-nil, zero value otherwise.

### GetBotOk

`func (o *SessionItem) GetBotOk() (*bool, bool)`

GetBotOk returns a tuple with the Bot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBot

`func (o *SessionItem) SetBot(v bool)`

SetBot sets Bot field to given value.


### GetBrowser

`func (o *SessionItem) GetBrowser() string`

GetBrowser returns the Browser field if non-nil, zero value otherwise.

### GetBrowserOk

`func (o *SessionItem) GetBrowserOk() (*string, bool)`

GetBrowserOk returns a tuple with the Browser field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrowser

`func (o *SessionItem) SetBrowser(v string)`

SetBrowser sets Browser field to given value.


### GetCreatedAt

`func (o *SessionItem) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *SessionItem) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *SessionItem) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetCurrent

`func (o *SessionItem) GetCurrent() bool`

GetCurrent returns the Current field if non-nil, zero value otherwise.

### GetCurrentOk

`func (o *SessionItem) GetCurrentOk() (*bool, bool)`

GetCurrentOk returns a tuple with the Current field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrent

`func (o *SessionItem) SetCurrent(v bool)`

SetCurrent sets Current field to given value.


### GetDesktop

`func (o *SessionItem) GetDesktop() bool`

GetDesktop returns the Desktop field if non-nil, zero value otherwise.

### GetDesktopOk

`func (o *SessionItem) GetDesktopOk() (*bool, bool)`

GetDesktopOk returns a tuple with the Desktop field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDesktop

`func (o *SessionItem) SetDesktop(v bool)`

SetDesktop sets Desktop field to given value.


### GetDevice

`func (o *SessionItem) GetDevice() string`

GetDevice returns the Device field if non-nil, zero value otherwise.

### GetDeviceOk

`func (o *SessionItem) GetDeviceOk() (*string, bool)`

GetDeviceOk returns a tuple with the Device field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDevice

`func (o *SessionItem) SetDevice(v string)`

SetDevice sets Device field to given value.


### GetDeviceType

`func (o *SessionItem) GetDeviceType() string`

GetDeviceType returns the DeviceType field if non-nil, zero value otherwise.

### GetDeviceTypeOk

`func (o *SessionItem) GetDeviceTypeOk() (*string, bool)`

GetDeviceTypeOk returns a tuple with the DeviceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceType

`func (o *SessionItem) SetDeviceType(v string)`

SetDeviceType sets DeviceType field to given value.


### GetExpiresAt

`func (o *SessionItem) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *SessionItem) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *SessionItem) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.


### GetId

`func (o *SessionItem) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SessionItem) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SessionItem) SetId(v int32)`

SetId sets Id field to given value.


### GetIpAddress

`func (o *SessionItem) GetIpAddress() string`

GetIpAddress returns the IpAddress field if non-nil, zero value otherwise.

### GetIpAddressOk

`func (o *SessionItem) GetIpAddressOk() (*string, bool)`

GetIpAddressOk returns a tuple with the IpAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpAddress

`func (o *SessionItem) SetIpAddress(v string)`

SetIpAddress sets IpAddress field to given value.


### GetLastUsed

`func (o *SessionItem) GetLastUsed() time.Time`

GetLastUsed returns the LastUsed field if non-nil, zero value otherwise.

### GetLastUsedOk

`func (o *SessionItem) GetLastUsedOk() (*time.Time, bool)`

GetLastUsedOk returns a tuple with the LastUsed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastUsed

`func (o *SessionItem) SetLastUsed(v time.Time)`

SetLastUsed sets LastUsed field to given value.


### GetLocation

`func (o *SessionItem) GetLocation() string`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *SessionItem) GetLocationOk() (*string, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *SessionItem) SetLocation(v string)`

SetLocation sets Location field to given value.


### GetMobile

`func (o *SessionItem) GetMobile() bool`

GetMobile returns the Mobile field if non-nil, zero value otherwise.

### GetMobileOk

`func (o *SessionItem) GetMobileOk() (*bool, bool)`

GetMobileOk returns a tuple with the Mobile field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMobile

`func (o *SessionItem) SetMobile(v bool)`

SetMobile sets Mobile field to given value.


### GetOs

`func (o *SessionItem) GetOs() string`

GetOs returns the Os field if non-nil, zero value otherwise.

### GetOsOk

`func (o *SessionItem) GetOsOk() (*string, bool)`

GetOsOk returns a tuple with the Os field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOs

`func (o *SessionItem) SetOs(v string)`

SetOs sets Os field to given value.


### GetTablet

`func (o *SessionItem) GetTablet() bool`

GetTablet returns the Tablet field if non-nil, zero value otherwise.

### GetTabletOk

`func (o *SessionItem) GetTabletOk() (*bool, bool)`

GetTabletOk returns a tuple with the Tablet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTablet

`func (o *SessionItem) SetTablet(v bool)`

SetTablet sets Tablet field to given value.


### GetToken

`func (o *SessionItem) GetToken() string`

GetToken returns the Token field if non-nil, zero value otherwise.

### GetTokenOk

`func (o *SessionItem) GetTokenOk() (*string, bool)`

GetTokenOk returns a tuple with the Token field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToken

`func (o *SessionItem) SetToken(v string)`

SetToken sets Token field to given value.


### GetType

`func (o *SessionItem) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *SessionItem) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *SessionItem) SetType(v string)`

SetType sets Type field to given value.


### GetUserAgent

`func (o *SessionItem) GetUserAgent() string`

GetUserAgent returns the UserAgent field if non-nil, zero value otherwise.

### GetUserAgentOk

`func (o *SessionItem) GetUserAgentOk() (*string, bool)`

GetUserAgentOk returns a tuple with the UserAgent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserAgent

`func (o *SessionItem) SetUserAgent(v string)`

SetUserAgent sets UserAgent field to given value.


### GetUserId

`func (o *SessionItem) GetUserId() int32`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *SessionItem) GetUserIdOk() (*int32, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *SessionItem) SetUserId(v int32)`

SetUserId sets UserId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


