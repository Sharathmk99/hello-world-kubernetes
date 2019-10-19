# Hellow World to test Kuberenets Cluster

It uses ngnix as base container to server static html pages

# Kubectl command

kubectl create deployment hellow-world-kubernetes --image=sharathmk99/hello-world-kubernetes:latest

kubectl create service nodeport hellow-world-kubernetes --tcp=80:80 