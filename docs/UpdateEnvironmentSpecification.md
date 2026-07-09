# UpdateEnvironmentSpecification

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | Pointer to **string** | description replaces the environment&#39;s description when set. | [optional] 
**Name** | Pointer to **string** | name replaces the environment&#39;s name when set. | [optional] 
**Rules** | Pointer to [**EnvironmentRules**](EnvironmentRules.md) |  | [optional] 

## Methods

### NewUpdateEnvironmentSpecification

`func NewUpdateEnvironmentSpecification() *UpdateEnvironmentSpecification`

NewUpdateEnvironmentSpecification instantiates a new UpdateEnvironmentSpecification object.
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed.

### GetDescription

`func (o *UpdateEnvironmentSpecification) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### SetDescription

`func (o *UpdateEnvironmentSpecification) SetDescription(v string)`

SetDescription sets Description field to given value.

### GetName

`func (o *UpdateEnvironmentSpecification) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### SetName

`func (o *UpdateEnvironmentSpecification) SetName(v string)`

SetName sets Name field to given value.

### GetRules

`func (o *UpdateEnvironmentSpecification) GetRules() EnvironmentRules`

GetRules returns the Rules field if non-nil, zero value otherwise.

### SetRules

`func (o *UpdateEnvironmentSpecification) SetRules(v EnvironmentRules)`

SetRules sets Rules field to given value.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


