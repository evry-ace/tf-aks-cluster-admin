# tf_aks_cluster_admin

Terraform Module for Azure AKS Cluster Admin Role Binding

## Usage

```hcl
module "aks_admin_role_binding" {
  source   = "github.com/evry-ace/tf_aks_cluster_admin"
  group_id = "${var.aks_rbac_cluster_admins_group_id}"
}
```

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|:----:|:-----:|:-----:|
| group\_id | Azure AD administrator group ID | string | `"000000-0000-0000-000000"` | yes |

## Authors

Module is maintained by the EVRY ACE Team.

## License

MIT License. See [LICENSE](./LICENSE) for full details.
