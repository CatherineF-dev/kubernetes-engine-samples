## mldiagnostics-webhook-and-operator

It provide helm charts for mldiagnostics webhook and operator, which is needed for integrating mldiagnostics SDK in GKE.


### Install injection-webhook

```bash
helm install mldiagnostics \
   --namespace=gke-diagon\
   --create-namespace \
  ./injection-webhook/chart

```


### Install connection-operator

```bash
helm install mldiagnostics \
   --namespace=gke-diagon\
   --create-namespace \
  ./connection-operator/chart
```
