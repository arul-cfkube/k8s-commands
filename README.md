# k8s-commands

#### pod/images to debug networks 
```
kubectl  run netshoot --image=nicolaka/netshoot --rm -it --restart=Never --command -- sh
```
