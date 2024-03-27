# NextDNS Terraform Provider

This repo is a fork of [amalucelli/terraform-provider-nextdns](https://github.com/amalucelli/terraform-provider-nextdns), I decide to fork it because the original repo is not responding to PR.
Thanks to [amalucelli](https://github.com/amalucelli) for the original work.

[NextDNS](https://nextdns.io/) provider for [Terraform](https://terraform.io).

This provider lets you declaratively define the configuration for your NextDNS profiles.

## Requirements

An API Key is required to interact with the NextDNS API.
You can find your API Key in the [NextDNS account](https://my.nextdns.io/account) page.

## Getting Started

```hcl
terraform {
  required_providers {
    nextdns = {
      source  = "carbans/nextdns"
      version = "0.2.2"
    }
  }
}

provider "nextdns" {
  api_key = "NEXTDNS_API_KEY"
}
```
