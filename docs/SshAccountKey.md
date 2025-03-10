# SshAccountKey

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | **string** | The SSH key&#x27;s immutable ID. | [optional] [default to null]
**Key** | **string** | The SSH public key value in OpenSSH format. | [optional] [default to null]
**Comment** | **string** | The comment parsed from the SSH key (if present) | [optional] [default to null]
**Label** | **string** | The user-defined label for the SSH key | [optional] [default to null]
**CreatedOn** | [**time.Time**](time.Time.md) |  | [optional] [default to null]
**LastUsed** | [**time.Time**](time.Time.md) |  | [optional] [default to null]
**Links** | [***BranchrestrictionLinks**](branchrestriction_links.md) |  | [optional] [default to null]
**Owner** | [***Account**](account.md) |  | [optional] [default to null]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

