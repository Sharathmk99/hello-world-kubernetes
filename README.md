# Hellow World to test Kuberenets Cluster

It uses ngnix as base container to server static html pages

# Kubectl command

kubectl create deployment helow-world-kubernetes --image=sharathmk99/hello-world-kubernetes:latest

kubectl create service nodeport helow-world-kubernetes --tcp=80:80 