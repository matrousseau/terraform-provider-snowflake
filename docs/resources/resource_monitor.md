---
page_title: "snowflake_resource_monitor Resource - terraform-provider-snowflake"
subcategory: ""
description: |-
  
---

# Resource `snowflake_resource_monitor`





## Schema

### Required

- **name** (String, Required) Identifier for the resource monitor; must be unique for your account.

### Optional

- **credit_quota** (Number, Optional) The number of credits allocated monthly to the resource monitor.
- **end_timestamp** (String, Optional) The date and time when the resource monitor suspends the assigned warehouses.
- **frequency** (String, Optional) The frequency interval at which the credit usage resets to 0. If you set a frequency for a resource monitor, you must also set START_TIMESTAMP.
- **id** (String, Optional) The ID of this resource.
- **notify_triggers** (Set of Number, Optional) A list of percentage thresholds at which to send an alert to subscribed users.
- **start_timestamp** (String, Optional) The date and time when the resource monitor starts monitoring credit usage for the assigned warehouses.
- **suspend_immediate_triggers** (Set of Number, Optional) A list of percentage thresholds at which to immediately suspend all warehouses.
- **suspend_triggers** (Set of Number, Optional) A list of percentage thresholds at which to suspend all warehouses.


