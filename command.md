# Basic POD commands:

* kubectl get nodes
* kubectl get pods --all-namespaces
* kubectl get pods
* kubectl describe pod/hello-pod
* kubectl delete pod/hello-pod

# Basic RC(ReplicationController) commands:

* kubectl create -f rc.yml
* kubectl get rc -o wide
* kubectl describe rc
* kubectl apply -f rc.yml
* kubectl get rc
* kubectl get pods
* kubectl delete rc/hello-rc

# Basic SVC(Service) commands:

* kubectl create -f svc.yml
* kubectl apply -f svc.yml
* kubectl get svc
* kubectl describe svc hello-svc

# Basic ep(EndPoint) commands:

* kubectl get ep
* kubectl describe ep hello-svc