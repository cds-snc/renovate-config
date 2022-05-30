# CDS Renovate default config

This repository provides some base files for setting up a repository at
CDS. Plan is to create more project template for specific technologies:

### How to use

Grant the `renovate-bot` access to your repository. This will result in the creation of an onboarding PR that contains a `renovate.json`. Update that renovate.json to what's contained in the following code block.

```json
{
  "extends": [
    "github>cds-snc/renovate-config"
  ]
}
```