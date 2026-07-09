# CidrRule

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Settable** | Pointer to **bool** | settable permits the creator to override value. | [optional] 
**Value** | Pointer to **string** | value is the environment-supplied cidr_range. | [optional] 

## Methods

### NewCidrRule

`func NewCidrRule() *CidrRule`

NewCidrRule instantiates a new CidrRule object.
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed.

### GetSettable

`func (o *CidrRule) GetSettable() bool`

GetSettable returns the Settable field if non-nil, zero value otherwise.

### SetSettable

`func (o *CidrRule) SetSettable(v bool)`

SetSettable sets Settable field to given value.

### GetValue

`func (o *CidrRule) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### SetValue

`func (o *CidrRule) SetValue(v string)`

SetValue sets Value field to given value.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


