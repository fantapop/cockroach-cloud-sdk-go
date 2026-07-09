# CreateEnvironmentRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | Pointer to **string** | description should say when to use this environment. | [optional] 
**Name** | **string** | name is unique within the organization. | 
**Rules** | [**EnvironmentRules**](EnvironmentRules.md) |  | 

## Methods

### NewCreateEnvironmentRequest

`func NewCreateEnvironmentRequest(name string, rules EnvironmentRules, ) *CreateEnvironmentRequest`

NewCreateEnvironmentRequest instantiates a new CreateEnvironmentRequest object.
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed.

### NewCreateEnvironmentRequestWithDefaults

`func NewCreateEnvironmentRequestWithDefaults() *CreateEnvironmentRequest`

NewCreateEnvironmentRequestWithDefaults instantiates a new CreateEnvironmentRequest object.
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set.

### GetDescription

`func (o *CreateEnvironmentRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### SetDescription

`func (o *CreateEnvironmentRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### GetName

`func (o *CreateEnvironmentRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### SetName

`func (o *CreateEnvironmentRequest) SetName(v string)`

SetName sets Name field to given value.

### GetRules

`func (o *CreateEnvironmentRequest) GetRules() EnvironmentRules`

GetRules returns the Rules field if non-nil, zero value otherwise.

### SetRules

`func (o *CreateEnvironmentRequest) SetRules(v EnvironmentRules)`

SetRules sets Rules field to given value.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


