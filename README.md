# Flannel (flannel)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
