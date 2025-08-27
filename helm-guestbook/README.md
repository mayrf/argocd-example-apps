# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/mayrf/argocd-example-apps
# cd into the cloned directory
git checkout f58c7ed8cfe28ad70701c5923fdbd0154388ea9f
helm template . --name-template prod-helm-guestbook --include-crds
```
