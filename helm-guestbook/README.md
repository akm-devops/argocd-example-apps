# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/akm-devops/argocd-example-apps
# cd into the cloned directory
git checkout 22875a97c7d7d655b7829d8d0ebf9a115cb17a0b
helm template . --name-template prod-helm-guestbook --include-crds
```
