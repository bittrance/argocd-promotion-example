
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/bittrance/argocd-promotion-example
# cd into the cloned directory
git checkout 485f37332b4d445ffa5cd104636f0d871d1b2f18
helm template . --name-template hello-rest-test --set replicas=2 --include-crds
```