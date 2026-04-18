# Azure Kubernetes Service (azure-kubernetes-service)
Azure Kubernetes Service (AKS) simplifies deploying a managed Kubernetes cluster in Azure by offloading the operational overhead to Azure. As a hosted Kubernetes service, Azure handles critical tasks, like health monitoring and maintenance.

**URL:** [Visit APIs.json URL](https://azure.microsoft.com/en-us/services/kubernetes-service/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Azure, Cloud, Containers, DevOps, Kubernetes, Orchestration

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-18

## APIs

### Azure Kubernetes Service REST API
REST API for managing Azure Kubernetes Service clusters.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/aks/](https://learn.microsoft.com/en-us/rest/api/aks/)

#### Tags:

 - Containers, Kubernetes, Management

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/aks/)
- [OpenAPI](openapi/azure-kubernetes-service-openapi.yml)
- [JSONSchema](json-schema/azure-kubernetes-service-cluster-schema.json)
- [JSONLD](json-ld/azure-kubernetes-service-context.jsonld)
- [Authentication](https://learn.microsoft.com/en-us/azure/aks/concepts-identity)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/kubernetes-service/)
- [RateLimits](https://learn.microsoft.com/en-us/azure/aks/quotas-skus-regions)
- [GettingStarted](https://learn.microsoft.com/en-us/azure/aks/learn/quick-kubernetes-deploy-portal)
- [ChangeLog](https://github.com/Azure/AKS/blob/master/CHANGELOG.md)
- [ReleaseNotes](https://learn.microsoft.com/en-us/azure/aks/release-tracker)
- [SDK - Python](https://learn.microsoft.com/en-us/python/api/overview/azure/mgmt-containerservice-readme)
- [SDK - JavaScript](https://learn.microsoft.com/en-us/javascript/api/overview/azure/container-service)
- [SDK - .NET](https://learn.microsoft.com/en-us/dotnet/api/overview/azure/resourcemanager.containerservice-readme)
- [SDK - Java](https://learn.microsoft.com/en-us/java/api/overview/azure/resourcemanager-containerservice-readme)
- [SDK - Go](https://pkg.go.dev/github.com/Azure/azure-sdk-for-go/sdk/resourcemanager/containerservice/armcontainerservice/v6)

### Azure Kubernetes Service Managed Clusters API
REST API for creating, updating, deleting, and managing AKS managed clusters.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/aks/managed-clusters](https://learn.microsoft.com/en-us/rest/api/aks/managed-clusters)

#### Tags:

 - Clusters, Kubernetes, Management

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/aks/)
- [APIReference](https://learn.microsoft.com/en-us/rest/api/aks/managed-clusters)
- [OpenAPI](openapi/azure-kubernetes-service-openapi.yml)
- [JSONSchema](json-schema/azure-kubernetes-service-cluster-schema.json)
- [JSONLD](json-ld/azure-kubernetes-service-context.jsonld)
- [Authentication](https://learn.microsoft.com/en-us/azure/aks/concepts-identity)
- [GettingStarted](https://learn.microsoft.com/en-us/azure/aks/learn/quick-kubernetes-deploy-cli)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/kubernetes-service/)

### Azure Kubernetes Service Agent Pools API
REST API for managing agent pools (node pools) within AKS managed clusters.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/aks/agent-pools](https://learn.microsoft.com/en-us/rest/api/aks/agent-pools)

#### Tags:

 - Agent Pools, Kubernetes, Node Pools

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/aks/create-node-pools)
- [APIReference](https://learn.microsoft.com/en-us/rest/api/aks/agent-pools)
- [OpenAPI](openapi/azure-kubernetes-service-openapi.yml)
- [Authentication](https://learn.microsoft.com/en-us/azure/aks/concepts-identity)
- [GettingStarted](https://learn.microsoft.com/en-us/azure/aks/create-node-pools)

### Azure Kubernetes Service Maintenance Configurations API
REST API for managing planned maintenance configurations for AKS clusters.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/aks/maintenance-configurations](https://learn.microsoft.com/en-us/rest/api/aks/maintenance-configurations)

#### Tags:

 - Configuration, Kubernetes, Maintenance

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/aks/planned-maintenance)
- [APIReference](https://learn.microsoft.com/en-us/rest/api/aks/maintenance-configurations)
- [Authentication](https://learn.microsoft.com/en-us/azure/aks/concepts-identity)

### Azure Kubernetes Service Snapshots API
REST API for managing node pool snapshots in AKS.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/aks/snapshots](https://learn.microsoft.com/en-us/rest/api/aks/snapshots)

#### Tags:

 - Backup, Kubernetes, Snapshots

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/aks/node-pool-snapshot)
- [APIReference](https://learn.microsoft.com/en-us/rest/api/aks/snapshots)
- [Authentication](https://learn.microsoft.com/en-us/azure/aks/concepts-identity)

### Azure Kubernetes Service Private Endpoint Connections API
REST API for managing private endpoint connections for AKS clusters.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/aks/private-endpoint-connections](https://learn.microsoft.com/en-us/rest/api/aks/private-endpoint-connections)

#### Tags:

 - Kubernetes, Networking, Private Endpoints

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/aks/private-clusters)
- [APIReference](https://learn.microsoft.com/en-us/rest/api/aks/private-endpoint-connections)
- [Authentication](https://learn.microsoft.com/en-us/azure/aks/concepts-identity)

### Azure Kubernetes Service Trusted Access Role Bindings API
REST API for managing trusted access role bindings for AKS clusters.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/aks/trusted-access-role-bindings](https://learn.microsoft.com/en-us/rest/api/aks/trusted-access-role-bindings)

#### Tags:

 - Kubernetes, Security, Trusted Access

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/aks/trusted-access-feature)
- [APIReference](https://learn.microsoft.com/en-us/rest/api/aks/trusted-access-role-bindings)
- [Authentication](https://learn.microsoft.com/en-us/azure/aks/concepts-identity)

### Azure Kubernetes Service kubectl API
Kubernetes API accessible via kubectl for cluster operations.

**Human URL:** [https://kubernetes.io/docs/reference/](https://kubernetes.io/docs/reference/)

#### Tags:

 - Cluster Management, Kubectl, Kubernetes

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/aks/kubernetes-walkthrough)
- [APIReference](https://kubernetes.io/docs/reference/kubernetes-api/)
- [Authentication](https://learn.microsoft.com/en-us/azure/aks/control-kubeconfig-access)
- [GettingStarted](https://learn.microsoft.com/en-us/azure/aks/tutorial-kubernetes-deploy-cluster)

## Common Properties

- [Portal](https://portal.azure.com/)
- [GettingStarted](https://learn.microsoft.com/en-us/azure/aks/learn/quick-kubernetes-deploy-portal)
- [CLI](https://learn.microsoft.com/en-us/cli/azure/aks)
- [StatusPage](https://status.azure.com/)
- [Support](https://azure.microsoft.com/en-us/support/options/)
- [Blog](https://azure.microsoft.com/en-us/blog/topics/kubernetes/)
- [GitHubRepository](https://github.com/Azure/AKS)
- [StackOverflow](https://stackoverflow.com/questions/tagged/azure-aks)
- [Security](https://learn.microsoft.com/en-us/azure/aks/concepts-security)
- [Compliance](https://learn.microsoft.com/en-us/azure/aks/concepts-security#azure-policy)
- [Documentation](https://learn.microsoft.com/en-us/azure/aks/)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/kubernetes-service/)
- [SignUp](https://azure.microsoft.com/en-us/pricing/purchase-options/azure-account)
- [Login](https://portal.azure.com/)
- [TermsOfService](https://azure.microsoft.com/en-us/support/legal/)
- [PrivacyPolicy](https://privacy.microsoft.com/en-us/privacystatement)
- [ChangeLog](https://github.com/Azure/AKS/blob/master/CHANGELOG.md)
- [ReleaseNotes](https://learn.microsoft.com/en-us/azure/aks/release-tracker)
- [FAQ](https://learn.microsoft.com/en-us/azure/aks/faq)
- [Training](https://learn.microsoft.com/en-us/training/modules/intro-to-azure-kubernetes-service/)
- [YouTube](https://www.youtube.com/c/MicrosoftAzure)

## Features

| Name | Description |
|------|-------------|
| Managed Cluster Lifecycle | Create, update, delete, start, and stop AKS managed clusters with full lifecycle management. |
| Agent Pool Management | Create and manage node pools with configurable VM sizes, scaling, and upgrade policies. |
| Cluster Upgrades | Upgrade Kubernetes versions and node images with controlled rollout and upgrade profiles. |
| Credential Management | Retrieve admin, user, and monitoring credentials for cluster access and authentication. |
| Private Clusters | Deploy private AKS clusters with private endpoint connections for secure API server access. |
| Maintenance Windows | Configure planned maintenance windows to control when updates are applied to clusters. |
| Node Pool Snapshots | Create and manage snapshots of node pools for backup and recovery scenarios. |
| Trusted Access | Grant Azure services secure access to AKS API server using managed identities and role bindings. |
| Run Commands | Execute commands on cluster nodes remotely through the AKS API without direct SSH access. |
| Auto-Scaling | Automatically scale node pools based on workload demands with configurable auto-scaler profiles. |

## Use Cases

| Name | Description |
|------|-------------|
| Microservices Deployment | Deploy and manage microservices architectures with container orchestration and service mesh capabilities. |
| CI/CD Pipelines | Integrate AKS with Azure DevOps and GitHub Actions for automated build, test, and deployment workflows. |
| Hybrid Cloud | Run Kubernetes workloads across on-premises and Azure environments with Azure Arc integration. |
| Machine Learning | Deploy and scale ML model serving infrastructure using AKS with GPU-enabled node pools. |
| Edge Computing | Deploy containerized workloads to edge locations using AKS Edge Essentials and Azure IoT. |

## Integrations

| Name | Description |
|------|-------------|
| Azure Container Registry | Pull container images from Azure Container Registry with managed identity authentication. |
| Azure Monitor | Monitor cluster health, performance, and logs with Azure Monitor and Container Insights. |
| Azure Policy | Enforce organizational standards and compliance with Azure Policy for Kubernetes. |
| Azure Active Directory | Integrate with Azure AD for cluster authentication and role-based access control. |
| Azure DevOps | Automate deployments to AKS using Azure Pipelines with native Kubernetes tasks. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Azure Kubernetes Service REST API](openapi/azure-kubernetes-service-openapi.yml)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [AKS REST API](capabilities/shared/aks-rest.yaml) — 12 operations for cluster and agent pool management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Cluster Management](capabilities/cluster-management.yaml) | AKS REST | 11 | DevOps Engineer / Platform Admin |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
