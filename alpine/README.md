# jefferyb/openshift-alpine

Official Alpine Docker image using OpenShift specific guidelines, built to run on Openshift/Kubernetes/Docker environment.

## Using Openshift CLI

```bash
# Deploy Alpine
$ oc new-app --name=alpine jefferyb/openshift-alpine
```

## Using Kubernetes CLI

```bash
# Deploy Alpine
$ kubectl run alpine --image=jefferyb/openshift-alpine
```

## Using Docker

```bash
# Deploy Alpine
$ docker run -itd --name alpine jefferyb/openshift-alpine
```
