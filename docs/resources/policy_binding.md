---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "authentik_policy_binding Resource - terraform-provider-authentik"
subcategory: ""
description: |-
  
---

# authentik_policy_binding (Resource)





<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **order** (Number)
- **target** (String) ID of the object this binding should apply to

### Optional

- **enabled** (Boolean) Defaults to `true`.
- **group** (String) UUID of the group
- **id** (String) The ID of this resource.
- **negate** (Boolean) Defaults to `false`.
- **policy** (String) UUID of the policy
- **timeout** (Number) Defaults to `30`.
- **user** (String) UID of the user

