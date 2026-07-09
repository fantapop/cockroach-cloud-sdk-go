# NetworkRule

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RestrictEgressTraffic** | Pointer to [**BoolRule**](BoolRule.md) |  | [optional] 
**VisibilityAllowed** | Pointer to [**[]NetworkVisibilityType**](NetworkVisibilityType.md) | visibility_allowed constrains network visibility. Empty means both; exactly one value means the environment owns it. PRIVATE forces the dedicated family. | [optional] 
**VisibilityDefault** | Pointer to [**NetworkVisibilityType**](NetworkVisibilityType.md) |  | [optional] 

## Methods

### NewNetworkRule

`func NewNetworkRule() *NetworkRule`

NewNetworkRule instantiates a new NetworkRule object.
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed.

### GetRestrictEgressTraffic

`func (o *NetworkRule) GetRestrictEgressTraffic() BoolRule`

GetRestrictEgressTraffic returns the RestrictEgressTraffic field if non-nil, zero value otherwise.

### SetRestrictEgressTraffic

`func (o *NetworkRule) SetRestrictEgressTraffic(v BoolRule)`

SetRestrictEgressTraffic sets RestrictEgressTraffic field to given value.

### GetVisibilityAllowed

`func (o *NetworkRule) GetVisibilityAllowed() []NetworkVisibilityType`

GetVisibilityAllowed returns the VisibilityAllowed field if non-nil, zero value otherwise.

### SetVisibilityAllowed

`func (o *NetworkRule) SetVisibilityAllowed(v []NetworkVisibilityType)`

SetVisibilityAllowed sets VisibilityAllowed field to given value.

### GetVisibilityDefault

`func (o *NetworkRule) GetVisibilityDefault() NetworkVisibilityType`

GetVisibilityDefault returns the VisibilityDefault field if non-nil, zero value otherwise.

### SetVisibilityDefault

`func (o *NetworkRule) SetVisibilityDefault(v NetworkVisibilityType)`

SetVisibilityDefault sets VisibilityDefault field to given value.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


