# terraform-vault-management
<!-- BEGIN_TF_DOCS -->
## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_vault"></a> [vault](#requirement\_vault) | 3.14.0 |

## Providers

| Name | Version |
|------|---------|
| <a name="provider_vault"></a> [vault](#provider\_vault) | 3.14.0 |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [vault_identity_group.internal](https://registry.terraform.io/providers/hashicorp/vault/3.14.0/docs/resources/identity_group) | resource |
| [vault_identity_group_member_entity_ids.test](https://registry.terraform.io/providers/hashicorp/vault/3.14.0/docs/resources/identity_group_member_entity_ids) | resource |
| [vault_mount.kv_vaults](https://registry.terraform.io/providers/hashicorp/vault/3.14.0/docs/resources/mount) | resource |
| [vault_policy.policies](https://registry.terraform.io/providers/hashicorp/vault/3.14.0/docs/resources/policy) | resource |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_vault_address"></a> [vault\_address](#input\_vault\_address) | Vault address. | `string` | `"https://your_vault/"` | no |
| <a name="input_vault_token"></a> [vault\_token](#input\_vault\_token) | Vault token. | `string` | `""` | no |

## Outputs

No outputs.
<!-- END_TF_DOCS -->