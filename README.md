# devops-kubernetes-config
Deployment:

```
kubectl create -f manifests/setup
kubectl create -f manifests/
kubectl apply -f manifests/app-deployment.yaml
```

* Grafana will be exposed at `30000` port. (Credentials: admin/admin) (Example dashboard: http://ip-ip-ip-ip:3000/d/85a562078cdf77779eaa1add43ccec1e/kubernetes-compute-resources-namespace-pods?orgId=1&refresh=10s&var-datasource=prometheus&var-cluster=&var-namespace=monitoring)
* Diplom-App will be exposed at `30001` port.