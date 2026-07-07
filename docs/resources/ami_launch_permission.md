---
subcategory: "EC2 (Elastic Compute Cloud)"
layout: "aws"
pagee_id = "cmi-12345678"
  group    = "all"
}
```

## Argument Reference

The following arguments are supported:

* `image_id` - (Required) The ID of the image.
* `account_id` - (Optional) The ID of the project (`project@customer`) for the launch permission.
* `group` - (Optional) The name of the group for the launch permission.
    * _Valid values:_ `all`

## Attribute Reference

### Supported attributes

In addition to all arguments above, the following attributes are exported:

* `id` - The ID of the launch permission.

### Unsupported attributes

~> **Note** These attributes may be present in the `terraform.tfstate` file, but they have preset values and cannot be specified in configuration files.

The following attributes are not currently supported:

`organization_arn`, `organizational_unit_arn`.

## Timeouts

Timeouts usage for launch permissions is not currently supported.

## Import

Import of the image launch permissions is not currently supported.
