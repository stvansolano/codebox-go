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

## k3d commands

```
k3d cluster create mycluster \
    && k3d kubeconfig merge mycluster --kubeconfig-switch-context
```

## Azure functions
- https://techcommunity.microsoft.com/t5/apps-on-azure/azure-functions-in-any-language-with-custom-handlers/ba-p/1942744

- https://docs.microsoft.com/en-us/azure/azure-functions/create-first-function-vs-code-other?tabs=go%2Cwindows

- https://docs.microsoft.com/en-us/azure/azure-functions/functions-run-local?tabs=linux%2Ccsharp%2Cbash#v2