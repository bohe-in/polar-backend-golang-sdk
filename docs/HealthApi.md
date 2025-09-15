# \HealthApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**Health**](HealthApi.md#Health) | **Get** /api/v1/health/ | 
[**HealthOptions**](HealthApi.md#HealthOptions) | **Options** /api/v1/health/ | 



## Health

> ResponsesSuccessResponse Health(ctx).Execute()



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

    configuration := openapiclient.NewConfiguration()
    apiClient := openapiclient.NewAPIClient(configuration)
    resp, r, err := apiClient.HealthApi.Health(context.Background()).Execute()
    if err != nil {
        fmt.Fprintf(os.Stderr, "Error when calling `HealthApi.Health``: %v\n", err)
        fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
    }
    // response from `Health`: ResponsesSuccessResponse
    fmt.Fprintf(os.Stdout, "Response from `HealthApi.Health`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiHealthRequest struct via the builder pattern


### Return type

[**ResponsesSuccessResponse**](ResponsesSuccessResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## HealthOptions

> ResponsesSuccessResponse HealthOptions(ctx).Execute()



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

    configuration := openapiclient.NewConfiguration()
    apiClient := openapiclient.NewAPIClient(configuration)
    resp, r, err := apiClient.HealthApi.HealthOptions(context.Background()).Execute()
    if err != nil {
        fmt.Fprintf(os.Stderr, "Error when calling `HealthApi.HealthOptions``: %v\n", err)
        fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
    }
    // response from `HealthOptions`: ResponsesSuccessResponse
    fmt.Fprintf(os.Stdout, "Response from `HealthApi.HealthOptions`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiHealthOptionsRequest struct via the builder pattern


### Return type

[**ResponsesSuccessResponse**](ResponsesSuccessResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

