# FreeTakServer Helm Chart

Helm chart for freetakserver.

## Prerequisites
  * Kubernetes 1.20+
  * PV provisioner support in the underlying infrastructure

## Installing the Chart

Add the repository:
```sh
helm repo add freetak https://kgrubb.github.io/helm-chart-freetak/
```

Install the package:
```sh
helm install freetak freetak/freetak
```
