# CreateClusterInEnvironmentBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AllowlistEntries** | Pointer to [**[]AllowlistEntryRule**](AllowlistEntryRule.md) | allowlist_entries are additional entries, when the allowlist is settable. | [optional] 
**CidrRange** | Pointer to **string** | cidr_range overrides the network range, when the cidr rule is settable. | [optional] 
**CloudAccount** | Pointer to [**CustomerCloudAccount**](CustomerCloudAccount.md) |  | [optional] 
**DeleteProtection** | Pointer to [**DeleteProtectionStateType**](DeleteProtectionStateType.md) |  | [optional] 
**FolderId** | Pointer to **string** | folder_id answers the folder question. | [optional] 
**Isolation** | Pointer to [**ComputeIsolationType**](ComputeIsolationType.md) |  | [optional] 
**Labels** | Pointer to **map[string]string** | labels are creator labels, merged under the environment&#39;s label rules. | [optional] 
**Name** | **string** | name follows the same constraints as CreateClusterRequest.name. | 
**NetworkVisibility** | Pointer to [**NetworkVisibilityType**](NetworkVisibilityType.md) |  | [optional] 
**Regions** | Pointer to **[]string** | regions answers the region question. | [optional] 
**RestrictEgressTraffic** | Pointer to **bool** | restrict_egress_traffic answers the egress question. | [optional] 
**StorageGib** | Pointer to **int64** | storage_gib answers the storage question (dedicated family only). | [optional] 
**Vcpus** | Pointer to **int64** | vcpus answers the compute size question. | [optional] 

## Methods

### NewCreateClusterInEnvironmentBody

`func NewCreateClusterInEnvironmentBody(name string, ) *CreateClusterInEnvironmentBody`

NewCreateClusterInEnvironmentBody instantiates a new CreateClusterInEnvironmentBody object.
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed.

### NewCreateClusterInEnvironmentBodyWithDefaults

`func NewCreateClusterInEnvironmentBodyWithDefaults() *CreateClusterInEnvironmentBody`

NewCreateClusterInEnvironmentBodyWithDefaults instantiates a new CreateClusterInEnvironmentBody object.
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set.

### GetAllowlistEntries

`func (o *CreateClusterInEnvironmentBody) GetAllowlistEntries() []AllowlistEntryRule`

GetAllowlistEntries returns the AllowlistEntries field if non-nil, zero value otherwise.

### SetAllowlistEntries

`func (o *CreateClusterInEnvironmentBody) SetAllowlistEntries(v []AllowlistEntryRule)`

SetAllowlistEntries sets AllowlistEntries field to given value.

### GetCidrRange

`func (o *CreateClusterInEnvironmentBody) GetCidrRange() string`

GetCidrRange returns the CidrRange field if non-nil, zero value otherwise.

### SetCidrRange

`func (o *CreateClusterInEnvironmentBody) SetCidrRange(v string)`

SetCidrRange sets CidrRange field to given value.

### GetCloudAccount

`func (o *CreateClusterInEnvironmentBody) GetCloudAccount() CustomerCloudAccount`

GetCloudAccount returns the CloudAccount field if non-nil, zero value otherwise.

### SetCloudAccount

`func (o *CreateClusterInEnvironmentBody) SetCloudAccount(v CustomerCloudAccount)`

SetCloudAccount sets CloudAccount field to given value.

### GetDeleteProtection

`func (o *CreateClusterInEnvironmentBody) GetDeleteProtection() DeleteProtectionStateType`

GetDeleteProtection returns the DeleteProtection field if non-nil, zero value otherwise.

### SetDeleteProtection

`func (o *CreateClusterInEnvironmentBody) SetDeleteProtection(v DeleteProtectionStateType)`

SetDeleteProtection sets DeleteProtection field to given value.

### GetFolderId

`func (o *CreateClusterInEnvironmentBody) GetFolderId() string`

GetFolderId returns the FolderId field if non-nil, zero value otherwise.

### SetFolderId

`func (o *CreateClusterInEnvironmentBody) SetFolderId(v string)`

SetFolderId sets FolderId field to given value.

### GetIsolation

`func (o *CreateClusterInEnvironmentBody) GetIsolation() ComputeIsolationType`

GetIsolation returns the Isolation field if non-nil, zero value otherwise.

### SetIsolation

`func (o *CreateClusterInEnvironmentBody) SetIsolation(v ComputeIsolationType)`

SetIsolation sets Isolation field to given value.

### GetLabels

`func (o *CreateClusterInEnvironmentBody) GetLabels() map[string]string`

GetLabels returns the Labels field if non-nil, zero value otherwise.

### SetLabels

`func (o *CreateClusterInEnvironmentBody) SetLabels(v map[string]string)`

SetLabels sets Labels field to given value.

### GetName

`func (o *CreateClusterInEnvironmentBody) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### SetName

`func (o *CreateClusterInEnvironmentBody) SetName(v string)`

SetName sets Name field to given value.

### GetNetworkVisibility

`func (o *CreateClusterInEnvironmentBody) GetNetworkVisibility() NetworkVisibilityType`

GetNetworkVisibility returns the NetworkVisibility field if non-nil, zero value otherwise.

### SetNetworkVisibility

`func (o *CreateClusterInEnvironmentBody) SetNetworkVisibility(v NetworkVisibilityType)`

SetNetworkVisibility sets NetworkVisibility field to given value.

### GetRegions

`func (o *CreateClusterInEnvironmentBody) GetRegions() []string`

GetRegions returns the Regions field if non-nil, zero value otherwise.

### SetRegions

`func (o *CreateClusterInEnvironmentBody) SetRegions(v []string)`

SetRegions sets Regions field to given value.

### GetRestrictEgressTraffic

`func (o *CreateClusterInEnvironmentBody) GetRestrictEgressTraffic() bool`

GetRestrictEgressTraffic returns the RestrictEgressTraffic field if non-nil, zero value otherwise.

### SetRestrictEgressTraffic

`func (o *CreateClusterInEnvironmentBody) SetRestrictEgressTraffic(v bool)`

SetRestrictEgressTraffic sets RestrictEgressTraffic field to given value.

### GetStorageGib

`func (o *CreateClusterInEnvironmentBody) GetStorageGib() int64`

GetStorageGib returns the StorageGib field if non-nil, zero value otherwise.

### SetStorageGib

`func (o *CreateClusterInEnvironmentBody) SetStorageGib(v int64)`

SetStorageGib sets StorageGib field to given value.

### GetVcpus

`func (o *CreateClusterInEnvironmentBody) GetVcpus() int64`

GetVcpus returns the Vcpus field if non-nil, zero value otherwise.

### SetVcpus

`func (o *CreateClusterInEnvironmentBody) SetVcpus(v int64)`

SetVcpus sets Vcpus field to given value.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


