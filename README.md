# Sql Kubernetes Installtion

## SQL sa password secret
```
kubectl create secret generic mssql --from-literal=SA_PASSWORD=Abc123!!
```
## Apply Persistent Volume Claim
