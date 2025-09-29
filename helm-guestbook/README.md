# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/akm-devops/argocd-example-apps
# cd into the cloned directory
git checkout 27c566295f2688d9db50a0fa1dfd8d016455f3b0
helm template . --name-template staging-helm-guestbook --include-crds
```
