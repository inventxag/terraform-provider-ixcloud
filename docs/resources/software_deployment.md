---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "ixcloud_software_deployment Resource - terraform-provider-ixcloud"
subcategory: ""
description: |-
  
---

# ixcloud_software_deployment (Resource)



## Example Usage

```terraform
resource "ixcloud_software_deployment" "vscode" {
  virtualmachine_name = "ABCTL1234"
  software = [
    "vscode",
    "vscode-powershell"
  ]
}

resource "ixcloud_software_deployment" "netfx" {
  virtualmachine_name = "ABCTL1234"
  software = [
    "netfx-4.8",
  ]
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `software` (List of String) List of software packages ids to be deployed on the Virtual Machine
- `virtualmachine_name` (String) Name of the virtual machine where the software should be deployed


