## Install Argo Events with Kustomize

 * https://github.com/argoproj/argo-events
 https://github.com/kubernetes-sigs/kustomize

## Install Kustomize

 * https://github.com/kubernetes-sigs/kustomize/blob/master/docs/INSTALL.md

## Build & Diff

```
 $ kustomize build . > install.yaml
 $ git diff dist/bundle.yaml
```

## Build & Apply

```
 $ kustomize build . | kc apply -f -
```
