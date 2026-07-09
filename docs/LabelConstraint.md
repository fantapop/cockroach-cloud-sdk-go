# LabelConstraint

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Key** | Pointer to **string** | key is the label key being constrained. | [optional] 
**Required** | Pointer to **bool** | required means the creator must provide this label. | [optional] 
**Values** | Pointer to **[]string** | values bounds the label&#39;s value; empty means any value. | [optional] 

## Methods

### NewLabelConstraint

`func NewLabelConstraint() *LabelConstraint`

NewLabelConstraint instantiates a new LabelConstraint object.
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed.

### GetKey

`func (o *LabelConstraint) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### SetKey

`func (o *LabelConstraint) SetKey(v string)`

SetKey sets Key field to given value.

### GetRequired

`func (o *LabelConstraint) GetRequired() bool`

GetRequired returns the Required field if non-nil, zero value otherwise.

### SetRequired

`func (o *LabelConstraint) SetRequired(v bool)`

SetRequired sets Required field to given value.

### GetValues

`func (o *LabelConstraint) GetValues() []string`

GetValues returns the Values field if non-nil, zero value otherwise.

### SetValues

`func (o *LabelConstraint) SetValues(v []string)`

SetValues sets Values field to given value.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


