
## Installation

```sh
helm repo add k8s-at-home https://k8s-at-home.com/charts/
helm repo update
helm upgrade --install kanboard k8s-at-home/kanboard
    --namespace=karatsuba \
```
