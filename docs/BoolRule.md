# BoolRule

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Allowed** | Pointer to **[]bool** | allowed lists the permitted values (at most two). | [optional] 
**Default** | Pointer to **bool** | default is preselected when the question is asked. | [optional] 

## Methods

### NewBoolRule

`func NewBoolRule() *BoolRule`

NewBoolRule instantiates a new BoolRule object.
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed.

### GetAllowed

`func (o *BoolRule) GetAllowed() []bool`

GetAllowed returns the Allowed field if non-nil, zero value otherwise.

### SetAllowed

`func (o *BoolRule) SetAllowed(v []bool)`

SetAllowed sets Allowed field to given value.

### GetDefault

`func (o *BoolRule) GetDefault() bool`

GetDefault returns the Default field if non-nil, zero value otherwise.

### SetDefault

`func (o *BoolRule) SetDefault(v bool)`

SetDefault sets Default field to given value.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


