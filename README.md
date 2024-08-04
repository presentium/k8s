# Kubernetes resources for Presentium

Main repository used by ArgoCD for deploying the Presentium API and tools on the cloud.

## Continuous Delivery

The `main` branch is listened to by ArgoCD, depending on projects changes might be
automatically deployed (for example, staging endpoints) or require manual intervention.

Access to ArgoCD is reserved to organization members, using GitHub OIDC login.

## Contributing

Please refer to the [Contributing Guide][contributing] before making a pull request.

[contributing]: https://github.com/presentium/meta/blob/main/CONTRIBUTING.md
