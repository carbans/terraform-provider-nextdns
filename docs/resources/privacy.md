---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "nextdns_privacy Resource - terraform-provider-nextdns"
subcategory: ""
description: |-
  
---

# nextdns_privacy (Resource)





<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `allow_affiliate` (Boolean) Allow affiliate & tracking links.
- `disguised_trackers` (Boolean) Block disguised third-party trackers.
- `profile_id` (String) The profile identifier to target the resource.

### Optional

- `blocklists` (List of String) Blocklists.
- `natives` (List of String) Native tracking protection.

### Read-Only

- `id` (String) The ID of this resource.
