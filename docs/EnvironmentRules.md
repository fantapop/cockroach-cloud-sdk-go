# EnvironmentRules

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Allowlist** | Pointer to [**AllowlistRule**](AllowlistRule.md) |  | [optional] 
**Cidr** | Pointer to [**CidrRule**](CidrRule.md) |  | [optional] 
**CloudAccount** | Pointer to [**CloudAccountRule**](CloudAccountRule.md) |  | [optional] 
**Compute** | Pointer to [**ComputeRule**](ComputeRule.md) |  | [optional] 
**DeleteProtection** | Pointer to [**DeleteProtectionRule**](DeleteProtectionRule.md) |  | [optional] 
**Folder** | Pointer to [**FolderRule**](FolderRule.md) |  | [optional] 
**Labels** | Pointer to [**LabelsRule**](LabelsRule.md) |  | [optional] 
**Network** | Pointer to [**NetworkRule**](NetworkRule.md) |  | [optional] 
**Provider** | Pointer to [**CloudProviderType**](CloudProviderType.md) |  | [optional] 
**Regions** | Pointer to [**RegionRule**](RegionRule.md) |  | [optional] 

## Methods

### NewEnvironmentRules

`func NewEnvironmentRules() *EnvironmentRules`

NewEnvironmentRules instantiates a new EnvironmentRules object.
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed.

### GetAllowlist

`func (o *EnvironmentRules) GetAllowlist() AllowlistRule`

GetAllowlist returns the Allowlist field if non-nil, zero value otherwise.

### SetAllowlist

`func (o *EnvironmentRules) SetAllowlist(v AllowlistRule)`

SetAllowlist sets Allowlist field to given value.

### GetCidr

`func (o *EnvironmentRules) GetCidr() CidrRule`

GetCidr returns the Cidr field if non-nil, zero value otherwise.

### SetCidr

`func (o *EnvironmentRules) SetCidr(v CidrRule)`

SetCidr sets Cidr field to given value.

### GetCloudAccount

`func (o *EnvironmentRules) GetCloudAccount() CloudAccountRule`

GetCloudAccount returns the CloudAccount field if non-nil, zero value otherwise.

### SetCloudAccount

`func (o *EnvironmentRules) SetCloudAccount(v CloudAccountRule)`

SetCloudAccount sets CloudAccount field to given value.

### GetCompute

`func (o *EnvironmentRules) GetCompute() ComputeRule`

GetCompute returns the Compute field if non-nil, zero value otherwise.

### SetCompute

`func (o *EnvironmentRules) SetCompute(v ComputeRule)`

SetCompute sets Compute field to given value.

### GetDeleteProtection

`func (o *EnvironmentRules) GetDeleteProtection() DeleteProtectionRule`

GetDeleteProtection returns the DeleteProtection field if non-nil, zero value otherwise.

### SetDeleteProtection

`func (o *EnvironmentRules) SetDeleteProtection(v DeleteProtectionRule)`

SetDeleteProtection sets DeleteProtection field to given value.

### GetFolder

`func (o *EnvironmentRules) GetFolder() FolderRule`

GetFolder returns the Folder field if non-nil, zero value otherwise.

### SetFolder

`func (o *EnvironmentRules) SetFolder(v FolderRule)`

SetFolder sets Folder field to given value.

### GetLabels

`func (o *EnvironmentRules) GetLabels() LabelsRule`

GetLabels returns the Labels field if non-nil, zero value otherwise.

### SetLabels

`func (o *EnvironmentRules) SetLabels(v LabelsRule)`

SetLabels sets Labels field to given value.

### GetNetwork

`func (o *EnvironmentRules) GetNetwork() NetworkRule`

GetNetwork returns the Network field if non-nil, zero value otherwise.

### SetNetwork

`func (o *EnvironmentRules) SetNetwork(v NetworkRule)`

SetNetwork sets Network field to given value.

### GetProvider

`func (o *EnvironmentRules) GetProvider() CloudProviderType`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### SetProvider

`func (o *EnvironmentRules) SetProvider(v CloudProviderType)`

SetProvider sets Provider field to given value.

### GetRegions

`func (o *EnvironmentRules) GetRegions() RegionRule`

GetRegions returns the Regions field if non-nil, zero value otherwise.

### SetRegions

`func (o *EnvironmentRules) SetRegions(v RegionRule)`

SetRegions sets Regions field to given value.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


