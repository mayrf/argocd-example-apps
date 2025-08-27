# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/mayrf/argocd-example-apps
# cd into the cloned directory
git checkout c23ee85c216141ff64e2993bb467dc4529cc2178
helm template . --name-template prod-helm-guestbook --include-crds
```
