# CloudAccountRule

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Settable** | Pointer to **bool** | settable permits the creator to supply a customer cloud account. | [optional] 
**Value** | Pointer to [**CustomerCloudAccount**](CustomerCloudAccount.md) |  | [optional] 

## Methods

### NewCloudAccountRule

`func NewCloudAccountRule() *CloudAccountRule`

NewCloudAccountRule instantiates a new CloudAccountRule object.
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed.

### GetSettable

`func (o *CloudAccountRule) GetSettable() bool`

GetSettable returns the Settable field if non-nil, zero value otherwise.

### SetSettable

`func (o *CloudAccountRule) SetSettable(v bool)`

SetSettable sets Settable field to given value.

### GetValue

`func (o *CloudAccountRule) GetValue() CustomerCloudAccount`

GetValue returns the Value field if non-nil, zero value otherwise.

### SetValue

`func (o *CloudAccountRule) SetValue(v CustomerCloudAccount)`

SetValue sets Value field to given value.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


