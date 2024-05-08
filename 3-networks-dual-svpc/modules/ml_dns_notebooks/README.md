# Machine Learning Cloud DNS Notebooks Service Endpoints module

Configures the service endpoints to use a custom Private Service Connect IP.

- `*.notebooks.cloud.google.com`
- `*.notebooks.googleusercontent.com`
- `*.kernels.googleusercontent.com`

<!-- BEGINNING OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| private\_service\_connect\_ip | Google Private Service Connect IP Address. | `string` | n/a | yes |
| private\_visibility\_config\_networks | List of VPC self links that can see this zone. | `list(string)` | `[]` | no |
| project\_id | Project ID of the project in which Cloud DNS configurations will be made. | `string` | n/a | yes |

## Outputs

No outputs.

<!-- END OF PRE-COMMIT-TERRAFORM DOCS HOOK -->