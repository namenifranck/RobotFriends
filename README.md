# robofriends
To run the project:

1. Clone this repo
2. Run `npm install`
3. Run `npm start`

# Kubernetes commands

kubectl get deploy
kubectl get svc

## HELM 

troubleshooting technique
helm lint

helm template . : check the mapping values

helm template .| kubectl create -f - : simulate deployment
