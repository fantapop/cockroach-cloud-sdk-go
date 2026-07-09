# DeleteProtectionRule

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Allowed** | Pointer to [**[]DeleteProtectionStateType**](DeleteProtectionStateType.md) | allowed constrains the setting. Empty means both; one value owns it. | [optional] 
**Default** | Pointer to [**DeleteProtectionStateType**](DeleteProtectionStateType.md) |  | [optional] 

## Methods

### NewDeleteProtectionRule

`func NewDeleteProtectionRule() *DeleteProtectionRule`

NewDeleteProtectionRule instantiates a new DeleteProtectionRule object.
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed.

### GetAllowed

`func (o *DeleteProtectionRule) GetAllowed() []DeleteProtectionStateType`

GetAllowed returns the Allowed field if non-nil, zero value otherwise.

### SetAllowed

`func (o *DeleteProtectionRule) SetAllowed(v []DeleteProtectionStateType)`

SetAllowed sets Allowed field to given value.

### GetDefault

`func (o *DeleteProtectionRule) GetDefault() DeleteProtectionStateType`

GetDefault returns the Default field if non-nil, zero value otherwise.

### SetDefault

`func (o *DeleteProtectionRule) SetDefault(v DeleteProtectionStateType)`

SetDefault sets Default field to given value.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


