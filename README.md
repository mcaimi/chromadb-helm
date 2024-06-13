# ChromaDB Helm Chart

[![Docker Repository on Quay](https://quay.io/repository/marcocaimi/chromadb/status "Docker Repository on Quay")](https://quay.io/repository/marcocaimi/chromadb)

Run ChromaDB on Kubernetes and (hopefully) Openshift

Currently supports:

- Local Minikube
- Local or remote K3s deployments with host-path storage provider
- Runs on Openshift without persistent storage and AnyUID SCC applied to the service account

## TODO

- Properly support Openshift deployments
