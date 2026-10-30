# Azure Kubernetes Service

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

**Areas:** Microsoft Azure · Cloud · Containers · DevOps · Kubernetes · Container Orchestration

## Azure Kubernetes Service on APIs.io

Everything profiled for Azure Kubernetes Service is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/microsoft-azure-kubernetes-service/](https://apis.io/providers/microsoft-azure-kubernetes-service/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [Azure Kubernetes Service Maintenance Configurations API](https://apis.io/apis/microsoft-azure-kubernetes-service/azure-kubernetes-service-maintenance-configurations-api/) — REST API for managing planned maintenance configurations, used to configure when updates can be deployed to an AKS managed cluster.
- [Azure Kubernetes Service Snapshots API](https://apis.io/apis/microsoft-azure-kubernetes-service/azure-kubernetes-service-snapshots-api/) — REST API for creating, updating, deleting, and managing node pool snapshots in AKS, including listing snapshots by resource group.
- [Azure Kubernetes Service Private Endpoint Connections API](https://apis.io/apis/microsoft-azure-kubernetes-service/azure-kubernetes-service-private-endpoint-connections-api/) — REST API for managing private endpoint connections for AKS clusters, enabling secure private network access to the cluster API server.
- [Azure Kubernetes Service Trusted Access Role Bindings API](https://apis.io/apis/microsoft-azure-kubernetes-service/azure-kubernetes-service-trusted-access-role-bindings-api/) — REST API for managing trusted access role bindings that give Azure services secure access to AKS API server using system-assigned managed identities.
- [Azure Kubernetes Service Kubectl API](https://apis.io/apis/microsoft-azure-kubernetes-service/azure-kubernetes-service-kubectl-api/) — Kubernetes API accessible via kubectl for cluster operations.
- [Azure Kubernetes Service Agent Pools API](https://apis.io/apis/microsoft-azure-kubernetes-service/microsoft-azure-kubernetes-service-agent-pools-api/) — Operations for managing agent pools (node pools) within AKS clusters
- [Azure Kubernetes Service Managed Clusters API](https://apis.io/apis/microsoft-azure-kubernetes-service/microsoft-azure-kubernetes-service-managed-clusters-api/) — Operations for managing AKS managed clusters

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Arazzo workflows (10)

Multi-step workflows that chain operations into a business task.

- [Azure Kubernetes Service Add Node Pool and Poll](https://apis.io/arazzos/microsoft-azure-kubernetes-service/azure-kubernetes-service-add-node-pool-workflow/)
- [Azure Kubernetes Service Delete Node Pool Machines](https://apis.io/arazzos/microsoft-azure-kubernetes-service/azure-kubernetes-service-delete-machines-workflow/)
- [Azure Kubernetes Service Provision Cluster and Fetch Credentials](https://apis.io/arazzos/microsoft-azure-kubernetes-service/azure-kubernetes-service-provision-cluster-workflow/)
- [Azure Kubernetes Service Rotate Cluster Certificates](https://apis.io/arazzos/microsoft-azure-kubernetes-service/azure-kubernetes-service-rotate-certificates-workflow/)
- [Azure Kubernetes Service Run Command on Cluster](https://apis.io/arazzos/microsoft-azure-kubernetes-service/azure-kubernetes-service-run-command-workflow/)
- [Azure Kubernetes Service Scale Node Pool](https://apis.io/arazzos/microsoft-azure-kubernetes-service/azure-kubernetes-service-scale-node-pool-workflow/)
- [Azure Kubernetes Service Start Cluster](https://apis.io/arazzos/microsoft-azure-kubernetes-service/azure-kubernetes-service-start-cluster-workflow/)
- [Azure Kubernetes Service Stop Cluster](https://apis.io/arazzos/microsoft-azure-kubernetes-service/azure-kubernetes-service-stop-cluster-workflow/)
- [Azure Kubernetes Service Upgrade Cluster Control Plane](https://apis.io/arazzos/microsoft-azure-kubernetes-service/azure-kubernetes-service-upgrade-cluster-workflow/)
- [Azure Kubernetes Service Upgrade Node Pool Image](https://apis.io/arazzos/microsoft-azure-kubernetes-service/azure-kubernetes-service-upgrade-node-image-workflow/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Microsoft Azure Kubernetes Service Agentic Access](https://apis.io/agentic-access/microsoft-azure-kubernetes-service/microsoft-azure-kubernetes-service-agentic-access/)

#### JSON Schema (91)

The data models the API reads and writes.

- [AgentPool](https://apis.io/schemas/microsoft-azure-kubernetes-service/azure-kubernetes-service-agent-pool/)
- [AgentPoolAvailableVersions](https://apis.io/schemas/microsoft-azure-kubernetes-service/azure-kubernetes-service-agent-pool-available-versions/)
- [AgentPoolDeleteMachinesParameter](https://apis.io/schemas/microsoft-azure-kubernetes-service/azure-kubernetes-service-agent-pool-delete-machines-parameter/)
- [AgentPoolListResult](https://apis.io/schemas/microsoft-azure-kubernetes-service/azure-kubernetes-service-agent-pool-list-result/)
- [AgentPoolProperties](https://apis.io/schemas/microsoft-azure-kubernetes-service/azure-kubernetes-service-agent-pool-properties/)
- [AgentPoolUpgradeProfile](https://apis.io/schemas/microsoft-azure-kubernetes-service/azure-kubernetes-service-agent-pool-upgrade-profile/)
- [AgentPoolUpgradeSettings](https://apis.io/schemas/microsoft-azure-kubernetes-service/azure-kubernetes-service-agent-pool-upgrade-settings/)
- [CloudError](https://apis.io/schemas/microsoft-azure-kubernetes-service/azure-kubernetes-service-cloud-error/)
- [Azure Kubernetes Service Managed Cluster](https://apis.io/schemas/microsoft-azure-kubernetes-service/azure-kubernetes-service-cluster/)
- [ClusterUpgradeSettings](https://apis.io/schemas/microsoft-azure-kubernetes-service/azure-kubernetes-service-cluster-upgrade-settings/)
- [ContainerServiceLinuxProfile](https://apis.io/schemas/microsoft-azure-kubernetes-service/azure-kubernetes-service-container-service-linux-profile/)
- [ContainerServiceNetworkProfile](https://apis.io/schemas/microsoft-azure-kubernetes-service/azure-kubernetes-service-container-service-network-profile/)
- [CreationData](https://apis.io/schemas/microsoft-azure-kubernetes-service/azure-kubernetes-service-creation-data/)
- [CredentialResults](https://apis.io/schemas/microsoft-azure-kubernetes-service/azure-kubernetes-service-credential-results/)
- [ExtendedLocation](https://apis.io/schemas/microsoft-azure-kubernetes-service/azure-kubernetes-service-extended-location/)
- [ManagedCluster](https://apis.io/schemas/microsoft-azure-kubernetes-service/azure-kubernetes-service-managed-cluster/)
- [ManagedClusterAADProfile](https://apis.io/schemas/microsoft-azure-kubernetes-service/azure-kubernetes-service-managed-cluster-aad-profile/)
- [ManagedClusterAddonProfile](https://apis.io/schemas/microsoft-azure-kubernetes-service/azure-kubernetes-service-managed-cluster-addon-profile/)
- [ManagedClusterAgentPoolProfile](https://apis.io/schemas/microsoft-azure-kubernetes-service/azure-kubernetes-service-managed-cluster-agent-pool-profile/)
- [ManagedClusterAPIServerAccessProfile](https://apis.io/schemas/microsoft-azure-kubernetes-service/azure-kubernetes-service-managed-cluster-api-server-access-profile/)
- [ManagedClusterAutoScalerProfile](https://apis.io/schemas/microsoft-azure-kubernetes-service/azure-kubernetes-service-managed-cluster-auto-scaler-profile/)
- [ManagedClusterAutoUpgradeProfile](https://apis.io/schemas/microsoft-azure-kubernetes-service/azure-kubernetes-service-managed-cluster-auto-upgrade-profile/)
- [ManagedClusterAzureMonitorProfile](https://apis.io/schemas/microsoft-azure-kubernetes-service/azure-kubernetes-service-managed-cluster-azure-monitor-profile/)
- [ManagedClusterIdentity](https://apis.io/schemas/microsoft-azure-kubernetes-service/azure-kubernetes-service-managed-cluster-identity/)
- [ManagedClusterIngressProfile](https://apis.io/schemas/microsoft-azure-kubernetes-service/azure-kubernetes-service-managed-cluster-ingress-profile/)
- …and 66 more published on APIs.io

#### JSON Structure (46)

Data models expressed in JSON Structure.

- [Azure Kubernetes Service Agent Pool Available Versions Structure](https://apis.io/json-structure/microsoft-azure-kubernetes-service/azure-kubernetes-service-agent-pool-available-versions-structure/)
- [Azure Kubernetes Service Agent Pool Delete Machines Parameter Structure](https://apis.io/json-structure/microsoft-azure-kubernetes-service/azure-kubernetes-service-agent-pool-delete-machines-parameter-structure/)
- [Azure Kubernetes Service Agent Pool List Result Structure](https://apis.io/json-structure/microsoft-azure-kubernetes-service/azure-kubernetes-service-agent-pool-list-result-structure/)
- [Azure Kubernetes Service Agent Pool Properties Structure](https://apis.io/json-structure/microsoft-azure-kubernetes-service/azure-kubernetes-service-agent-pool-properties-structure/)
- [Azure Kubernetes Service Agent Pool Structure](https://apis.io/json-structure/microsoft-azure-kubernetes-service/azure-kubernetes-service-agent-pool-structure/)
- [Azure Kubernetes Service Agent Pool Upgrade Profile Structure](https://apis.io/json-structure/microsoft-azure-kubernetes-service/azure-kubernetes-service-agent-pool-upgrade-profile-structure/)
- [Azure Kubernetes Service Agent Pool Upgrade Settings Structure](https://apis.io/json-structure/microsoft-azure-kubernetes-service/azure-kubernetes-service-agent-pool-upgrade-settings-structure/)
- [Azure Kubernetes Service Cloud Error Structure](https://apis.io/json-structure/microsoft-azure-kubernetes-service/azure-kubernetes-service-cloud-error-structure/)
- [Azure Kubernetes Service Cluster Upgrade Settings Structure](https://apis.io/json-structure/microsoft-azure-kubernetes-service/azure-kubernetes-service-cluster-upgrade-settings-structure/)
- [Azure Kubernetes Service Container Service Linux Profile Structure](https://apis.io/json-structure/microsoft-azure-kubernetes-service/azure-kubernetes-service-container-service-linux-profile-structure/)
- [Azure Kubernetes Service Container Service Network Profile Structure](https://apis.io/json-structure/microsoft-azure-kubernetes-service/azure-kubernetes-service-container-service-network-profile-structure/)
- [Azure Kubernetes Service Creation Data Structure](https://apis.io/json-structure/microsoft-azure-kubernetes-service/azure-kubernetes-service-creation-data-structure/)
- [Azure Kubernetes Service Credential Results Structure](https://apis.io/json-structure/microsoft-azure-kubernetes-service/azure-kubernetes-service-credential-results-structure/)
- [Azure Kubernetes Service Extended Location Structure](https://apis.io/json-structure/microsoft-azure-kubernetes-service/azure-kubernetes-service-extended-location-structure/)
- [Azure Kubernetes Service Managed Cluster Aad Profile Structure](https://apis.io/json-structure/microsoft-azure-kubernetes-service/azure-kubernetes-service-managed-cluster-aad-profile-structure/)
- [Azure Kubernetes Service Managed Cluster Addon Profile Structure](https://apis.io/json-structure/microsoft-azure-kubernetes-service/azure-kubernetes-service-managed-cluster-addon-profile-structure/)
- [Azure Kubernetes Service Managed Cluster Agent Pool Profile Structure](https://apis.io/json-structure/microsoft-azure-kubernetes-service/azure-kubernetes-service-managed-cluster-agent-pool-profile-structure/)
- [Azure Kubernetes Service Managed Cluster Api Server Access Profile Structure](https://apis.io/json-structure/microsoft-azure-kubernetes-service/azure-kubernetes-service-managed-cluster-api-server-access-profile-structure/)
- [Azure Kubernetes Service Managed Cluster Auto Scaler Profile Structure](https://apis.io/json-structure/microsoft-azure-kubernetes-service/azure-kubernetes-service-managed-cluster-auto-scaler-profile-structure/)
- [Azure Kubernetes Service Managed Cluster Auto Upgrade Profile Structure](https://apis.io/json-structure/microsoft-azure-kubernetes-service/azure-kubernetes-service-managed-cluster-auto-upgrade-profile-structure/)
- [Azure Kubernetes Service Managed Cluster Azure Monitor Profile Structure](https://apis.io/json-structure/microsoft-azure-kubernetes-service/azure-kubernetes-service-managed-cluster-azure-monitor-profile-structure/)
- [Azure Kubernetes Service Managed Cluster Identity Structure](https://apis.io/json-structure/microsoft-azure-kubernetes-service/azure-kubernetes-service-managed-cluster-identity-structure/)
- [Azure Kubernetes Service Managed Cluster Ingress Profile Structure](https://apis.io/json-structure/microsoft-azure-kubernetes-service/azure-kubernetes-service-managed-cluster-ingress-profile-structure/)
- [Azure Kubernetes Service Managed Cluster List Result Structure](https://apis.io/json-structure/microsoft-azure-kubernetes-service/azure-kubernetes-service-managed-cluster-list-result-structure/)
- [Azure Kubernetes Service Managed Cluster Load Balancer Profile Structure](https://apis.io/json-structure/microsoft-azure-kubernetes-service/azure-kubernetes-service-managed-cluster-load-balancer-profile-structure/)
- …and 21 more published on APIs.io

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Azure Kubernetes Service Context](https://apis.io/jsonld/microsoft-azure-kubernetes-service/azure-kubernetes-service-context/)

#### Vocabulary (2)

The provider's domain terms, defined.

- [azure-kubernetes-service API Vocabulary](https://apis.io/vocabularies/microsoft-azure-kubernetes-service/azure-kubernetes-service-vocabulary/)
- [Azure Kubernetes Service Domain Vocabulary](https://apis.io/vocabularies/microsoft-azure-kubernetes-service/microsoft-azure-kubernetes-service-vocabulary/)

#### Examples (69)

Example requests and responses.

- [Azure Kubernetes Service Agent Pool Available Versions Example](https://apis.io/examples/microsoft-azure-kubernetes-service/azure-kubernetes-service-agent-pool-available-versions-example/)
- [Azure Kubernetes Service Agent Pool Delete Machines Parameter Example](https://apis.io/examples/microsoft-azure-kubernetes-service/azure-kubernetes-service-agent-pool-delete-machines-parameter-example/)
- [Azure Kubernetes Service Agent Pool Example](https://apis.io/examples/microsoft-azure-kubernetes-service/azure-kubernetes-service-agent-pool-example/)
- [Azure Kubernetes Service Agent Pool List Result Example](https://apis.io/examples/microsoft-azure-kubernetes-service/azure-kubernetes-service-agent-pool-list-result-example/)
- [Azure Kubernetes Service Agent Pool Properties Example](https://apis.io/examples/microsoft-azure-kubernetes-service/azure-kubernetes-service-agent-pool-properties-example/)
- [Azure Kubernetes Service Agent Pool Upgrade Profile Example](https://apis.io/examples/microsoft-azure-kubernetes-service/azure-kubernetes-service-agent-pool-upgrade-profile-example/)
- [Azure Kubernetes Service Agent Pool Upgrade Settings Example](https://apis.io/examples/microsoft-azure-kubernetes-service/azure-kubernetes-service-agent-pool-upgrade-settings-example/)
- [Azure Kubernetes Service Cloud Error Example](https://apis.io/examples/microsoft-azure-kubernetes-service/azure-kubernetes-service-cloud-error-example/)
- [Azure Kubernetes Service Cluster Upgrade Settings Example](https://apis.io/examples/microsoft-azure-kubernetes-service/azure-kubernetes-service-cluster-upgrade-settings-example/)
- [Azure Kubernetes Service Container Service Linux Profile Example](https://apis.io/examples/microsoft-azure-kubernetes-service/azure-kubernetes-service-container-service-linux-profile-example/)
- [Azure Kubernetes Service Container Service Network Profile Example](https://apis.io/examples/microsoft-azure-kubernetes-service/azure-kubernetes-service-container-service-network-profile-example/)
- [Azure Kubernetes Service Creation Data Example](https://apis.io/examples/microsoft-azure-kubernetes-service/azure-kubernetes-service-creation-data-example/)
- [Azure Kubernetes Service Credential Results Example](https://apis.io/examples/microsoft-azure-kubernetes-service/azure-kubernetes-service-credential-results-example/)
- [Azure Kubernetes Service Extended Location Example](https://apis.io/examples/microsoft-azure-kubernetes-service/azure-kubernetes-service-extended-location-example/)
- [Azure Kubernetes Service Managed Cluster Aad Profile Example](https://apis.io/examples/microsoft-azure-kubernetes-service/azure-kubernetes-service-managed-cluster-aad-profile-example/)
- [Azure Kubernetes Service Managed Cluster Addon Profile Example](https://apis.io/examples/microsoft-azure-kubernetes-service/azure-kubernetes-service-managed-cluster-addon-profile-example/)
- [Azure Kubernetes Service Managed Cluster Agent Pool Profile Example](https://apis.io/examples/microsoft-azure-kubernetes-service/azure-kubernetes-service-managed-cluster-agent-pool-profile-example/)
- [Azure Kubernetes Service Managed Cluster Api Server Access Profile Example](https://apis.io/examples/microsoft-azure-kubernetes-service/azure-kubernetes-service-managed-cluster-api-server-access-profile-example/)
- [Azure Kubernetes Service Managed Cluster Auto Scaler Profile Example](https://apis.io/examples/microsoft-azure-kubernetes-service/azure-kubernetes-service-managed-cluster-auto-scaler-profile-example/)
- [Azure Kubernetes Service Managed Cluster Auto Upgrade Profile Example](https://apis.io/examples/microsoft-azure-kubernetes-service/azure-kubernetes-service-managed-cluster-auto-upgrade-profile-example/)
- [Azure Kubernetes Service Managed Cluster Azure Monitor Profile Example](https://apis.io/examples/microsoft-azure-kubernetes-service/azure-kubernetes-service-managed-cluster-azure-monitor-profile-example/)
- [Azure Kubernetes Service Managed Cluster Example](https://apis.io/examples/microsoft-azure-kubernetes-service/azure-kubernetes-service-managed-cluster-example/)
- [Azure Kubernetes Service Managed Cluster Identity Example](https://apis.io/examples/microsoft-azure-kubernetes-service/azure-kubernetes-service-managed-cluster-identity-example/)
- [Azure Kubernetes Service Managed Cluster Ingress Profile Example](https://apis.io/examples/microsoft-azure-kubernetes-service/azure-kubernetes-service-managed-cluster-ingress-profile-example/)
- [Azure Kubernetes Service Managed Cluster List Result Example](https://apis.io/examples/microsoft-azure-kubernetes-service/azure-kubernetes-service-managed-cluster-list-result-example/)
- …and 44 more published on APIs.io

#### Collections (4)

Postman and Open Collection request collections.

- [Azure Kubernetes Service REST API](https://apis.io/collections/microsoft-azure-kubernetes-service/open-azure-kubernetes-service/)
- [Azure Kubernetes Service REST Agent Pools API](https://apis.io/collections/microsoft-azure-kubernetes-service/open-microsoft-azure-kubernetes-service-agent-pools-api/)
- [Azure Kubernetes Service REST Agent Pools Managed Clusters API](https://apis.io/collections/microsoft-azure-kubernetes-service/open-microsoft-azure-kubernetes-service-managed-clusters-api/)
- [Azure Kubernetes Service REST API](https://apis.io/collections/microsoft-azure-kubernetes-service/postman-azure-kubernetes-service/)

#### Overlays (2)

OpenAPI overlays, including conversational phrasing for each operation.

- [Microsoft Azure Kubernetes Service Agent Pools Api Phrasing Overlay](https://apis.io/overlays/microsoft-azure-kubernetes-service/microsoft-azure-kubernetes-service-agent-pools-api-phrasing-overlay/)
- [Microsoft Azure Kubernetes Service Managed Clusters Api Phrasing Overlay](https://apis.io/overlays/microsoft-azure-kubernetes-service/microsoft-azure-kubernetes-service-managed-clusters-api-phrasing-overlay/)

#### Governance rules (3)

Spectral rulesets for the provider's contracts.

- [Azure Kubernetes Service — azure kubernetes service rules](https://apis.io/rules/microsoft-azure-kubernetes-service/azure-kubernetes-service-spectral-rules/)
- [Azure Kubernetes Service — jsonschema rules](https://apis.io/rules/microsoft-azure-kubernetes-service/microsoft-azure-kubernetes-service-jsonschema-spectral-rules/)
- [Azure Kubernetes Service API Rules](https://apis.io/rules/microsoft-azure-kubernetes-service/microsoft-azure-kubernetes-service-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Microsoft Azure Kubernetes Service Authentication](https://apis.io/security/microsoft-azure-kubernetes-service/microsoft-azure-kubernetes-service-authentication/)
- [Microsoft Azure Kubernetes Service Domain Security](https://apis.io/security/microsoft-azure-kubernetes-service/microsoft-azure-kubernetes-service-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Microsoft Azure Kubernetes Service Scopes](https://apis.io/scopes/microsoft-azure-kubernetes-service/microsoft-azure-kubernetes-service-scopes/)

#### Plans and pricing (2)

Published plans, tiers and prices.

- [Azure Kubernetes Service Plans Pricing](https://apis.io/plans/microsoft-azure-kubernetes-service/azure-kubernetes-service-plans-pricing/)
- [Microsoft Azure Kubernetes Service Plans Pricing](https://apis.io/plans/microsoft-azure-kubernetes-service/microsoft-azure-kubernetes-service-plans-pricing/)

#### Rate limits (2)

Published request limits.

- [Azure Kubernetes Service Rate Limits](https://apis.io/rate-limits/microsoft-azure-kubernetes-service/azure-kubernetes-service-rate-limits/)
- [Microsoft Azure Kubernetes Service Rate Limits](https://apis.io/rate-limits/microsoft-azure-kubernetes-service/microsoft-azure-kubernetes-service-rate-limits/)

#### FinOps (2)

What the API costs to run, by operation.

- [Azure Kubernetes Service Finops](https://apis.io/finops/microsoft-azure-kubernetes-service/azure-kubernetes-service-finops/)
- [Microsoft Azure Kubernetes Service Finops](https://apis.io/finops/microsoft-azure-kubernetes-service/microsoft-azure-kubernetes-service-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.microsoft.com/)
- [Documentation](https://learn.microsoft.com/en-us/azure/aks/)
- [Getting started](https://learn.microsoft.com/en-us/azure/aks/learn/quick-kubernetes-deploy-portal)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/kubernetes-service/)
- [Support](https://azure.microsoft.com/en-us/support/options/)
- [Changelog](https://github.com/Azure/AKS/blob/master/CHANGELOG.md)
- [Blog](https://azure.microsoft.com/en-us/blog/topics/kubernetes/)
- [Security](https://learn.microsoft.com/en-us/azure/aks/concepts-security)
- [Compliance](https://learn.microsoft.com/en-us/azure/aks/concepts-security#azure-policy)
- [Terms of service](https://azure.microsoft.com/en-us/support/legal/)
- [Privacy policy](https://privacy.microsoft.com/en-us/privacystatement)
- [Status](https://status.azure.com/)

## API Evangelist rating

**Kin Score 68.4** — exemplar · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 57.9 |
| Contract governance | 13.6 |
| Operational transparency | 55.3 |
| Developer ergonomics | 82.1 |
| Access clarity | 60.5 |

**Agent readiness 28.9** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | verified |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 39.2** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/microsoft-azure-kubernetes-service/](https://apis.io/providers/microsoft-azure-kubernetes-service/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Azure Kubernetes Service: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/microsoft-azure-kubernetes-service/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
