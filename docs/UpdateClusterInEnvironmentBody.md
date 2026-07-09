# UpdateClusterInEnvironmentBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeleteProtection** | Pointer to [**DeleteProtectionStateType**](DeleteProtectionStateType.md) |  | [optional] 
**FolderId** | Pointer to **string** | folder_id answers the folder question. | [optional] 
**Labels** | Pointer to **map[string]string** | labels are creator labels, merged under the environment&#39;s label rules. | [optional] 
**Regions** | Pointer to **[]string** | regions answers the region question. | [optional] 
**StorageGib** | Pointer to **int64** | storage_gib answers the storage question (dedicated family only). | [optional] 
**Vcpus** | Pointer to **int64** | vcpus answers the compute size question. | [optional] 

## Methods

### NewUpdateClusterInEnvironmentBody

`func NewUpdateClusterInEnvironmentBody() *UpdateClusterInEnvironmentBody`

NewUpdateClusterInEnvironmentBody instantiates a new UpdateClusterInEnvironmentBody object.
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed.

### GetDeleteProtection

`func (o *UpdateClusterInEnvironmentBody) GetDeleteProtection() DeleteProtectionStateType`

GetDeleteProtection returns the DeleteProtection field if non-nil, zero value otherwise.

### SetDeleteProtection

`func (o *UpdateClusterInEnvironmentBody) SetDeleteProtection(v DeleteProtectionStateType)`

SetDeleteProtection sets DeleteProtection field to given value.

### GetFolderId

`func (o *UpdateClusterInEnvironmentBody) GetFolderId() string`

GetFolderId returns the FolderId field if non-nil, zero value otherwise.

### SetFolderId

`func (o *UpdateClusterInEnvironmentBody) SetFolderId(v string)`

SetFolderId sets FolderId field to given value.

### GetLabels

`func (o *UpdateClusterInEnvironmentBody) GetLabels() map[string]string`

GetLabels returns the Labels field if non-nil, zero value otherwise.

### SetLabels

`func (o *UpdateClusterInEnvironmentBody) SetLabels(v map[string]string)`

SetLabels sets Labels field to given value.

### GetRegions

`func (o *UpdateClusterInEnvironmentBody) GetRegions() []string`

GetRegions returns the Regions field if non-nil, zero value otherwise.

### SetRegions

`func (o *UpdateClusterInEnvironmentBody) SetRegions(v []string)`

SetRegions sets Regions field to given value.

### GetStorageGib

`func (o *UpdateClusterInEnvironmentBody) GetStorageGib() int64`

GetStorageGib returns the StorageGib field if non-nil, zero value otherwise.

### SetStorageGib

`func (o *UpdateClusterInEnvironmentBody) SetStorageGib(v int64)`

SetStorageGib sets StorageGib field to given value.

### GetVcpus

`func (o *UpdateClusterInEnvironmentBody) GetVcpus() int64`

GetVcpus returns the Vcpus field if non-nil, zero value otherwise.

### SetVcpus

`func (o *UpdateClusterInEnvironmentBody) SetVcpus(v int64)`

SetVcpus sets Vcpus field to given value.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


