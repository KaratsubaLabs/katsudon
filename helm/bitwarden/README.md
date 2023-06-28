
## Installation

Chart is from [bitwarden-k8s](https://github.com/cdwv/bitwarden-k8s)

```
helm upgrade --install bitwarden ./chart \
    --namespace=karatsuba \
    -f ./values.yaml
```

## TODO

- [ ] persistent volume
