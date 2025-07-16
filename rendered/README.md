
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/bittrance/argocd-promotion-example
# cd into the cloned directory
git checkout 1fb992d897d1aed51a2f2bf60018d42f85cbaf6c
helm template . --name-template hello-rest-test --set replicas=3 --include-crds
```