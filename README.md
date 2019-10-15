# prometheus-operator-k8s-demo
Setting up prometheus operator in a minikube

- install prometheus operator
- install exporter
 - install cadvisor
 - install kube-state-metrics
 - install node-exporter
 - [TODO] custom exporter

- install service monitor
  - add service monitor for cadvisor
  - add service monitor for noe-exporter
  - add service monitor for kube-state-metrics
  - [TODO] custom service monitor
- [TODO] install grafana
       - install plugins
       - add dashboard
       - add kubernetes plugin 
