# BeSdkRunEmailCampaignRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CampaignUnid** | **string** |  | 
**CustomData** | Pointer to **map[string]interface{}** |  | [optional] 
**UserUnid** | **string** |  | 

## Methods

### NewBeSdkRunEmailCampaignRequest

`func NewBeSdkRunEmailCampaignRequest(campaignUnid string, userUnid string, ) *BeSdkRunEmailCampaignRequest`

NewBeSdkRunEmailCampaignRequest instantiates a new BeSdkRunEmailCampaignRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBeSdkRunEmailCampaignRequestWithDefaults

`func NewBeSdkRunEmailCampaignRequestWithDefaults() *BeSdkRunEmailCampaignRequest`

NewBeSdkRunEmailCampaignRequestWithDefaults instantiates a new BeSdkRunEmailCampaignRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCampaignUnid

`func (o *BeSdkRunEmailCampaignRequest) GetCampaignUnid() string`

GetCampaignUnid returns the CampaignUnid field if non-nil, zero value otherwise.

### GetCampaignUnidOk

`func (o *BeSdkRunEmailCampaignRequest) GetCampaignUnidOk() (*string, bool)`

GetCampaignUnidOk returns a tuple with the CampaignUnid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCampaignUnid

`func (o *BeSdkRunEmailCampaignRequest) SetCampaignUnid(v string)`

SetCampaignUnid sets CampaignUnid field to given value.


### GetCustomData

`func (o *BeSdkRunEmailCampaignRequest) GetCustomData() map[string]interface{}`

GetCustomData returns the CustomData field if non-nil, zero value otherwise.

### GetCustomDataOk

`func (o *BeSdkRunEmailCampaignRequest) GetCustomDataOk() (*map[string]interface{}, bool)`

GetCustomDataOk returns a tuple with the CustomData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomData

`func (o *BeSdkRunEmailCampaignRequest) SetCustomData(v map[string]interface{})`

SetCustomData sets CustomData field to given value.

### HasCustomData

`func (o *BeSdkRunEmailCampaignRequest) HasCustomData() bool`

HasCustomData returns a boolean if a field has been set.

### GetUserUnid

`func (o *BeSdkRunEmailCampaignRequest) GetUserUnid() string`

GetUserUnid returns the UserUnid field if non-nil, zero value otherwise.

### GetUserUnidOk

`func (o *BeSdkRunEmailCampaignRequest) GetUserUnidOk() (*string, bool)`

GetUserUnidOk returns a tuple with the UserUnid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserUnid

`func (o *BeSdkRunEmailCampaignRequest) SetUserUnid(v string)`

SetUserUnid sets UserUnid field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


