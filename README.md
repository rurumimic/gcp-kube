# gcp-kube

GKE

## Contents

### Create a kubernetes cluster

- [Cloud SDK](docs/01.cloud.sdk.md): CLI
- [Network](docs/02.network.md): Router, NAT
- [Kubernetes Engine](docs/03.gke.md): Kubernetes Cluster, Firewall
- [Istio](docs/04.istio.md): Istio

### Run services

- [Certificates](docs/05.certs.md): TLS
- [Database](docs/06.sql.md): Cloud SQL, Proxy, Read Replica
- [Istio Gateway](docs/07.gateway.md): Istio gateway, virtual service, health, DNS, CDN
- [SSD](docs/08.ssd.md): Storage Type
- [Elastic](docs/09.eck.md)
- [Node.js](docs/10.node.md): Backend app
- [Nginx](docs/11.nginx.md): Reverse proxy
- [ProxySQL](docs/12.proxy.sql.md)

### Deploy

```bash
kubectl apply -f deploy.yml
```

---

## Documentations

### Google Cloud

#### Services

- [Virtual Private Cloud](https://cloud.google.com/vpc/docs/vpc): a virtual version of a physical network.
- [Router](https://cloud.google.com/network-connectivity/docs/router): to dynamically exchange routes between Virtual Private Cloud (VPC) and on-premises networks by using [Border Gateway Protocol (BGP)](https://en.wikipedia.org/wiki/Border_Gateway_Protocol).
  - BGP: a standardized exterior gateway protocol 
- [Network Address Translation](https://cloud.google.com/nat/docs): software-defined [network address translation](https://en.wikipedia.org/wiki/Network_address_translation).
- [Load Balancing](https://cloud.google.com/load-balancing/docs): to put resources behind a single IP address that is externally accessible or internal to Virtual Private Cloud (VPC) network.
- [SQL](https://cloud.google.com/sql/docs): fully-managed database service with MySQL, PostgreSQL, or SQL Server.
- [Kubernetes Engine](https://cloud.google.com/kubernetes-engine/docs)
- [Anthos](https://cloud.google.com/anthos/docs)
- [Run](https://cloud.google.com/run/docs)

#### Solutions

- [Istio](https://cloud.google.com/istio): reduces complexity of managing microservice deployments by providing a uniform way to secure, connect, and monitor microservices.

#### Features

- [Identity and Access Management](https://cloud.google.com/iam/docs): create and manage permissions for Google Cloud resources.
  - [Service accounts](https://cloud.google.com/iam/docs/service-accounts): a special kind of account used by an application or a virtual machine (VM) instance, not a person.

### Open Sources

- [Istio](https://istio.io/latest/docs/concepts/what-is-istio/): [service mesh](https://en.wikipedia.org/wiki/Service_mesh).
- [ProxySQL](https://proxysql.com/documentation/): database protocol aware proxy for MySQL.
- [cert-manager](https://cert-manager.io/docs/): a native Kubernetes certificate management controller.
- [Varnish Cache](https://varnish-cache.org/docs/index.html): a web application accelerator also known as a caching HTTP reverse proxy.
- [Elastic Cloud on Kubernetes](https://www.elastic.co/guide/en/cloud-on-k8s/current/k8s-quickstart.html)
