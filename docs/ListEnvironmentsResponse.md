# ListEnvironmentsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Environments** | [**[]Environment**](Environment.md) | environments are the organization&#39;s environments, sorted by name. | 
**Pagination** | Pointer to [**KeysetPaginationResponse**](KeysetPaginationResponse.md) |  | [optional] 

## Methods

### NewListEnvironmentsResponse

`func NewListEnvironmentsResponse(environments []Environment, ) *ListEnvironmentsResponse`

NewListEnvironmentsResponse instantiates a new ListEnvironmentsResponse object.
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed.

### NewListEnvironmentsResponseWithDefaults

`func NewListEnvironmentsResponseWithDefaults() *ListEnvironmentsResponse`

NewListEnvironmentsResponseWithDefaults instantiates a new ListEnvironmentsResponse object.
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set.

### GetEnvironments

`func (o *ListEnvironmentsResponse) GetEnvironments() []Environment`

GetEnvironments returns the Environments field if non-nil, zero value otherwise.

### SetEnvironments

`func (o *ListEnvironmentsResponse) SetEnvironments(v []Environment)`

SetEnvironments sets Environments field to given value.

### GetPagination

`func (o *ListEnvironmentsResponse) GetPagination() KeysetPaginationResponse`

GetPagination returns the Pagination field if non-nil, zero value otherwise.

### SetPagination

`func (o *ListEnvironmentsResponse) SetPagination(v KeysetPaginationResponse)`

SetPagination sets Pagination field to given value.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


