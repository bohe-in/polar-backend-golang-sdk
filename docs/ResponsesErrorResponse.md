# ResponsesErrorResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | Pointer to [**ResponsesErrorDetails**](ResponsesErrorDetails.md) |  | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 
**Version** | Pointer to **string** |  | [optional] 

## Methods

### NewResponsesErrorResponse

`func NewResponsesErrorResponse() *ResponsesErrorResponse`

NewResponsesErrorResponse instantiates a new ResponsesErrorResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResponsesErrorResponseWithDefaults

`func NewResponsesErrorResponseWithDefaults() *ResponsesErrorResponse`

NewResponsesErrorResponseWithDefaults instantiates a new ResponsesErrorResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *ResponsesErrorResponse) GetError() ResponsesErrorDetails`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ResponsesErrorResponse) GetErrorOk() (*ResponsesErrorDetails, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ResponsesErrorResponse) SetError(v ResponsesErrorDetails)`

SetError sets Error field to given value.

### HasError

`func (o *ResponsesErrorResponse) HasError() bool`

HasError returns a boolean if a field has been set.

### GetRequestId

`func (o *ResponsesErrorResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *ResponsesErrorResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *ResponsesErrorResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *ResponsesErrorResponse) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.

### GetVersion

`func (o *ResponsesErrorResponse) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *ResponsesErrorResponse) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *ResponsesErrorResponse) SetVersion(v string)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *ResponsesErrorResponse) HasVersion() bool`

HasVersion returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


