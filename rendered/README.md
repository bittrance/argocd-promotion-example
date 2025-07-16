
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/bittrance/argocd-promotion-example
# cd into the cloned directory
git checkout 8ce211ea692ba0f7573e487e48e43f096f9f126c
helm template . --name-template hello-rest-test --include-crds
```