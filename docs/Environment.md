# Environment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CreatedAt** | **time.Time** | created_at is when the environment was created. | 
**CreationSpec** | **map[string]interface{}** | creation_spec is a JSON Schema (draft 2020-12) document describing the CreateClusterInEnvironment request body this environment accepts: one property per asked question plus name; environment-owned questions are absent. required lists only the fields whose omission makes creation fail. Derived from rules at read time; output only. | [readonly] 
**Description** | **string** | description should say when to use this environment, not what it configures. | 
**Id** | **string** | id uniquely identifies the environment. | 
**Name** | **string** | name is unique within the organization. Choose names creators can pick from alone, using knowledge they already have (dev, staging, prod). | 
**Rules** | [**EnvironmentRules**](EnvironmentRules.md) |  | 
**UpdateSpec** | **map[string]interface{}** | update_spec is the same schema restricted to the fields UpdateClusterInEnvironment supports. It carries no defaults and no required list: omitting a field in an update leaves it unchanged. Derived from rules at read time; output only. | [readonly] 
**UpdatedAt** | **time.Time** | updated_at is when the environment was last updated. | 

## Methods

### NewEnvironment

`func NewEnvironment(createdAt time.Time, creationSpec map[string]interface{}, description string, id string, name string, rules EnvironmentRules, updateSpec map[string]interface{}, updatedAt time.Time, ) *Environment`

NewEnvironment instantiates a new Environment object.
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed.

### NewEnvironmentWithDefaults

`func NewEnvironmentWithDefaults() *Environment`

NewEnvironmentWithDefaults instantiates a new Environment object.
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set.

### GetCreatedAt

`func (o *Environment) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### SetCreatedAt

`func (o *Environment) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### GetCreationSpec

`func (o *Environment) GetCreationSpec() map[string]interface{}`

GetCreationSpec returns the CreationSpec field if non-nil, zero value otherwise.

### SetCreationSpec

`func (o *Environment) SetCreationSpec(v map[string]interface{})`

SetCreationSpec sets CreationSpec field to given value.

### GetDescription

`func (o *Environment) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### SetDescription

`func (o *Environment) SetDescription(v string)`

SetDescription sets Description field to given value.

### GetId

`func (o *Environment) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### SetId

`func (o *Environment) SetId(v string)`

SetId sets Id field to given value.

### GetName

`func (o *Environment) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### SetName

`func (o *Environment) SetName(v string)`

SetName sets Name field to given value.

### GetRules

`func (o *Environment) GetRules() EnvironmentRules`

GetRules returns the Rules field if non-nil, zero value otherwise.

### SetRules

`func (o *Environment) SetRules(v EnvironmentRules)`

SetRules sets Rules field to given value.

### GetUpdateSpec

`func (o *Environment) GetUpdateSpec() map[string]interface{}`

GetUpdateSpec returns the UpdateSpec field if non-nil, zero value otherwise.

### SetUpdateSpec

`func (o *Environment) SetUpdateSpec(v map[string]interface{})`

SetUpdateSpec sets UpdateSpec field to given value.

### GetUpdatedAt

`func (o *Environment) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### SetUpdatedAt

`func (o *Environment) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


