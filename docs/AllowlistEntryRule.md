# AllowlistEntryRule

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Cidr** | Pointer to **string** | cidr is the entry in \&quot;ip/mask\&quot; form; a bare IP means /32. Include \&quot;0.0.0.0/0\&quot; for open-to-all. | [optional] 
**Sql** | Pointer to **bool** | sql grants SQL access from the range. | [optional] 
**Ui** | Pointer to **bool** | ui grants DB Console access from the range. | [optional] 

## Methods

### NewAllowlistEntryRule

`func NewAllowlistEntryRule() *AllowlistEntryRule`

NewAllowlistEntryRule instantiates a new AllowlistEntryRule object.
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed.

### GetCidr

`func (o *AllowlistEntryRule) GetCidr() string`

GetCidr returns the Cidr field if non-nil, zero value otherwise.

### SetCidr

`func (o *AllowlistEntryRule) SetCidr(v string)`

SetCidr sets Cidr field to given value.

### GetSql

`func (o *AllowlistEntryRule) GetSql() bool`

GetSql returns the Sql field if non-nil, zero value otherwise.

### SetSql

`func (o *AllowlistEntryRule) SetSql(v bool)`

SetSql sets Sql field to given value.

### GetUi

`func (o *AllowlistEntryRule) GetUi() bool`

GetUi returns the Ui field if non-nil, zero value otherwise.

### SetUi

`func (o *AllowlistEntryRule) SetUi(v bool)`

SetUi sets Ui field to given value.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


