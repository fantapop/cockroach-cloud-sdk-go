# RegionRule

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Allowed** | Pointer to **[]string** | allowed lists the permitted regions of the environment&#39;s provider. | [optional] 
**Default** | Pointer to **[]string** | default is preselected when the question is asked; it must be a subset of allowed when allowed is non-empty. | [optional] 
**MaxRegionCount** | Pointer to **int32** | max_region_count caps regions per cluster; 1 means single-region only; 0 means no cap. | [optional] 

## Methods

### NewRegionRule

`func NewRegionRule() *RegionRule`

NewRegionRule instantiates a new RegionRule object.
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed.

### GetAllowed

`func (o *RegionRule) GetAllowed() []string`

GetAllowed returns the Allowed field if non-nil, zero value otherwise.

### SetAllowed

`func (o *RegionRule) SetAllowed(v []string)`

SetAllowed sets Allowed field to given value.

### GetDefault

`func (o *RegionRule) GetDefault() []string`

GetDefault returns the Default field if non-nil, zero value otherwise.

### SetDefault

`func (o *RegionRule) SetDefault(v []string)`

SetDefault sets Default field to given value.

### GetMaxRegionCount

`func (o *RegionRule) GetMaxRegionCount() int32`

GetMaxRegionCount returns the MaxRegionCount field if non-nil, zero value otherwise.

### SetMaxRegionCount

`func (o *RegionRule) SetMaxRegionCount(v int32)`

SetMaxRegionCount sets MaxRegionCount field to given value.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


