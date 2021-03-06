---
page_title: "snowflake_table Resource - terraform-provider-snowflake"
subcategory: ""
description: |-
  
---

# Resource `snowflake_table`





## Schema

### Required

- **column** (Block List, Min: 1) Definitions of a column to create in the table. Minimum one required. (see [below for nested schema](#nestedblock--column))
- **database** (String, Required) The database in which to create the table.
- **name** (String, Required) Specifies the identifier for the table; must be unique for the database and schema in which the table is created.
- **schema** (String, Required) The schema in which to create the table.

### Optional

- **comment** (String, Optional) Specifies a comment for the table.
- **id** (String, Optional) The ID of this resource.

### Read-only

- **owner** (String, Read-only) Name of the role that owns the table.

<a id="nestedblock--column"></a>
### Nested Schema for `column`

Required:

- **name** (String, Required) Column name
- **type** (String, Required) Column type, e.g. VARIANT


