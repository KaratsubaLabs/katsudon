
# DEPLOYMENT

Create secret using env file for gitbounites
```sh
kubectl --namespace karatsuba create secret generic gitbounties-secret  --dry-run=client --save-config --from-file=.env -o yaml | kubectl apply -f -

```
