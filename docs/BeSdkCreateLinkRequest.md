# BeSdkCreateLinkRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AnalyticsTags** | Pointer to [**RequestsLinkAnalyticTags**](RequestsLinkAnalyticTags.md) |  | [optional] 
**Data** | Pointer to **map[string]interface{}** |  | [optional] 
**Name** | **string** |  | 
**Redirects** | Pointer to [**RequestsLinkRedirects**](RequestsLinkRedirects.md) |  | [optional] 
**SocialMediaTags** | Pointer to [**RequestsLinkSocialMediaTags**](RequestsLinkSocialMediaTags.md) |  | [optional] 

## Methods

### NewBeSdkCreateLinkRequest

`func NewBeSdkCreateLinkRequest(name string, ) *BeSdkCreateLinkRequest`

NewBeSdkCreateLinkRequest instantiates a new BeSdkCreateLinkRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBeSdkCreateLinkRequestWithDefaults

`func NewBeSdkCreateLinkRequestWithDefaults() *BeSdkCreateLinkRequest`

NewBeSdkCreateLinkRequestWithDefaults instantiates a new BeSdkCreateLinkRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAnalyticsTags

`func (o *BeSdkCreateLinkRequest) GetAnalyticsTags() RequestsLinkAnalyticTags`

GetAnalyticsTags returns the AnalyticsTags field if non-nil, zero value otherwise.

### GetAnalyticsTagsOk

`func (o *BeSdkCreateLinkRequest) GetAnalyticsTagsOk() (*RequestsLinkAnalyticTags, bool)`

GetAnalyticsTagsOk returns a tuple with the AnalyticsTags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnalyticsTags

`func (o *BeSdkCreateLinkRequest) SetAnalyticsTags(v RequestsLinkAnalyticTags)`

SetAnalyticsTags sets AnalyticsTags field to given value.

### HasAnalyticsTags

`func (o *BeSdkCreateLinkRequest) HasAnalyticsTags() bool`

HasAnalyticsTags returns a boolean if a field has been set.

### GetData

`func (o *BeSdkCreateLinkRequest) GetData() map[string]interface{}`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *BeSdkCreateLinkRequest) GetDataOk() (*map[string]interface{}, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *BeSdkCreateLinkRequest) SetData(v map[string]interface{})`

SetData sets Data field to given value.

### HasData

`func (o *BeSdkCreateLinkRequest) HasData() bool`

HasData returns a boolean if a field has been set.

### GetName

`func (o *BeSdkCreateLinkRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *BeSdkCreateLinkRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *BeSdkCreateLinkRequest) SetName(v string)`

SetName sets Name field to given value.


### GetRedirects

`func (o *BeSdkCreateLinkRequest) GetRedirects() RequestsLinkRedirects`

GetRedirects returns the Redirects field if non-nil, zero value otherwise.

### GetRedirectsOk

`func (o *BeSdkCreateLinkRequest) GetRedirectsOk() (*RequestsLinkRedirects, bool)`

GetRedirectsOk returns a tuple with the Redirects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRedirects

`func (o *BeSdkCreateLinkRequest) SetRedirects(v RequestsLinkRedirects)`

SetRedirects sets Redirects field to given value.

### HasRedirects

`func (o *BeSdkCreateLinkRequest) HasRedirects() bool`

HasRedirects returns a boolean if a field has been set.

### GetSocialMediaTags

`func (o *BeSdkCreateLinkRequest) GetSocialMediaTags() RequestsLinkSocialMediaTags`

GetSocialMediaTags returns the SocialMediaTags field if non-nil, zero value otherwise.

### GetSocialMediaTagsOk

`func (o *BeSdkCreateLinkRequest) GetSocialMediaTagsOk() (*RequestsLinkSocialMediaTags, bool)`

GetSocialMediaTagsOk returns a tuple with the SocialMediaTags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSocialMediaTags

`func (o *BeSdkCreateLinkRequest) SetSocialMediaTags(v RequestsLinkSocialMediaTags)`

SetSocialMediaTags sets SocialMediaTags field to given value.

### HasSocialMediaTags

`func (o *BeSdkCreateLinkRequest) HasSocialMediaTags() bool`

HasSocialMediaTags returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


