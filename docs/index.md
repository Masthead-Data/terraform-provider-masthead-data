---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "masthead Provider"
subcategory: ""
description: |-

---

# masthead Provider

## Example Usage

```terraform
provider "masthead" {
  api_token = "your_api_token"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Optional

- `api_token` (String, Sensitive) Masthead API Token. This token is used to authenticate with the Masthead API. To obtain a token, log in to your Masthead account and navigate to the **Settings / API Tokens** page. Create a new token and copy it here. Alternatively, you can set the `MASTHEAD_TOKEN` environment variable to use the token from there.
