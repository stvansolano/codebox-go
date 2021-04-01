# My Codespace

[Twitter: @stvansolano](https://twitter.com/stvansolano)

## Do you like it? Give a Star! :star:

If you like or are using this project to learn or start your own solution, please give it a star. I appreciate it!

A ready-to-use, templated GitHub Codespace that I regularly use for VS Code on GitHub (Codespaces).

## Batteries included

- Docker
- Kubernetes - K3D

Extensions

- Docker
- Kubernetes
- Go

# Samples included in this Codebox (branches):
- [Hello World - [main]*](https://github.com/stvansolano/codebox-go/tree/main)
- [Azure functions [az-functions]](https://github.com/stvansolano/codebox-go/tree/az-functions)
- ... more coming!

## k3d commands

```
k3d cluster create mycluster \
    && k3d kubeconfig merge mycluster --kubeconfig-switch-context
```
