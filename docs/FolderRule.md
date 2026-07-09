# FolderRule

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Allowed** | Pointer to **[]string** | allowed lists permitted parent folder IDs (\&quot;root\&quot; for the root level). | [optional] 
**Default** | Pointer to **string** | default is preselected when the question is asked. | [optional] 

## Methods

### NewFolderRule

`func NewFolderRule() *FolderRule`

NewFolderRule instantiates a new FolderRule object.
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed.

### GetAllowed

`func (o *FolderRule) GetAllowed() []string`

GetAllowed returns the Allowed field if non-nil, zero value otherwise.

### SetAllowed

`func (o *FolderRule) SetAllowed(v []string)`

SetAllowed sets Allowed field to given value.

### GetDefault

`func (o *FolderRule) GetDefault() string`

GetDefault returns the Default field if non-nil, zero value otherwise.

### SetDefault

`func (o *FolderRule) SetDefault(v string)`

SetDefault sets Default field to given value.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


