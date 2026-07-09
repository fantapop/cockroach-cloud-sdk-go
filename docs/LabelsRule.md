# LabelsRule

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AllowOtherLabels** | Pointer to **bool** | allow_other_labels permits creator labels on keys not listed in constraints. | [optional] 
**Constraints** | Pointer to [**[]LabelConstraint**](LabelConstraint.md) | constraints govern specific creator label keys. | [optional] 
**Supplied** | Pointer to **map[string]string** | supplied labels are stamped on every cluster created in the environment and win key collisions with creator labels. | [optional] 

## Methods

### NewLabelsRule

`func NewLabelsRule() *LabelsRule`

NewLabelsRule instantiates a new LabelsRule object.
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed.

### GetAllowOtherLabels

`func (o *LabelsRule) GetAllowOtherLabels() bool`

GetAllowOtherLabels returns the AllowOtherLabels field if non-nil, zero value otherwise.

### SetAllowOtherLabels

`func (o *LabelsRule) SetAllowOtherLabels(v bool)`

SetAllowOtherLabels sets AllowOtherLabels field to given value.

### GetConstraints

`func (o *LabelsRule) GetConstraints() []LabelConstraint`

GetConstraints returns the Constraints field if non-nil, zero value otherwise.

### SetConstraints

`func (o *LabelsRule) SetConstraints(v []LabelConstraint)`

SetConstraints sets Constraints field to given value.

### GetSupplied

`func (o *LabelsRule) GetSupplied() map[string]string`

GetSupplied returns the Supplied field if non-nil, zero value otherwise.

### SetSupplied

`func (o *LabelsRule) SetSupplied(v map[string]string)`

SetSupplied sets Supplied field to given value.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


