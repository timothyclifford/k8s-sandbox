# k8s-sandbox

## Install a cluster locally - minikube or kind

https://kubernetes.io/docs/tasks/tools/

## Install an NGINX ingress controller

- [minikube](https://kubernetes.io/docs/tasks/access-application-cluster/ingress-minikube/)
- [kind](https://kind.sigs.k8s.io/docs/user/ingress/)

## Set default context

`kubectl config get-contexts`

`kubectl config set-context CONTEXT_NAME`

## Create apps

`kubectl apply -f app-bar.yaml`

`kubectl apply -f app-foo.yaml`

## View logs for a pod

`kubectl logs POD_NAME`

## Create an ingress

`kubectl apply -f ingress.yaml`

## Play around with CLI

Try `describe`, `edit`, `delete` resources or maybe install [k9s](https://k9scli.io/) 

[kubectl cheat sheet](https://kubernetes.io/docs/reference/kubectl/cheatsheet/)