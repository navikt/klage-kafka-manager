Usage:

Dev:
```
kubectl config use-context dev-gcp
kubectl apply -f klage-kafka-manager-dev.yaml -n klage
```
Kafka-manager available at https://klage-kafka-manager.dev.intern.nav.no/index.html

Prod:

```
kubectl config use-context prod-gcp
kubectl apply -f klage-kafka-manager-prod.yaml -n klage
```
Kafka-manager available at https://klage-kafka-manager.intern.nav.no/index.html


Contact: #team-digital-klage