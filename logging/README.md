# Cluster Logging

The following commands will deploy cluster logging components on OpenShift. See also the [Logging documentation](https://docs.openshift.com/container-platform/latest/logging/cluster-logging.html).

```
$ oc apply --kustomize elasticsearch-operator/base
```
```
$ oc apply --kustomize cluster-logging-operator/base
```
```
$ oc apply --kustomize cluster-logging-instance/base
```