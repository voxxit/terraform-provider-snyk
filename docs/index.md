---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "snyk-assets Provider"
subcategory: ""
description: |-
  
---

# snyk-assets Provider



## Example Usage

```terraform
variable "SNYK_TOKEN" {
  default = ""
}

provider "snyk" {
  # example configuration here
  api_token = var.SNYK_TOKEN
  endpoint  = "https://api.snyk.io/rest"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Optional

- `api_token` (String) API token
- `endpoint` (String) Example provider attribute