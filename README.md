# Keycloak OAUTH2 Service

## Deploy for development namespace
kubectl apply -f ./keycloak-dev

## Deploy for production namespace
kubectl apply -f ./keycloak-prod

## To log in to the UI you have to use port forward
kubectl port-forward <pod-name> 9080:9080