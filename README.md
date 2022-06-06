# Template for Github Codespaces with Kubernetes & Go

Installs (through Docker):
- Kind Cluster & Registry
- kubectl
- Go Version 1.18
- Yarn

(through setup.sh):
- Brew

## Setup & Customizations

[How to use codespaces](https://github.com/features/codespaces)

Can be run either through a docker image or devcontainer.json (which builds a docker image which then gets used)

Start this template as a codespace, once running, run `setup.sh`

## Optional

- Custom environments via [dotfiles](https://burkeholland.github.io/posts/codespaces-dotfiles/)

Installing Helm Charts:  

```
$ ./helm_upgrade.sh
```

## WiP
- How to access the running Cluster locally, e.g. with Lens
- Adding Istio install


