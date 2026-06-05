# Azure Kubernetes Service (azure-kubernetes-service)

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
