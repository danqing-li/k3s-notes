# k3s-notes
### kubectl get pods --all-namespaces
展示了kubernetes集群中所有命名空间下的pod状态
```
controlplane ~ ➜  kubectl get pods --all-namespaces 
NAMESPACE     NAME                                      READY   STATUS             RESTARTS   AGE
kube-system   coredns-6799fbcd5-8z5rg                   1/1     Running            0          24m
kube-system   local-path-provisioner-84db5d44d9-q5mrz   1/1     Running            0          24m
kube-system   helm-install-traefik-crd-kvdrq            0/1     Completed          0          24m
kube-system   svclb-traefik-2ffcdc9a-mdzm4              2/2     Running            0          23m
kube-system   helm-install-traefik-mmqc7                0/1     Completed          1          24m
kube-system   traefik-f4564c4f4-zx6lp                   1/1     Running            0          23m
kube-system   metrics-server-67c658944b-2npcj           1/1     Running            0          24m
default       frontend-deployment-7b9984b987-qgz2d      0/1     ImagePullBackOff   0          7m36s
default       frontend-deployment-7b9984b987-5d65b      0/1     ImagePullBackOff   0          7m36s
default       frontend-deployment-7b9984b987-9ml4g      0/1     ImagePullBackOff   0          7m36s
default       frontend-deployment-7b9984b987-kgkdj      0/1     ImagePullBackOff   0          7m36s
```
