# StatsResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EventsByCategory** | **map[string]int32** |  | 
**EventsBySeverity** | **map[string]int32** |  | 
**EventsLast24Hours** | **int32** |  | 
**EventsLast7Days** | **int32** |  | 
**FailedEvents** | **int32** |  | 
**RecentEventTypes** | [**[]EventTypeCount**](EventTypeCount.md) |  | 
**TotalEvents** | **int32** |  | 

## Methods

### NewStatsResponseData

`func NewStatsResponseData(eventsByCategory map[string]int32, eventsBySeverity map[string]int32, eventsLast24Hours int32, eventsLast7Days int32, failedEvents int32, recentEventTypes []EventTypeCount, totalEvents int32, ) *StatsResponseData`

NewStatsResponseData instantiates a new StatsResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStatsResponseDataWithDefaults

`func NewStatsResponseDataWithDefaults() *StatsResponseData`

NewStatsResponseDataWithDefaults instantiates a new StatsResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEventsByCategory

`func (o *StatsResponseData) GetEventsByCategory() map[string]int32`

GetEventsByCategory returns the EventsByCategory field if non-nil, zero value otherwise.

### GetEventsByCategoryOk

`func (o *StatsResponseData) GetEventsByCategoryOk() (*map[string]int32, bool)`

GetEventsByCategoryOk returns a tuple with the EventsByCategory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventsByCategory

`func (o *StatsResponseData) SetEventsByCategory(v map[string]int32)`

SetEventsByCategory sets EventsByCategory field to given value.


### GetEventsBySeverity

`func (o *StatsResponseData) GetEventsBySeverity() map[string]int32`

GetEventsBySeverity returns the EventsBySeverity field if non-nil, zero value otherwise.

### GetEventsBySeverityOk

`func (o *StatsResponseData) GetEventsBySeverityOk() (*map[string]int32, bool)`

GetEventsBySeverityOk returns a tuple with the EventsBySeverity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventsBySeverity

`func (o *StatsResponseData) SetEventsBySeverity(v map[string]int32)`

SetEventsBySeverity sets EventsBySeverity field to given value.


### GetEventsLast24Hours

`func (o *StatsResponseData) GetEventsLast24Hours() int32`

GetEventsLast24Hours returns the EventsLast24Hours field if non-nil, zero value otherwise.

### GetEventsLast24HoursOk

`func (o *StatsResponseData) GetEventsLast24HoursOk() (*int32, bool)`

GetEventsLast24HoursOk returns a tuple with the EventsLast24Hours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventsLast24Hours

`func (o *StatsResponseData) SetEventsLast24Hours(v int32)`

SetEventsLast24Hours sets EventsLast24Hours field to given value.


### GetEventsLast7Days

`func (o *StatsResponseData) GetEventsLast7Days() int32`

GetEventsLast7Days returns the EventsLast7Days field if non-nil, zero value otherwise.

### GetEventsLast7DaysOk

`func (o *StatsResponseData) GetEventsLast7DaysOk() (*int32, bool)`

GetEventsLast7DaysOk returns a tuple with the EventsLast7Days field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventsLast7Days

`func (o *StatsResponseData) SetEventsLast7Days(v int32)`

SetEventsLast7Days sets EventsLast7Days field to given value.


### GetFailedEvents

`func (o *StatsResponseData) GetFailedEvents() int32`

GetFailedEvents returns the FailedEvents field if non-nil, zero value otherwise.

### GetFailedEventsOk

`func (o *StatsResponseData) GetFailedEventsOk() (*int32, bool)`

GetFailedEventsOk returns a tuple with the FailedEvents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailedEvents

`func (o *StatsResponseData) SetFailedEvents(v int32)`

SetFailedEvents sets FailedEvents field to given value.


### GetRecentEventTypes

`func (o *StatsResponseData) GetRecentEventTypes() []EventTypeCount`

GetRecentEventTypes returns the RecentEventTypes field if non-nil, zero value otherwise.

### GetRecentEventTypesOk

`func (o *StatsResponseData) GetRecentEventTypesOk() (*[]EventTypeCount, bool)`

GetRecentEventTypesOk returns a tuple with the RecentEventTypes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecentEventTypes

`func (o *StatsResponseData) SetRecentEventTypes(v []EventTypeCount)`

SetRecentEventTypes sets RecentEventTypes field to given value.


### GetTotalEvents

`func (o *StatsResponseData) GetTotalEvents() int32`

GetTotalEvents returns the TotalEvents field if non-nil, zero value otherwise.

### GetTotalEventsOk

`func (o *StatsResponseData) GetTotalEventsOk() (*int32, bool)`

GetTotalEventsOk returns a tuple with the TotalEvents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalEvents

`func (o *StatsResponseData) SetTotalEvents(v int32)`

SetTotalEvents sets TotalEvents field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


