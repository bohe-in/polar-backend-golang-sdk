# \DefaultApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateLink**](DefaultApi.md#CreateLink) | **Post** /api/v1/links | 
[**RunEmailCampaign**](DefaultApi.md#RunEmailCampaign) | **Post** /api/v1/campaigns/email/run | 
[**RunPushCampaign**](DefaultApi.md#RunPushCampaign) | **Post** /api/v1/campaigns/push/run | 
[**UpdateUserProfile**](DefaultApi.md#UpdateUserProfile) | **Post** /api/v1/users/profile | 



## CreateLink

> ResponsesSdkLinkResponse CreateLink(ctx).XApiKey(xApiKey).XApiSecret(xApiSecret).BeSdkCreateLinkRequest(beSdkCreateLinkRequest).Execute()



### Example

```go
package main

import (
    "context"
    "fmt"
    "os"
    openapiclient "github.com/bohe-in/polar-backend-golang-sdk"
)

func main() {
    xApiKey := "xApiKey_example" // string | 
    xApiSecret := "xApiSecret_example" // string | 
    beSdkCreateLinkRequest := *openapiclient.NewBeSdkCreateLinkRequest("Name_example") // BeSdkCreateLinkRequest | 

    configuration := openapiclient.NewConfiguration()
    apiClient := openapiclient.NewAPIClient(configuration)
    resp, r, err := apiClient.DefaultApi.CreateLink(context.Background()).XApiKey(xApiKey).XApiSecret(xApiSecret).BeSdkCreateLinkRequest(beSdkCreateLinkRequest).Execute()
    if err != nil {
        fmt.Fprintf(os.Stderr, "Error when calling `DefaultApi.CreateLink``: %v\n", err)
        fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
    }
    // response from `CreateLink`: ResponsesSdkLinkResponse
    fmt.Fprintf(os.Stdout, "Response from `DefaultApi.CreateLink`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateLinkRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xApiKey** | **string** |  | 
 **xApiSecret** | **string** |  | 
 **beSdkCreateLinkRequest** | [**BeSdkCreateLinkRequest**](BeSdkCreateLinkRequest.md) |  | 

### Return type

[**ResponsesSdkLinkResponse**](ResponsesSdkLinkResponse.md)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RunEmailCampaign

> ResponsesSuccessResponse RunEmailCampaign(ctx).XApiKey(xApiKey).XApiSecret(xApiSecret).BeSdkRunEmailCampaignRequest(beSdkRunEmailCampaignRequest).Execute()



### Example

```go
package main

import (
    "context"
    "fmt"
    "os"
    openapiclient "github.com/bohe-in/polar-backend-golang-sdk"
)

func main() {
    xApiKey := "xApiKey_example" // string | 
    xApiSecret := "xApiSecret_example" // string | 
    beSdkRunEmailCampaignRequest := *openapiclient.NewBeSdkRunEmailCampaignRequest("CampaignUnid_example", "UserUnid_example") // BeSdkRunEmailCampaignRequest | 

    configuration := openapiclient.NewConfiguration()
    apiClient := openapiclient.NewAPIClient(configuration)
    resp, r, err := apiClient.DefaultApi.RunEmailCampaign(context.Background()).XApiKey(xApiKey).XApiSecret(xApiSecret).BeSdkRunEmailCampaignRequest(beSdkRunEmailCampaignRequest).Execute()
    if err != nil {
        fmt.Fprintf(os.Stderr, "Error when calling `DefaultApi.RunEmailCampaign``: %v\n", err)
        fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
    }
    // response from `RunEmailCampaign`: ResponsesSuccessResponse
    fmt.Fprintf(os.Stdout, "Response from `DefaultApi.RunEmailCampaign`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRunEmailCampaignRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xApiKey** | **string** |  | 
 **xApiSecret** | **string** |  | 
 **beSdkRunEmailCampaignRequest** | [**BeSdkRunEmailCampaignRequest**](BeSdkRunEmailCampaignRequest.md) |  | 

### Return type

[**ResponsesSuccessResponse**](ResponsesSuccessResponse.md)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RunPushCampaign

> ResponsesSuccessResponse RunPushCampaign(ctx).XApiKey(xApiKey).XApiSecret(xApiSecret).BeSdkRunPushCampaignRequest(beSdkRunPushCampaignRequest).Execute()



### Example

```go
package main

import (
    "context"
    "fmt"
    "os"
    openapiclient "github.com/bohe-in/polar-backend-golang-sdk"
)

func main() {
    xApiKey := "xApiKey_example" // string | 
    xApiSecret := "xApiSecret_example" // string | 
    beSdkRunPushCampaignRequest := *openapiclient.NewBeSdkRunPushCampaignRequest("CampaignUnid_example", "UserUnid_example") // BeSdkRunPushCampaignRequest | 

    configuration := openapiclient.NewConfiguration()
    apiClient := openapiclient.NewAPIClient(configuration)
    resp, r, err := apiClient.DefaultApi.RunPushCampaign(context.Background()).XApiKey(xApiKey).XApiSecret(xApiSecret).BeSdkRunPushCampaignRequest(beSdkRunPushCampaignRequest).Execute()
    if err != nil {
        fmt.Fprintf(os.Stderr, "Error when calling `DefaultApi.RunPushCampaign``: %v\n", err)
        fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
    }
    // response from `RunPushCampaign`: ResponsesSuccessResponse
    fmt.Fprintf(os.Stdout, "Response from `DefaultApi.RunPushCampaign`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRunPushCampaignRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xApiKey** | **string** |  | 
 **xApiSecret** | **string** |  | 
 **beSdkRunPushCampaignRequest** | [**BeSdkRunPushCampaignRequest**](BeSdkRunPushCampaignRequest.md) |  | 

### Return type

[**ResponsesSuccessResponse**](ResponsesSuccessResponse.md)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateUserProfile

> ResponsesSuccessResponse UpdateUserProfile(ctx).XApiKey(xApiKey).XApiSecret(xApiSecret).BeSdkUserProfileUpdateRequest(beSdkUserProfileUpdateRequest).Execute()



### Example

```go
package main

import (
    "context"
    "fmt"
    "os"
    openapiclient "github.com/bohe-in/polar-backend-golang-sdk"
)

func main() {
    xApiKey := "xApiKey_example" // string | 
    xApiSecret := "xApiSecret_example" // string | 
    beSdkUserProfileUpdateRequest := *openapiclient.NewBeSdkUserProfileUpdateRequest(map[string]interface{}{"key": interface{}(123)}) // BeSdkUserProfileUpdateRequest | 

    configuration := openapiclient.NewConfiguration()
    apiClient := openapiclient.NewAPIClient(configuration)
    resp, r, err := apiClient.DefaultApi.UpdateUserProfile(context.Background()).XApiKey(xApiKey).XApiSecret(xApiSecret).BeSdkUserProfileUpdateRequest(beSdkUserProfileUpdateRequest).Execute()
    if err != nil {
        fmt.Fprintf(os.Stderr, "Error when calling `DefaultApi.UpdateUserProfile``: %v\n", err)
        fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
    }
    // response from `UpdateUserProfile`: ResponsesSuccessResponse
    fmt.Fprintf(os.Stdout, "Response from `DefaultApi.UpdateUserProfile`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUpdateUserProfileRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xApiKey** | **string** |  | 
 **xApiSecret** | **string** |  | 
 **beSdkUserProfileUpdateRequest** | [**BeSdkUserProfileUpdateRequest**](BeSdkUserProfileUpdateRequest.md) |  | 

### Return type

[**ResponsesSuccessResponse**](ResponsesSuccessResponse.md)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

