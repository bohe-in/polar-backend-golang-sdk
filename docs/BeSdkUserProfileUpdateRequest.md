# BeSdkUserProfileUpdateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ClobberMatchingAttributes** | Pointer to **bool** |  | [optional] 
**Data** | **map[string]interface{}** |  | 
**UserID** | Pointer to **string** |  | [optional] 

## Methods

### NewBeSdkUserProfileUpdateRequest

`func NewBeSdkUserProfileUpdateRequest(data map[string]interface{}, ) *BeSdkUserProfileUpdateRequest`

NewBeSdkUserProfileUpdateRequest instantiates a new BeSdkUserProfileUpdateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBeSdkUserProfileUpdateRequestWithDefaults

`func NewBeSdkUserProfileUpdateRequestWithDefaults() *BeSdkUserProfileUpdateRequest`

NewBeSdkUserProfileUpdateRequestWithDefaults instantiates a new BeSdkUserProfileUpdateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetClobberMatchingAttributes

`func (o *BeSdkUserProfileUpdateRequest) GetClobberMatchingAttributes() bool`

GetClobberMatchingAttributes returns the ClobberMatchingAttributes field if non-nil, zero value otherwise.

### GetClobberMatchingAttributesOk

`func (o *BeSdkUserProfileUpdateRequest) GetClobberMatchingAttributesOk() (*bool, bool)`

GetClobberMatchingAttributesOk returns a tuple with the ClobberMatchingAttributes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClobberMatchingAttributes

`func (o *BeSdkUserProfileUpdateRequest) SetClobberMatchingAttributes(v bool)`

SetClobberMatchingAttributes sets ClobberMatchingAttributes field to given value.

### HasClobberMatchingAttributes

`func (o *BeSdkUserProfileUpdateRequest) HasClobberMatchingAttributes() bool`

HasClobberMatchingAttributes returns a boolean if a field has been set.

### GetData

`func (o *BeSdkUserProfileUpdateRequest) GetData() map[string]interface{}`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *BeSdkUserProfileUpdateRequest) GetDataOk() (*map[string]interface{}, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *BeSdkUserProfileUpdateRequest) SetData(v map[string]interface{})`

SetData sets Data field to given value.


### GetUserID

`func (o *BeSdkUserProfileUpdateRequest) GetUserID() string`

GetUserID returns the UserID field if non-nil, zero value otherwise.

### GetUserIDOk

`func (o *BeSdkUserProfileUpdateRequest) GetUserIDOk() (*string, bool)`

GetUserIDOk returns a tuple with the UserID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserID

`func (o *BeSdkUserProfileUpdateRequest) SetUserID(v string)`

SetUserID sets UserID field to given value.

### HasUserID

`func (o *BeSdkUserProfileUpdateRequest) HasUserID() bool`

HasUserID returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


