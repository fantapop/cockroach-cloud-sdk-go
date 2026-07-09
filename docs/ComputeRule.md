# ComputeRule

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DefaultStorageGib** | Pointer to **int64** | default_storage_gib is used when storage is not asked or not answered. | [optional] 
**DefaultVcpus** | Pointer to **int64** | default_vcpus is preselected when the question is asked. | [optional] 
**IsolationAllowed** | Pointer to [**[]ComputeIsolationType**](ComputeIsolationType.md) | isolation_allowed constrains the isolation level. Empty means both; exactly one value means the environment owns it. Owning DEDICATED forces dedicated hardware even for public clusters. | [optional] 
**IsolationDefault** | Pointer to [**ComputeIsolationType**](ComputeIsolationType.md) |  | [optional] 
**MaxStorageGib** | Pointer to **int64** | max_storage_gib bounds per-node storage; 0 means unbounded above. | [optional] 
**MaxVcpus** | Pointer to **int64** | max_vcpus is the maximum vCPU count per cluster. 0 means unbounded above. | [optional] 
**MinStorageGib** | Pointer to **int64** | min_storage_gib bounds per-node storage; only meaningful when the family resolves dedicated. 0 means unbounded below. | [optional] 
**MinVcpus** | Pointer to **int64** | min_vcpus is the minimum vCPU count per cluster (provisioned vCPUs on serverless, machine vCPUs on dedicated). 0 means unbounded below. | [optional] 

## Methods

### NewComputeRule

`func NewComputeRule() *ComputeRule`

NewComputeRule instantiates a new ComputeRule object.
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed.

### GetDefaultStorageGib

`func (o *ComputeRule) GetDefaultStorageGib() int64`

GetDefaultStorageGib returns the DefaultStorageGib field if non-nil, zero value otherwise.

### SetDefaultStorageGib

`func (o *ComputeRule) SetDefaultStorageGib(v int64)`

SetDefaultStorageGib sets DefaultStorageGib field to given value.

### GetDefaultVcpus

`func (o *ComputeRule) GetDefaultVcpus() int64`

GetDefaultVcpus returns the DefaultVcpus field if non-nil, zero value otherwise.

### SetDefaultVcpus

`func (o *ComputeRule) SetDefaultVcpus(v int64)`

SetDefaultVcpus sets DefaultVcpus field to given value.

### GetIsolationAllowed

`func (o *ComputeRule) GetIsolationAllowed() []ComputeIsolationType`

GetIsolationAllowed returns the IsolationAllowed field if non-nil, zero value otherwise.

### SetIsolationAllowed

`func (o *ComputeRule) SetIsolationAllowed(v []ComputeIsolationType)`

SetIsolationAllowed sets IsolationAllowed field to given value.

### GetIsolationDefault

`func (o *ComputeRule) GetIsolationDefault() ComputeIsolationType`

GetIsolationDefault returns the IsolationDefault field if non-nil, zero value otherwise.

### SetIsolationDefault

`func (o *ComputeRule) SetIsolationDefault(v ComputeIsolationType)`

SetIsolationDefault sets IsolationDefault field to given value.

### GetMaxStorageGib

`func (o *ComputeRule) GetMaxStorageGib() int64`

GetMaxStorageGib returns the MaxStorageGib field if non-nil, zero value otherwise.

### SetMaxStorageGib

`func (o *ComputeRule) SetMaxStorageGib(v int64)`

SetMaxStorageGib sets MaxStorageGib field to given value.

### GetMaxVcpus

`func (o *ComputeRule) GetMaxVcpus() int64`

GetMaxVcpus returns the MaxVcpus field if non-nil, zero value otherwise.

### SetMaxVcpus

`func (o *ComputeRule) SetMaxVcpus(v int64)`

SetMaxVcpus sets MaxVcpus field to given value.

### GetMinStorageGib

`func (o *ComputeRule) GetMinStorageGib() int64`

GetMinStorageGib returns the MinStorageGib field if non-nil, zero value otherwise.

### SetMinStorageGib

`func (o *ComputeRule) SetMinStorageGib(v int64)`

SetMinStorageGib sets MinStorageGib field to given value.

### GetMinVcpus

`func (o *ComputeRule) GetMinVcpus() int64`

GetMinVcpus returns the MinVcpus field if non-nil, zero value otherwise.

### SetMinVcpus

`func (o *ComputeRule) SetMinVcpus(v int64)`

SetMinVcpus sets MinVcpus field to given value.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


