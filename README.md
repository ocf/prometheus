# prometheus
Prometheus instance on Kubernetes

to generate the configmaps run something inside /cfg like:

`kubectl -n app-prometheus create configmap prometheus-config --from-file prometheus.yml -o yaml --dry-run > filename.yml`
