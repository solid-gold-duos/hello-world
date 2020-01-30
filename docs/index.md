# Hello World Provider

Description paragraph for provider Hello World

## Example Usage

```hcl
# Configure the Hello World Provider
provider "hello-world" {
	user_name = "admin"
	password = "admin"
}
```

~> **Note** This provider is only used for demoing purposes. It prints `hello world`.

## Argument Reference
The following arguments are supported:

* `user_name` - (Required) Yeah this does nothing
* `password` - (Required) Gimme yo pw
* `arg1` - (Optional) reason to be a pirate
* `arg2` - (Optional) another reason to be a pirate
