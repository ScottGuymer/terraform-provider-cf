---
layout: "cloudfoundry"
page_title: "Cloud Foundry: cloudfoundry_info"
sidebar_current: "docs-cf-datasource-info"
description: |-
  Get information on a Cloud Foundry target.
---

# cloudfoundry\_info

Gets information on a Cloud Foundry target.

## Example Usage

```hcl
data "cloudfoundry_info" "info" {}
```

## Attributes Reference

The following attributes are exported:

* `api_version` - The Cloud Foundry API version
* `auth_endpoint` - The autentication endpoint URL
* `uaa_endpoint` - The UAA endpoint URL
* `routing_endpoint` - The routing endpoint URL
* `logging_endpoint` - The logging services endpoint URL
* `doppler_endpoint` - The doppler services endpoint URL 
* `app_ssh_endpoint` - The app instance SSH endpoint
* `app_ssh_host_key_fingerprint` - The fingerprint of the ssh endpoint
* `app_ssh_oauth_client` - The ssh OAuth client