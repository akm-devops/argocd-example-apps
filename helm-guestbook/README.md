# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/akm-devops/argocd-example-apps
# cd into the cloned directory
git checkout 07dda7cffa6b463a8ca63bcbac6addf317ace7b3
helm template . --name-template staging-helm-guestbook --include-crds
```
