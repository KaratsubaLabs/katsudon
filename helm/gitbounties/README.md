
# DEPLOYMENT

Create secret using env file for gitbounites
```sh
kubectl create secret generic gitbounties-secret --from-env-file=.env
```
