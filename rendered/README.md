
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/bittrance/argocd-promotion-example
# cd into the cloned directory
git checkout 9d4d3db02eb987a93791e2715d6ab8c8b559a320
helm template . --name-template hello-rest-test --set replicas=2 --include-crds
```