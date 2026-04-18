# Veritas InfoScale (veritas-infoscale)
APIs for Veritas InfoScale, an enterprise storage and availability management solution that provides high availability, disaster recovery, and storage management capabilities across physical, virtual, and cloud environments.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/veritas-infoscale/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Clustering, Data Management, Disaster Recovery, High Availability, Storage Management, Virtualization

## Timestamps

- **Created:** 2025-03-14
- **Modified:** 2026-04-18

## APIs

### Veritas InfoScale REST API
REST API for managing InfoScale clusters, storage resources, and high availability configurations. Supports storage configuration and management operations including disk groups, volumes, and file systems, as well as cluster configuration and management operations including service groups, resources, and heartbeats.

**Human URL:** [https://www.veritas.com/support/en_US/doc/79638609-166315478-0/v151832379-166315478](https://www.veritas.com/support/en_US/doc/79638609-166315478-0/v151832379-166315478)

#### Tags:

 - Availability, Clustering, Storage

#### Properties

- [Documentation](https://www.veritas.com/support/en_US/doc/79638609-166315478-0/v151832379-166315478)
- [OpenAPI](openapi/veritas-infoscale-rest-api.yaml)
- [Authentication](https://www.veritas.com/support/en_US/doc/79638609-166315478-0/v151837041-166315478)
- [Cluster Schema](json-schema/rest-api-cluster-schema.json)
- [Service Group Schema](json-schema/rest-api-service-group-schema.json)
- [Disk Group Schema](json-schema/rest-api-disk-group-schema.json)
- [Volume Schema](json-schema/rest-api-volume-schema.json)
- [System Schema](json-schema/rest-api-system-schema.json)
- [Alert Schema](json-schema/rest-api-alert-schema.json)
- [Cluster Structure](json-structure/rest-api-cluster-structure.json)
- [Service Group Structure](json-structure/rest-api-service-group-structure.json)
- [Disk Group Structure](json-structure/rest-api-disk-group-structure.json)
- [Volume Structure](json-structure/rest-api-volume-structure.json)
- [JSON-LD Context](json-ld/veritas-infoscale-rest-api-context.jsonld)
- [Cluster Example](examples/rest-api-cluster-example.json)
- [Service Group Example](examples/rest-api-service-group-example.json)
- [Disk Group Example](examples/rest-api-disk-group-example.json)
- [Volume Example](examples/rest-api-volume-example.json)
- [System Example](examples/rest-api-system-example.json)
- [Alert Example](examples/rest-api-alert-example.json)

### Veritas InfoScale Operations Manager API
REST API for centralized monitoring and management of InfoScale environments. Provides meta, query, update, and operational endpoints for managing clusters, service groups, hosts, storage, and extended attributes across the entire InfoScale infrastructure.

**Human URL:** [https://www.veritas.com/support/en_US/doc/120572053-156079406-0/viom_tot_v96894970-156079406](https://www.veritas.com/support/en_US/doc/120572053-156079406-0/viom_tot_v96894970-156079406)

#### Tags:

 - Management, Monitoring, Operations

#### Properties

- [Documentation](https://www.veritas.com/support/en_US/doc/120572053-156079406-0/viom_tot_v96894970-156079406)
- [API Reference](https://sort.veritas.com/public/documents/vom/7.3/windowsandunix/productguides/html/viom_user/ch38.htm)

### Veritas Cluster Server API
API for managing VCS clusters, service groups, and resources within InfoScale. Provides operations for cluster node management, service group failover and failback, resource dependency configuration, and heartbeat monitoring.

**Human URL:** [https://www.veritas.com/support/en_US/doc/79638609-166315478-0/v151832379-166315478](https://www.veritas.com/support/en_US/doc/79638609-166315478-0/v151832379-166315478)

#### Tags:

 - Clustering, Failover, High Availability

#### Properties

- [Documentation](https://www.veritas.com/support/en_US/doc/79638609-166315478-0/v151832379-166315478)
- [CLI](https://www.veritas.com/support/en_US/doc/cluster-server/cli-reference)

### Veritas Volume Manager API
API for storage volume management, including volume creation, resizing, mirroring, and snapshot operations. Manages disk groups, plexes, subdisks, and provides advanced storage features like thin provisioning, data migration, and volume replication.

**Human URL:** [https://www.veritas.com/support/en_US/doc/79638609-166315478-0/v151832379-166315478](https://www.veritas.com/support/en_US/doc/79638609-166315478-0/v151832379-166315478)

#### Tags:

 - Snapshots, Storage, Volumes

#### Properties

- [Documentation](https://www.veritas.com/support/en_US/doc/79638609-166315478-0/v151832379-166315478)
- [Getting Started](https://www.veritas.com/support/en_US/doc/volume-manager/admin-guide)

## Common Properties

- [Portal](https://my.veritas.com)
- [Support](https://www.veritas.com/support)
- [Knowledge Center](https://www.veritas.com/support/en_US/dpp.InfoScaleStorageFoundation)
- [Documentation](https://sort.veritas.com)
- [Getting Started](https://sort.veritas.com/infoscale/intro)
- [Training](https://www.veritas.com/support/training)
- [Blog](https://vox.veritas.com)
- [GitHub Organization](https://github.com/VeritasOS)
- [InfoScale Ansible Playbooks](https://github.com/VeritasOS/infoscale_ansible)
- [Terms of Service](https://www.veritas.com/company/legal/terms-of-use)
- [Privacy Policy](https://www.veritas.com/company/legal/privacy)
- [Contact](https://www.veritas.com/form/requestacall)
- [Pricing](https://sort.veritas.com/license_calc)
- [Release Notes](https://www.veritas.com/support/en_US/doc/infoscale)

## Features

| Name | Description |
|------|-------------|
| High Availability Clustering | Provides application-aware clustering with automatic failover and failback to ensure continuous availability of mission-critical applications. |
| Intelligent Monitoring Framework | Uses asynchronous event-based monitoring (IMF) to detect failures instantaneously, eliminating CPU overhead of legacy poll-based monitoring. |
| Storage Management | Software-defined storage services for volume management, thin provisioning, data migration, and multi-pathing across heterogeneous storage arrays. |
| Disaster Recovery | Volume replication (VVR) and file replication (VFR) for real-time data replication across sites with automated disaster recovery orchestration. |
| Snapshot Management | Space-optimized snapshots for backup, data analytics, forensic discovery, and point-in-time recovery without impacting production workloads. |
| Kubernetes Integration | Native CSI driver providing persistent storage on DAS and SAN with data integrity using I/O fencing for Kubernetes and OpenShift environments. |
| Cloud Deployment | Deployment on AWS, Azure, Google Cloud, and Oracle Cloud with solution templates and marketplace offerings for elastic scaling. |
| REST API Management | Full REST API support for control plane operations enabling automation and integration with DevOps pipelines and orchestration tools. |

## Use Cases

| Name | Description |
|------|-------------|
| Application High Availability | Ensure zero-downtime for mission-critical applications like Oracle, SAP, and SQL Server with automatic failover and health monitoring. |
| Disaster Recovery Automation | Automate cross-site replication and recovery orchestration to meet RPO and RTO requirements for business continuity planning. |
| Storage Consolidation | Consolidate heterogeneous storage arrays into a unified software-defined storage layer with volume management. |
| Cloud Migration | Migrate on-premises applications to cloud environments with consistent storage and availability management across hybrid infrastructure. |
| Container Storage | Provide enterprise-grade persistent storage for containerized applications on Kubernetes and OpenShift with CSI driver integration. |
| Database Protection | Protect databases with application-consistent snapshots, online data migration, and real-time replication without application downtime. |

## Integrations

| Name | Description |
|------|-------------|
| Oracle Database | Deep integration with Oracle RAC and single-instance databases for storage management, availability, and disaster recovery. |
| SAP Applications | Certified integration with SAP HANA and SAP applications for high availability and disaster recovery in enterprise environments. |
| Microsoft SQL Server | High availability and storage management for SQL Server Always On availability groups and failover cluster instances. |
| VMware vSphere | Integration with VMware vSphere and vSAN for virtualized application availability and storage management. |
| Kubernetes and OpenShift | CSI driver integration for persistent storage provisioning and management in container orchestration platforms. |
| Ansible Automation | Ansible modules for automated deployment, configuration, and management of InfoScale environments in DevOps pipelines. |
| Dell EMC Storage | SRDF MetroCluster support with Dell EMC PowerMax and vMAX arrays for storage replication and disaster recovery. |
| AWS and Azure | Cloud marketplace offerings and solution templates for deployment on Amazon Web Services and Microsoft Azure platforms. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Veritas InfoScale REST API](openapi/veritas-infoscale-rest-api.yaml)

### JSON Schema

- [Cluster Schema](json-schema/rest-api-cluster-schema.json)
- [Service Group Schema](json-schema/rest-api-service-group-schema.json)
- [Disk Group Schema](json-schema/rest-api-disk-group-schema.json)
- [Volume Schema](json-schema/rest-api-volume-schema.json)
- [System Schema](json-schema/rest-api-system-schema.json)
- [Alert Schema](json-schema/rest-api-alert-schema.json)

### JSON Structure

- [Cluster Structure](json-structure/rest-api-cluster-structure.json)
- [Service Group Structure](json-structure/rest-api-service-group-structure.json)
- [Disk Group Structure](json-structure/rest-api-disk-group-structure.json)
- [Volume Structure](json-structure/rest-api-volume-structure.json)

### JSON-LD

- [Veritas InfoScale REST API Context](json-ld/veritas-infoscale-rest-api-context.jsonld)

### Examples

- [Cluster Example](examples/rest-api-cluster-example.json)
- [Service Group Example](examples/rest-api-service-group-example.json)
- [Disk Group Example](examples/rest-api-disk-group-example.json)
- [Volume Example](examples/rest-api-volume-example.json)
- [System Example](examples/rest-api-system-example.json)
- [Alert Example](examples/rest-api-alert-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Veritas InfoScale REST API](capabilities/shared/infoscale-rest-api.yaml) -- 22 operations for cluster, service group, volume, and alert management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Infrastructure Management](capabilities/infrastructure-management.yaml) | InfoScale REST API | 16 | Infrastructure Engineer, Storage Administrator, SRE |

## Vocabulary

- [Veritas InfoScale Vocabulary](vocabulary/veritas-infoscale-vocabulary.yaml) -- Unified taxonomy mapping 8 resources, 10 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Veritas InfoScale Spectral Rules](rules/veritas-infoscale-spectral-rules.yml) -- 30 rules across 11 categories enforcing Veritas InfoScale API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
