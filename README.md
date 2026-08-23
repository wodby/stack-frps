# FRP Server application stack for Kubernetes on Wodby

Deploy FRP Server applications on Kubernetes with Wodby.

This repository defines the Wodby stack manifests and default service
composition for FRP Server.

<!-- wodby:generated:start -->

## Stack contract

- [FRP Server stack on Wodby](https://wodby.com/stacks/frps)
- [Browse Wodby application stacks](https://wodby.com/stacks)
- [FRP Server stack guide](https://wodby.com/docs/2.0/stacks/catalog/frps/)
- [Wodby stack documentation](https://wodby.com/docs/2.0/stacks/)
- [Stack manifest reference](https://wodby.com/docs/2.0/stacks/template/)

## Service definitions

- [FRP Server service](https://github.com/wodby/service-frps)

## What's included

| Component / service | Default configuration |
| --- | --- |
| FRP Server<br>`frps` | required; enabled by default |

Enabled optional services are selected by default but can be excluded when an
app is created. Disabled optional services are available but not selected by
default. Required services cannot be excluded.

## Validate the stack manifest

```bash
wodby stack validate-manifest stack.yml --org <org-id>
```

<!-- wodby:generated:end -->

## Deploy this stack

Add this stack from the Wodby catalog, then configure its enabled services and
integrations.

Review service versions, storage, links, and optional components when creating
the application. The same stack can be reused across development, staging, and
production environments.

## Maintain a custom version

1. Fork this repository.
2. Edit the stack manifest.
3. Import the repository as a [Git-backed stack](https://wodby.com/docs/2.0/stacks/create/#create-a-git-backed-stack).

When replacing or renaming a stack service, update every related link target
and derivative reference. Stack-local names and referenced service names are
distinct identifiers.
