# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/mayrf/argocd-example-apps
# cd into the cloned directory
git checkout 0959b385ed50e4bff33bfa64e762a9f61ef7310a
helm template . --name-template prod-helm-guestbook --include-crds
```
