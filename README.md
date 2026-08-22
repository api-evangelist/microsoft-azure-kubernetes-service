# Azure Kubernetes Service (azure-kubernetes-service)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Azure Kubernetes Service (AKS) simplifies deploying a managed Kubernetes cluster in Azure by offloading the operational overhead to Azure. As a hosted Kubernetes service, Azure handles critical tasks, like health monitoring and maintenance.

**APIs.json:** [https://azure.microsoft.com/en-us/services/kubernetes-service/](https://azure.microsoft.com/en-us/services/kubernetes-service/)

## Tags

- Azure
- Cloud
- Containers
- DevOps
- Kubernetes
- Orchestration

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-19

## APIs

### Azure Kubernetes Service REST API

REST API for managing Azure Kubernetes Service clusters.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/aks/](https://learn.microsoft.com/en-us/rest/api/aks/)
- **Base URL:** `https://management.azure.com`

#### Tags

- Containers
- Kubernetes
- Management

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/aks/)
- [OpenAPI](openapi/azure-kubernetes-service-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-kubernetes-service.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-kubernetes-service.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/azure-kubernetes-service-cluster-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/azure-kubernetes-service-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Authentication](https://learn.microsoft.com/en-us/azure/aks/concepts-identity)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/kubernetes-service/)
- [Rate Limits](https://learn.microsoft.com/en-us/azure/aks/quotas-skus-regions)
- [Getting Started](https://learn.microsoft.com/en-us/azure/aks/learn/quick-kubernetes-deploy-portal)
- [Changelog](https://github.com/Azure/AKS/blob/master/CHANGELOG.md)
- [Release Notes](https://learn.microsoft.com/en-us/azure/aks/release-tracker)
- [SDK](https://learn.microsoft.com/en-us/python/api/overview/azure/mgmt-containerservice-readme)
- [SDK](https://learn.microsoft.com/en-us/javascript/api/overview/azure/container-service)
- [SDK](https://learn.microsoft.com/en-us/dotnet/api/overview/azure/resourcemanager.containerservice-readme)
- [SDK](https://learn.microsoft.com/en-us/java/api/overview/azure/resourcemanager-containerservice-readme)
- [SDK](https://pkg.go.dev/github.com/Azure/azure-sdk-for-go/sdk/resourcemanager/containerservice/armcontainerservice/v6)

### Azure Kubernetes Service Managed Clusters API

REST API for creating, updating, deleting, and managing AKS managed clusters including cluster configuration, upgrades, credentials, and run commands.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/aks/managed-clusters](https://learn.microsoft.com/en-us/rest/api/aks/managed-clusters)
- **Base URL:** `https://management.azure.com`

#### Tags

- Clusters
- Kubernetes
- Management

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/aks/)
- [API Reference](https://learn.microsoft.com/en-us/rest/api/aks/managed-clusters)
- [OpenAPI](openapi/azure-kubernetes-service-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-kubernetes-service.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-kubernetes-service.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/azure-kubernetes-service-cluster-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/azure-kubernetes-service-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Authentication](https://learn.microsoft.com/en-us/azure/aks/concepts-identity)
- [Getting Started](https://learn.microsoft.com/en-us/azure/aks/learn/quick-kubernetes-deploy-cli)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/kubernetes-service/)

### Azure Kubernetes Service Agent Pools API

REST API for creating, updating, deleting, and managing agent pools (node pools) within AKS managed clusters, including scaling and configuration.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/aks/agent-pools](https://learn.microsoft.com/en-us/rest/api/aks/agent-pools)
- **Base URL:** `https://management.azure.com`

#### Tags

- Agent Pools
- Kubernetes
- Node Pools

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/aks/create-node-pools)
- [API Reference](https://learn.microsoft.com/en-us/rest/api/aks/agent-pools)
- [OpenAPI](openapi/azure-kubernetes-service-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-kubernetes-service.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-kubernetes-service.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/azure-kubernetes-service-cluster-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Authentication](https://learn.microsoft.com/en-us/azure/aks/concepts-identity)
- [Getting Started](https://learn.microsoft.com/en-us/azure/aks/create-node-pools)

### Azure Kubernetes Service Maintenance Configurations API

REST API for managing planned maintenance configurations, used to configure when updates can be deployed to an AKS managed cluster.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/aks/maintenance-configurations](https://learn.microsoft.com/en-us/rest/api/aks/maintenance-configurations)
- **Base URL:** `https://management.azure.com`

#### Tags

- Configuration
- Kubernetes
- Maintenance

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/aks/planned-maintenance)
- [API Reference](https://learn.microsoft.com/en-us/rest/api/aks/maintenance-configurations)
- [Authentication](https://learn.microsoft.com/en-us/azure/aks/concepts-identity)
- [Postman Collection](collections/azure-kubernetes-service.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-kubernetes-service.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Kubernetes Service Snapshots API

REST API for creating, updating, deleting, and managing node pool snapshots in AKS, including listing snapshots by resource group.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/aks/snapshots](https://learn.microsoft.com/en-us/rest/api/aks/snapshots)
- **Base URL:** `https://management.azure.com`

#### Tags

- Backup
- Kubernetes
- Snapshots

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/aks/node-pool-snapshot)
- [API Reference](https://learn.microsoft.com/en-us/rest/api/aks/snapshots)
- [Authentication](https://learn.microsoft.com/en-us/azure/aks/concepts-identity)
- [Postman Collection](collections/azure-kubernetes-service.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-kubernetes-service.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Kubernetes Service Private Endpoint Connections API

REST API for managing private endpoint connections for AKS clusters, enabling secure private network access to the cluster API server.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/aks/private-endpoint-connections](https://learn.microsoft.com/en-us/rest/api/aks/private-endpoint-connections)
- **Base URL:** `https://management.azure.com`

#### Tags

- Kubernetes
- Networking
- Private Endpoints

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/aks/private-clusters)
- [API Reference](https://learn.microsoft.com/en-us/rest/api/aks/private-endpoint-connections)
- [Authentication](https://learn.microsoft.com/en-us/azure/aks/concepts-identity)
- [Postman Collection](collections/azure-kubernetes-service.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-kubernetes-service.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Kubernetes Service Trusted Access Role Bindings API

REST API for managing trusted access role bindings that give Azure services secure access to AKS API server using system-assigned managed identities.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/aks/trusted-access-role-bindings](https://learn.microsoft.com/en-us/rest/api/aks/trusted-access-role-bindings)
- **Base URL:** `https://management.azure.com`

#### Tags

- Kubernetes
- Security
- Trusted Access

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/aks/trusted-access-feature)
- [API Reference](https://learn.microsoft.com/en-us/rest/api/aks/trusted-access-role-bindings)
- [Authentication](https://learn.microsoft.com/en-us/azure/aks/concepts-identity)
- [Postman Collection](collections/azure-kubernetes-service.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-kubernetes-service.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Kubernetes Service kubectl API

Kubernetes API accessible via kubectl for cluster operations.

- **Human URL:** [https://kubernetes.io/docs/reference/](https://kubernetes.io/docs/reference/)
- **Base URL:** `https://{cluster-name}.{region}.azmk8s.io`

#### Tags

- Cluster Management
- Kubectl
- Kubernetes

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/aks/kubernetes-walkthrough)
- [API Reference](https://kubernetes.io/docs/reference/kubernetes-api/)
- [Authentication](https://learn.microsoft.com/en-us/azure/aks/control-kubeconfig-access)
- [Getting Started](https://learn.microsoft.com/en-us/azure/aks/tutorial-kubernetes-deploy-cluster)
- [Postman Collection](collections/azure-kubernetes-service.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-kubernetes-service.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Portal](https://portal.azure.com/)
- [Getting Started](https://learn.microsoft.com/en-us/azure/aks/learn/quick-kubernetes-deploy-portal)
- [C L I](https://learn.microsoft.com/en-us/cli/azure/aks)
- [Status Page](https://status.azure.com/)
- [Support](https://azure.microsoft.com/en-us/support/options/)
- [Blog](https://azure.microsoft.com/en-us/blog/topics/kubernetes/)
- [GitHub Repository](https://github.com/Azure/AKS)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/azure-aks)
- [Security](https://learn.microsoft.com/en-us/azure/aks/concepts-security)
- [Compliance](https://learn.microsoft.com/en-us/azure/aks/concepts-security#azure-policy)
- [Documentation](https://learn.microsoft.com/en-us/azure/aks/)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/kubernetes-service/)
- [Sign Up](https://azure.microsoft.com/en-us/pricing/purchase-options/azure-account)
- [Login](https://portal.azure.com/)
- [Terms of Service](https://azure.microsoft.com/en-us/support/legal/)
- [Privacy Policy](https://privacy.microsoft.com/en-us/privacystatement)
- [Changelog](https://github.com/Azure/AKS/blob/master/CHANGELOG.md)
- [Release Notes](https://learn.microsoft.com/en-us/azure/aks/release-tracker)
- [F A Q](https://learn.microsoft.com/en-us/azure/aks/faq)
- [Training](https://learn.microsoft.com/en-us/training/modules/intro-to-azure-kubernetes-service/)
- [YouTube](https://www.youtube.com/c/MicrosoftAzure)
- [Spectral Rules](rules/azure-kubernetes-service-spectral-rules.yml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
