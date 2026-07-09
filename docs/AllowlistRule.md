# AllowlistRule

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Entries** | Pointer to [**[]AllowlistEntryRule**](AllowlistEntryRule.md) | entries are created with the cluster exactly as authored here; they are owned by the environment. | [optional] 
**Settable** | Pointer to **bool** | settable permits the creator to supply additional entries, including their sql/ui flags. | [optional] 

## Methods

### NewAllowlistRule

`func NewAllowlistRule() *AllowlistRule`

NewAllowlistRule instantiates a new AllowlistRule object.
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed.

### GetEntries

`func (o *AllowlistRule) GetEntries() []AllowlistEntryRule`

GetEntries returns the Entries field if non-nil, zero value otherwise.

### SetEntries

`func (o *AllowlistRule) SetEntries(v []AllowlistEntryRule)`

SetEntries sets Entries field to given value.

### GetSettable

`func (o *AllowlistRule) GetSettable() bool`

GetSettable returns the Settable field if non-nil, zero value otherwise.

### SetSettable

`func (o *AllowlistRule) SetSettable(v bool)`

SetSettable sets Settable field to given value.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


