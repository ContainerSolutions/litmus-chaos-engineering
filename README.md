# Chaos engineering with Litmus

TODO:

* Overview
* Architecture
* Workflow diagram
* Limitations
* Criteria table

Quick command to ping a pod to test latency:

`
kubectl -n app run -it --rm debug --image=busybox --restart=Never -- sh
`