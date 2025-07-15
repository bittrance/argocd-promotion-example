
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/bittrance/argocd-promotion-example
# cd into the cloned directory
git checkout 24b9f8df6f444e6efb2df42e863b631b454ed035
helm template . --name-template hello-rest-test --set replicas=2 --include-crds
```