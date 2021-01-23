# jenkins-k8s

```
kubectl exec -it -n jenkins $(kubectl get pods -o=jsonpath='{.items[0].metadata.name}' -n jenkins) -- cat /var/jenkins
_home/secrets/initialAdminPassword

```
