# Environments

All URIs are relative to *https://cockroachlabs.cloud*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateClusterInEnvironment**](EnvironmentsApi.md#CreateClusterInEnvironment) | **Post** /api/v1/environments/{environment_id}/clusters | Create a cluster in an environment, answering the questions posed by the environment&#39;s creation_spec
[**CreateEnvironment**](EnvironmentsApi.md#CreateEnvironment) | **Post** /api/v1/environments | Create an environment
[**DeleteEnvironment**](EnvironmentsApi.md#DeleteEnvironment) | **Delete** /api/v1/environments/{environment_id} | Delete an environment
[**GetEnvironment**](EnvironmentsApi.md#GetEnvironment) | **Get** /api/v1/environments/{environment_id} | Get an environment by ID
[**ListEnvironments**](EnvironmentsApi.md#ListEnvironments) | **Get** /api/v1/environments | List the environments in the organization
[**UpdateClusterInEnvironment**](EnvironmentsApi.md#UpdateClusterInEnvironment) | **Patch** /api/v1/environments/{environment_id}/clusters/{cluster_id} | Update a cluster that belongs to an environment, within the bounds of the environment&#39;s update_spec
[**UpdateEnvironment**](EnvironmentsApi.md#UpdateEnvironment) | **Patch** /api/v1/environments/{environment_id} | Update an environment



## CreateClusterInEnvironment

> Cluster CreateClusterInEnvironment(ctx, environmentId).CreateClusterInEnvironmentBody(createClusterInEnvironmentBody).Execute()

Create a cluster in an environment, answering the questions posed by the environment's creation_spec

Can be used by the following roles assigned at the organization scope:
- CLUSTER_ADMIN
- CLUSTER_CREATOR


### Example

```go
package main

import (
    "context"
    "fmt"
    "os"
    openapiclient "./openapi"
)

func main() {
    environmentId := "environmentId_example" // string | environment_id identifies the environment to create in.
    createClusterInEnvironmentBody := *openapiclient.NewCreateClusterInEnvironmentBody("Name_example") // CreateClusterInEnvironmentBody | 

    configuration := openapiclient.NewConfiguration()
    api_client := openapiclient.NewClient(configuration)
    resp, r, err := api_client.EnvironmentsApi.CreateClusterInEnvironment(context.Background(), environmentId).CreateClusterInEnvironmentBody(createClusterInEnvironmentBody).Execute()
    if err != nil {
        fmt.Fprintf(os.Stderr, "Error when calling `EnvironmentsApi.CreateClusterInEnvironment``: %v\n", err)
        fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
    }
    // response from `CreateClusterInEnvironment`: Cluster
    fmt.Fprintf(os.Stdout, "Response from `EnvironmentsApi.CreateClusterInEnvironment`: %v\n", resp)
}
```

### Path Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**environmentId** | **string** | environment_id identifies the environment to create in. | 

### Other Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createClusterInEnvironmentBody** | [**CreateClusterInEnvironmentBody**](CreateClusterInEnvironmentBody.md) |  | 

### Return type

[**Cluster**](Cluster.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to README]](../README.md)


## CreateEnvironment

> Environment CreateEnvironment(ctx).CreateEnvironmentRequest(createEnvironmentRequest).Execute()

Create an environment

Can be used by the following roles assigned at the organization scope:
- ORG_ADMIN


### Example

```go
package main

import (
    "context"
    "fmt"
    "os"
    openapiclient "./openapi"
)

func main() {
    createEnvironmentRequest := *openapiclient.NewCreateEnvironmentRequest("Name_example", *openapiclient.NewEnvironmentRules()) // CreateEnvironmentRequest | 

    configuration := openapiclient.NewConfiguration()
    api_client := openapiclient.NewClient(configuration)
    resp, r, err := api_client.EnvironmentsApi.CreateEnvironment(context.Background()).CreateEnvironmentRequest(createEnvironmentRequest).Execute()
    if err != nil {
        fmt.Fprintf(os.Stderr, "Error when calling `EnvironmentsApi.CreateEnvironment``: %v\n", err)
        fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
    }
    // response from `CreateEnvironment`: Environment
    fmt.Fprintf(os.Stdout, "Response from `EnvironmentsApi.CreateEnvironment`: %v\n", resp)
}
```

### Path Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.

### Other Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createEnvironmentRequest** | [**CreateEnvironmentRequest**](CreateEnvironmentRequest.md) |  | 

### Return type

[**Environment**](Environment.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to README]](../README.md)


## DeleteEnvironment

> Environment DeleteEnvironment(ctx, environmentId).Execute()

Delete an environment

Can be used by the following roles assigned at the organization scope:
- ORG_ADMIN


### Example

```go
package main

import (
    "context"
    "fmt"
    "os"
    openapiclient "./openapi"
)

func main() {
    environmentId := "environmentId_example" // string | environment_id identifies the environment.

    configuration := openapiclient.NewConfiguration()
    api_client := openapiclient.NewClient(configuration)
    resp, r, err := api_client.EnvironmentsApi.DeleteEnvironment(context.Background(), environmentId).Execute()
    if err != nil {
        fmt.Fprintf(os.Stderr, "Error when calling `EnvironmentsApi.DeleteEnvironment``: %v\n", err)
        fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
    }
    // response from `DeleteEnvironment`: Environment
    fmt.Fprintf(os.Stdout, "Response from `EnvironmentsApi.DeleteEnvironment`: %v\n", resp)
}
```

### Path Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**environmentId** | **string** | environment_id identifies the environment. | 

### Other Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Environment**](Environment.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to README]](../README.md)


## GetEnvironment

> Environment GetEnvironment(ctx, environmentId).Execute()

Get an environment by ID

Can be used by the following roles assigned at the organization scope:
- ORG_ADMIN
- CLUSTER_ADMIN
- CLUSTER_CREATOR


### Example

```go
package main

import (
    "context"
    "fmt"
    "os"
    openapiclient "./openapi"
)

func main() {
    environmentId := "environmentId_example" // string | environment_id identifies the environment.

    configuration := openapiclient.NewConfiguration()
    api_client := openapiclient.NewClient(configuration)
    resp, r, err := api_client.EnvironmentsApi.GetEnvironment(context.Background(), environmentId).Execute()
    if err != nil {
        fmt.Fprintf(os.Stderr, "Error when calling `EnvironmentsApi.GetEnvironment``: %v\n", err)
        fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
    }
    // response from `GetEnvironment`: Environment
    fmt.Fprintf(os.Stdout, "Response from `EnvironmentsApi.GetEnvironment`: %v\n", resp)
}
```

### Path Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**environmentId** | **string** | environment_id identifies the environment. | 

### Other Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Environment**](Environment.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to README]](../README.md)


## ListEnvironments

> ListEnvironmentsResponse ListEnvironments(ctx).PaginationPage(paginationPage).PaginationLimit(paginationLimit).PaginationAsOfTime(paginationAsOfTime).PaginationSortOrder(paginationSortOrder).Execute()

List the environments in the organization

Can be used by the following roles assigned at the organization scope:
- ORG_ADMIN
- CLUSTER_ADMIN
- CLUSTER_CREATOR


### Example

```go
package main

import (
    "context"
    "fmt"
    "os"
    "time"
    openapiclient "./openapi"
)

func main() {
    paginationPage := "paginationPage_example" // string |  (optional)
    paginationLimit := int32(56) // int32 |  (optional)
    paginationAsOfTime := time.Now() // time.Time |  (optional)
    paginationSortOrder := "paginationSortOrder_example" // string |  - ASC: Sort in ascending order. This is the default unless otherwise specified.  - DESC: Sort in descending order. (optional)

    configuration := openapiclient.NewConfiguration()
    api_client := openapiclient.NewClient(configuration)
    resp, r, err := api_client.EnvironmentsApi.ListEnvironments(context.Background()).PaginationPage(paginationPage).PaginationLimit(paginationLimit).PaginationAsOfTime(paginationAsOfTime).PaginationSortOrder(paginationSortOrder).Execute()
    if err != nil {
        fmt.Fprintf(os.Stderr, "Error when calling `EnvironmentsApi.ListEnvironments``: %v\n", err)
        fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
    }
    // response from `ListEnvironments`: ListEnvironmentsResponse
    fmt.Fprintf(os.Stdout, "Response from `EnvironmentsApi.ListEnvironments`: %v\n", resp)
}
```

### Path Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.

### Other Parameters

Optional parameters can be passed through a pointer to the ListEnvironmentsOptions struct.

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **paginationPage** | **string** |  | 
 **paginationLimit** | **int32** |  | 
 **paginationAsOfTime** | **time.Time** |  | 
 **paginationSortOrder** | **string** |  - ASC: Sort in ascending order. This is the default unless otherwise specified.  - DESC: Sort in descending order. | 

### Return type

[**ListEnvironmentsResponse**](ListEnvironmentsResponse.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to README]](../README.md)


## UpdateClusterInEnvironment

> Cluster UpdateClusterInEnvironment(ctx, environmentId, clusterId).UpdateClusterInEnvironmentBody(updateClusterInEnvironmentBody).Execute()

Update a cluster that belongs to an environment, within the bounds of the environment's update_spec

Can be used by the following roles assigned at the organization scope:
- CLUSTER_ADMIN


### Example

```go
package main

import (
    "context"
    "fmt"
    "os"
    openapiclient "./openapi"
)

func main() {
    environmentId := "environmentId_example" // string | environment_id identifies the environment; the cluster must belong to it.
    clusterId := "clusterId_example" // string | cluster_id identifies the cluster to update.
    updateClusterInEnvironmentBody := *openapiclient.NewUpdateClusterInEnvironmentBody() // UpdateClusterInEnvironmentBody | 

    configuration := openapiclient.NewConfiguration()
    api_client := openapiclient.NewClient(configuration)
    resp, r, err := api_client.EnvironmentsApi.UpdateClusterInEnvironment(context.Background(), environmentId, clusterId).UpdateClusterInEnvironmentBody(updateClusterInEnvironmentBody).Execute()
    if err != nil {
        fmt.Fprintf(os.Stderr, "Error when calling `EnvironmentsApi.UpdateClusterInEnvironment``: %v\n", err)
        fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
    }
    // response from `UpdateClusterInEnvironment`: Cluster
    fmt.Fprintf(os.Stdout, "Response from `EnvironmentsApi.UpdateClusterInEnvironment`: %v\n", resp)
}
```

### Path Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**environmentId** | **string** | environment_id identifies the environment; the cluster must belong to it. | 
**clusterId** | **string** | cluster_id identifies the cluster to update. | 

### Other Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updateClusterInEnvironmentBody** | [**UpdateClusterInEnvironmentBody**](UpdateClusterInEnvironmentBody.md) |  | 

### Return type

[**Cluster**](Cluster.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to README]](../README.md)


## UpdateEnvironment

> Environment UpdateEnvironment(ctx, environmentId).UpdateEnvironmentSpecification(updateEnvironmentSpecification).Execute()

Update an environment

Can be used by the following roles assigned at the organization scope:
- ORG_ADMIN


### Example

```go
package main

import (
    "context"
    "fmt"
    "os"
    openapiclient "./openapi"
)

func main() {
    environmentId := "environmentId_example" // string | environment_id identifies the environment.
    updateEnvironmentSpecification := *openapiclient.NewUpdateEnvironmentSpecification() // UpdateEnvironmentSpecification | spec carries the fields to update.

    configuration := openapiclient.NewConfiguration()
    api_client := openapiclient.NewClient(configuration)
    resp, r, err := api_client.EnvironmentsApi.UpdateEnvironment(context.Background(), environmentId).UpdateEnvironmentSpecification(updateEnvironmentSpecification).Execute()
    if err != nil {
        fmt.Fprintf(os.Stderr, "Error when calling `EnvironmentsApi.UpdateEnvironment``: %v\n", err)
        fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
    }
    // response from `UpdateEnvironment`: Environment
    fmt.Fprintf(os.Stdout, "Response from `EnvironmentsApi.UpdateEnvironment`: %v\n", resp)
}
```

### Path Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**environmentId** | **string** | environment_id identifies the environment. | 

### Other Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateEnvironmentSpecification** | [**UpdateEnvironmentSpecification**](UpdateEnvironmentSpecification.md) | spec carries the fields to update. | 

### Return type

[**Environment**](Environment.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to README]](../README.md)

