# Spin up
kubectl create -f clair-kubernetes.yaml

# CleanUp
kubectl delete po,svc,rc -l app=postgres
kubectl delete po,svc,rc -l app=clair

