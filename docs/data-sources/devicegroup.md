---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "simplemdm_devicegroup Data Source - simplemdm"
subcategory: ""
description: |-
  
---

# simplemdm_devicegroup (Data Source)



## Example Usage

```terraform
data "simplemdm_devicegroup" "devicegroup" {
  id = "123456"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `id` (String) ID of a Device Group in SimpleMDM.

### Read-Only

- `name` (String) Device group name.