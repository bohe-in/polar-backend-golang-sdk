# \DefaultApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateLink**](DefaultApi.md#CreateLink) | **Post** /api/v1/links | 



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

