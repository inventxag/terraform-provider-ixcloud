---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "ixcloud_dvd_drive Resource - terraform-provider-ixcloud"
subcategory: ""
description: |-
  Resource for creating and attaching virtual dvd drives to virtual machines
---

# ixcloud_dvd_drive (Resource)

Resource for creating and attaching virtual dvd drives to virtual machines

## Example Usage

```terraform
resource "ixcloud_dvd_drive" "dvd" {
  virtualmachine_name = "ABCTL1234"
  lun                 = 1
  iso_image           = "MyIsoImage.iso"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `lun` (Number)
- `virtualmachine_name` (String)

### Optional

- `bus` (Number)
- `iso_image` (String)
- `name` (String)

