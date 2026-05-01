# Flannel (flannel)
Flannel is a simple overlay network that satisfies the Kubernetes networking requirements. It runs a small single binary agent called flanneld on each host and is responsible for allocating a subnet lease to each host out of a larger preconfigured address space. Flannel does not expose its own HTTP/REST API; it stores network configuration in either the Kubernetes API or etcd directly and is managed via configuration files, kubectl, and Helm.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/flannel/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags:

 - CNI, Cloud Native, Containers, Kubernetes, Networking, Open Source, Overlay Network

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-04-28

## APIs

### Flannel
Flannel is a simple overlay network that satisfies the Kubernetes networking requirements. It allocates subnet leases to each host and provides a layer 3 IPv4 network between multiple nodes in a cluster. It is configured via the Kubernetes API or etcd and exposes no REST API of its own.

**Human URL:** [https://github.com/flannel-io/flannel](https://github.com/flannel-io/flannel)

#### Tags:

 - CNI, Containers, Kubernetes, Networking, Overlay Network

#### Properties

- [Documentation](https://github.com/flannel-io/flannel/blob/master/Documentation/kubernetes.md)
- [Getting Started](https://github.com/flannel-io/flannel/blob/master/Documentation/running.md)
- [Configuration](https://github.com/flannel-io/flannel/blob/master/Documentation/configuration.md)

## Common Properties

- [Website](https://github.com/flannel-io/flannel)
- [Documentation](https://github.com/flannel-io/flannel/blob/master/Documentation/kubernetes.md)
- [Getting Started](https://github.com/flannel-io/flannel/blob/master/Documentation/running.md)
- [GitHub Organization](https://github.com/flannel-io)
- [Helm Chart](https://flannel-io.github.io/flannel/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
