helm upgrade --install cert-manager jetstack/cert-manager --namespace cert-manager --create-namespace --set crds.enabled=true
kubectl apply -f cert-manager/ -f mongodb/ -f mongo-express/
