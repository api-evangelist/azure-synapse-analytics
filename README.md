# Azure Synapse Analytics (microsoft-azure-synapse-analytics)

Azure Synapse Analytics is an enterprise analytics service that accelerates time to insight across data warehouses and big data systems. It brings together the best of SQL technologies used in enterprise data warehousing, Spark technologies for big data, and Pipelines for data integration and ETL/ELT.

**APIs.json:** [https://azure.microsoft.com/en-us/services/synapse-analytics/](https://azure.microsoft.com/en-us/services/synapse-analytics/)

## Tags

- Analytics
- Apache Spark
- Big Data
- Data Integration
- Data Warehouse
- ETL
- SQL

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Synapse Workspace API

Manage Synapse workspaces including creation, configuration, and lifecycle management of analytics environments through Azure Resource Manager.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/](https://learn.microsoft.com/en-us/rest/api/synapse/)
- **Base URL:** `https://management.azure.com`

#### Tags

- Management
- Resource Manager
- Workspace

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/synapse/workspace)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/synapse/resource-manager/Microsoft.Synapse/stable/2021-06-01/workspace.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Swagger](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/synapse/resource-manager/Microsoft.Synapse/stable/2021-06-01/workspace.json)
- [OpenAPI](openapi/azure-synapse-analytics-workspace-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-synapse-analytics-workspace.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-synapse-analytics-workspace.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/azure-synapse-analytics-workspace-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/azure-synapse-analytics-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Synapse SQL Pools API

Manage dedicated SQL pools for enterprise data warehousing workloads including provisioning, scaling, pausing, and resuming compute resources.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/sqlpools](https://learn.microsoft.com/en-us/rest/api/synapse/sqlpools)
- **Base URL:** `https://management.azure.com`

#### Tags

- Data Warehouse
- Resource Manager
- SQL Pool

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/synapse/sqlpools)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/synapse/resource-manager/Microsoft.Synapse/stable/2021-06-01/sqlPool.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-synapse-analytics-sql-pools-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-synapse-analytics-sql-pools.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-synapse-analytics-sql-pools.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/azure-synapse-analytics-sql-pool-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/azure-synapse-analytics-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Synapse Spark Pools API

Manage Apache Spark pools for big data processing including pool creation, auto-scaling configuration, and Spark runtime version management.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/bigdatapool](https://learn.microsoft.com/en-us/rest/api/synapse/bigdatapool)
- **Base URL:** `https://management.azure.com`

#### Tags

- Apache Spark
- Big Data
- Resource Manager
- Spark

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/synapse/bigdatapool)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/synapse/resource-manager/Microsoft.Synapse/stable/2021-06-01/bigDataPool.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-synapse-analytics-spark-pools-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-synapse-analytics-spark-pools.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-synapse-analytics-spark-pools.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/azure-synapse-analytics-spark-pool-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/azure-synapse-analytics-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Synapse Pipeline API

Create and manage data integration pipelines for ETL/ELT workflows. Supports orchestrating data movement and transformation activities across diverse data stores.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/pipeline](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/pipeline)
- **Base URL:** `https://{workspaceName}.dev.azuresynapse.net`

#### Tags

- Data Integration
- Data Plane
- ETL
- Pipeline

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/pipeline)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/synapse/data-plane/Microsoft.Synapse/stable/2020-12-01/artifacts.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-synapse-analytics-pipeline-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-synapse-analytics-pipeline.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-synapse-analytics-pipeline.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/azure-synapse-analytics-pipeline-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/azure-synapse-analytics-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Synapse Spark Job API

Submit and manage Apache Spark batch jobs and interactive sessions. Provides operations for monitoring job status, retrieving logs, and cancelling running applications.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/spark](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/spark)
- **Base URL:** `https://{workspaceName}.dev.azuresynapse.net`

#### Tags

- Batch Processing
- Data Plane
- Spark Jobs

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/spark)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/synapse/data-plane/Microsoft.Synapse/stable/2019-11-01-preview/sparkJob.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-synapse-analytics-spark-job-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-synapse-analytics-spark-job.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-synapse-analytics-spark-job.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/azure-synapse-analytics-spark-batch-job-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/azure-synapse-analytics-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Synapse Monitoring API

Monitor pipeline runs, Spark jobs, and SQL requests within a Synapse workspace. Provides visibility into execution status, performance metrics, and operational health.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/monitoring](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/monitoring)
- **Base URL:** `https://{workspaceName}.dev.azuresynapse.net`

#### Tags

- Data Plane
- Monitoring
- Observability

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/monitoring)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/synapse/data-plane/Microsoft.Synapse/stable/2020-12-01/monitoring.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-synapse-analytics-monitoring-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-synapse-analytics-monitoring.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-synapse-analytics-monitoring.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/azure-synapse-analytics-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Synapse Link API

Manage Azure Synapse Link for real-time analytics over operational data. Enables hybrid transactional and analytical processing without impacting operational workloads.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/synapse-analytics/synapse-link/](https://learn.microsoft.com/en-us/azure/synapse-analytics/synapse-link/)
- **Base URL:** `https://management.azure.com`

#### Tags

- HTAP
- Real-Time Analytics
- Synapse Link

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/synapse-analytics/synapse-link/)
- [OpenAPI](openapi/azure-synapse-analytics-synapse-link-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-synapse-analytics-synapse-link.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-synapse-analytics-synapse-link.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/azure-synapse-analytics-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Synapse Access Control API

Manage role assignments, role definitions, and access control for Synapse workspace resources. Supports Synapse role-based access control for fine-grained permissions.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/role-assignments](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/role-assignments)
- **Base URL:** `https://{workspaceName}.dev.azuresynapse.net`

#### Tags

- Access Control
- Data Plane
- RBAC
- Security

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/role-assignments)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/synapse/data-plane/Microsoft.Synapse/stable/2020-12-01/roleAssignments.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-synapse-analytics-access-control-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-synapse-analytics-access-control.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-synapse-analytics-access-control.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/azure-synapse-analytics-role-assignment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/azure-synapse-analytics-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Synapse Notebook API

Create, update, list, and delete notebooks within a Synapse workspace. Notebooks support interactive data exploration using Python, Scala, SQL, and .NET languages.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/notebook](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/notebook)
- **Base URL:** `https://{workspaceName}.dev.azuresynapse.net`

#### Tags

- Artifacts
- Data Exploration
- Data Plane
- Notebook

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/notebook)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/synapse/data-plane/Microsoft.Synapse/stable/2020-12-01/artifacts.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-synapse-analytics-notebook-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-synapse-analytics-notebook.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-synapse-analytics-notebook.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/azure-synapse-analytics-notebook-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/azure-synapse-analytics-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Synapse Dataset API

Create and manage datasets that represent data structures within linked data stores. Datasets define the schema and location of data used in pipelines and data flows.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/dataset](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/dataset)
- **Base URL:** `https://{workspaceName}.dev.azuresynapse.net`

#### Tags

- Artifacts
- Data Management
- Data Plane
- Dataset

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/dataset)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/synapse/data-plane/Microsoft.Synapse/stable/2020-12-01/artifacts.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-synapse-analytics-dataset-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-synapse-analytics-dataset.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-synapse-analytics-dataset.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/azure-synapse-analytics-dataset-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/azure-synapse-analytics-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Synapse Linked Service API

Create and manage linked services that define connection information to external data sources. Linked services act as connection strings for integrating with databases, storage, and other services.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/linked-service](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/linked-service)
- **Base URL:** `https://{workspaceName}.dev.azuresynapse.net`

#### Tags

- Connectivity
- Data Integration
- Data Plane
- Linked Service

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/linked-service)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/synapse/data-plane/Microsoft.Synapse/stable/2020-12-01/artifacts.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-synapse-analytics-linked-service-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-synapse-analytics-linked-service.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-synapse-analytics-linked-service.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/azure-synapse-analytics-linked-service-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/azure-synapse-analytics-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Synapse Data Flow API

Create and manage data flows for visual data transformation logic. Data flows enable code-free data transformation at scale within Synapse pipelines.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/data-flow](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/data-flow)
- **Base URL:** `https://{workspaceName}.dev.azuresynapse.net`

#### Tags

- Data Flow
- Data Plane
- Data Transformation
- ETL

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/data-flow)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/synapse/data-plane/Microsoft.Synapse/stable/2020-12-01/artifacts.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-synapse-analytics-data-flow-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-synapse-analytics-data-flow.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-synapse-analytics-data-flow.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/azure-synapse-analytics-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Synapse SQL Script API

Create, update, list, and delete SQL scripts within a Synapse workspace. SQL scripts can target both dedicated and serverless SQL pools for querying and data management.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/sql-script](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/sql-script)
- **Base URL:** `https://{workspaceName}.dev.azuresynapse.net`

#### Tags

- Artifacts
- Data Plane
- SQL
- SQL Script

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/sql-script)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/synapse/data-plane/Microsoft.Synapse/stable/2020-12-01/artifacts.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-synapse-analytics-sql-script-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-synapse-analytics-sql-script.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-synapse-analytics-sql-script.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/azure-synapse-analytics-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Synapse Trigger API

Create and manage triggers that orchestrate pipeline execution. Supports schedule-based, tumbling window, and event-based triggers for automated workflow execution.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/trigger](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/trigger)
- **Base URL:** `https://{workspaceName}.dev.azuresynapse.net`

#### Tags

- Automation
- Data Plane
- Scheduling
- Trigger

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/trigger)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/synapse/data-plane/Microsoft.Synapse/stable/2020-12-01/artifacts.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-synapse-analytics-trigger-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-synapse-analytics-trigger.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-synapse-analytics-trigger.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/azure-synapse-analytics-trigger-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/azure-synapse-analytics-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Synapse Spark Job Definition API

Create and manage Spark job definitions as reusable templates for batch processing. Spark job definitions encapsulate configuration, code, and dependencies for repeatable execution.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/spark-job-definition](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/spark-job-definition)
- **Base URL:** `https://{workspaceName}.dev.azuresynapse.net`

#### Tags

- Artifacts
- Batch Processing
- Data Plane
- Spark Job Definition

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/spark-job-definition)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/synapse/data-plane/Microsoft.Synapse/stable/2020-12-01/artifacts.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-synapse-analytics-spark-job-definition-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-synapse-analytics-spark-job-definition.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-synapse-analytics-spark-job-definition.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/azure-synapse-analytics-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Synapse Managed Private Endpoints API

Create and manage managed private endpoints within a Synapse managed virtual network. Enables secure, private connectivity to Azure resources without exposing traffic to the public internet.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/managed-private-endpoints](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/managed-private-endpoints)
- **Base URL:** `https://{workspaceName}.dev.azuresynapse.net`

#### Tags

- Data Plane
- Networking
- Private Endpoints
- Security

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/managed-private-endpoints)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/synapse/data-plane/Microsoft.Synapse/preview/2021-06-01-preview/managedPrivateEndpoints.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-synapse-analytics-managed-private-endpoints-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-synapse-analytics-managed-private-endpoints.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-synapse-analytics-managed-private-endpoints.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/azure-synapse-analytics-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Synapse Integration Runtimes API

Manage integration runtimes that provide the compute infrastructure for data integration activities. Supports Azure-hosted, self-hosted, and Azure-SSIS integration runtime types.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/integration-runtimes](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/integration-runtimes)
- **Base URL:** `https://{workspaceName}.dev.azuresynapse.net`

#### Tags

- Compute
- Data Integration
- Data Plane
- Integration Runtime

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/integration-runtimes)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/synapse/data-plane/Microsoft.Synapse/stable/2020-12-01/artifacts.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-synapse-analytics-integration-runtimes-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-synapse-analytics-integration-runtimes.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-synapse-analytics-integration-runtimes.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/azure-synapse-analytics-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Synapse Library API

Manage workspace libraries including JAR files, Python wheels, and other packages used by Spark pools. Supports uploading, listing, and deleting library resources.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/library](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/library)
- **Base URL:** `https://{workspaceName}.dev.azuresynapse.net`

#### Tags

- Data Plane
- Library
- Package Management
- Spark

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/library)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/synapse/data-plane/Microsoft.Synapse/stable/2020-12-01/artifacts.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-synapse-analytics-library-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-synapse-analytics-library.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-synapse-analytics-library.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/azure-synapse-analytics-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Synapse Git Integration API

Manage Git repository integration for Synapse workspaces. Enables source control for workspace artifacts including pipelines, notebooks, and data flows through Git-based version control.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/git-integration](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/git-integration)
- **Base URL:** `https://{workspaceName}.dev.azuresynapse.net`

#### Tags

- Data Plane
- DevOps
- Git Integration
- Source Control

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/git-integration)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/synapse/data-plane/Microsoft.Synapse/stable/2020-12-01/gitintegration.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-synapse-analytics-git-integration-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-synapse-analytics-git-integration.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-synapse-analytics-git-integration.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/azure-synapse-analytics-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Synapse Firewall Rules API

Manage IP firewall rules for Synapse workspaces to control network access. Supports creating, updating, and deleting server-level IP firewall rules for workspace security.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/ip-firewall-rules](https://learn.microsoft.com/en-us/rest/api/synapse/ip-firewall-rules)
- **Base URL:** `https://management.azure.com`

#### Tags

- Firewall Rules
- Network Security
- Resource Manager

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/synapse/ip-firewall-rules)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/synapse/resource-manager/Microsoft.Synapse/stable/2021-06-01/firewallRule.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-synapse-analytics-firewall-rules-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-synapse-analytics-firewall-rules.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-synapse-analytics-firewall-rules.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/azure-synapse-analytics-firewall-rule-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/azure-synapse-analytics-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Synapse Keys API

Manage workspace encryption keys for data protection at rest. Supports customer-managed key configuration for dedicated SQL pools and workspace-level encryption.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/keys](https://learn.microsoft.com/en-us/rest/api/synapse/keys)
- **Base URL:** `https://management.azure.com`

#### Tags

- Encryption Keys
- Resource Manager
- Security

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/synapse/keys)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/synapse/resource-manager/Microsoft.Synapse/stable/2021-06-01/keys.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-synapse-analytics-keys-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-synapse-analytics-keys.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-synapse-analytics-keys.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/azure-synapse-analytics-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Synapse Private Endpoint Connections API

Manage private endpoint connections to Synapse workspaces. Enables approval and management of private link connections for secure access from virtual networks.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/private-endpoint-connections](https://learn.microsoft.com/en-us/rest/api/synapse/private-endpoint-connections)
- **Base URL:** `https://management.azure.com`

#### Tags

- Networking
- Private Endpoint
- Resource Manager
- Security

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/synapse/private-endpoint-connections)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/synapse/resource-manager/Microsoft.Synapse/stable/2021-06-01/privateEndpointConnections.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-synapse-analytics-private-endpoint-connections-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-synapse-analytics-private-endpoint-connections.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-synapse-analytics-private-endpoint-connections.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/azure-synapse-analytics-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Synapse Private Link Hubs API

Manage private link hubs that enable connecting to Synapse Studio through Azure Private Link. Provides centralized private connectivity for workspace management operations.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/private-link-hubs](https://learn.microsoft.com/en-us/rest/api/synapse/private-link-hubs)
- **Base URL:** `https://management.azure.com`

#### Tags

- Networking
- Private Link Hub
- Resource Manager
- Security

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/synapse/private-link-hubs)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/synapse/resource-manager/Microsoft.Synapse/stable/2021-06-01/privatelinkhub.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-synapse-analytics-private-link-hubs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-synapse-analytics-private-link-hubs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-synapse-analytics-private-link-hubs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/azure-synapse-analytics-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Synapse Kusto Pools API

Manage Data Explorer (Kusto) pools within a Synapse workspace for real-time log and telemetry analytics. Supports creating pools, databases, and managing data connections.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/kusto-pools](https://learn.microsoft.com/en-us/rest/api/synapse/kusto-pools)
- **Base URL:** `https://management.azure.com`

#### Tags

- Data Explorer
- Kusto Pool
- Real-Time Analytics
- Resource Manager

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/synapse/kusto-pools)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/synapse/resource-manager/Microsoft.Synapse/preview/2021-06-01-preview/kustoPool.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-synapse-analytics-kusto-pools-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-synapse-analytics-kusto-pools.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-synapse-analytics-kusto-pools.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/azure-synapse-analytics-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Synapse Azure AD Only Authentication API

Manage Azure Active Directory only authentication settings for Synapse workspaces. Enables enforcing Azure AD authentication and disabling SQL authentication for enhanced security.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/azure-ad-only-authentications](https://learn.microsoft.com/en-us/rest/api/synapse/azure-ad-only-authentications)
- **Base URL:** `https://management.azure.com`

#### Tags

- Authentication
- Azure Active Directory
- Resource Manager
- Security

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/synapse/azure-ad-only-authentications)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/synapse/resource-manager/Microsoft.Synapse/stable/2021-06-01/azureADOnlyAuthentication.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-synapse-analytics-azure-ad-only-auth-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-synapse-analytics-azure-ad-only-auth.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-synapse-analytics-azure-ad-only-auth.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/azure-synapse-analytics-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Synapse Spark Configuration API

Create and manage reusable Spark configuration artifacts for Synapse Spark pools. Supports defining Spark properties, environment variables, and package requirements as shareable configurations.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/spark-configuration](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/spark-configuration)
- **Base URL:** `https://{workspaceName}.dev.azuresynapse.net`

#### Tags

- Configuration
- Data Plane
- Spark
- Spark Configuration

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/spark-configuration)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/synapse/data-plane/Microsoft.Synapse/preview/2021-06-01-preview/sparkConfigurations.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-synapse-analytics-spark-configuration-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-synapse-analytics-spark-configuration.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-synapse-analytics-spark-configuration.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/azure-synapse-analytics-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Synapse Data Flow Debug Session API

Manage data flow debug sessions for interactive testing and debugging of data flow transformations. Enables previewing data and validating transformation logic before deployment.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/data-flow-debug-session](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/data-flow-debug-session)
- **Base URL:** `https://{workspaceName}.dev.azuresynapse.net`

#### Tags

- Data Flow Debug
- Data Plane
- Data Transformation
- Debugging

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/data-flow-debug-session)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/synapse/data-plane/Microsoft.Synapse/stable/2020-12-01/artifacts.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-synapse-analytics-data-flow-debug-session-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-synapse-analytics-data-flow-debug-session.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-synapse-analytics-data-flow-debug-session.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/azure-synapse-analytics-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Synapse Credential API

Manage credential artifacts used for authenticating with external data sources in Synapse workspaces. Supports creating and managing credentials referenced by linked services and datasets.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/credential](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/credential)
- **Base URL:** `https://{workspaceName}.dev.azuresynapse.net`

#### Tags

- Authentication
- Credential
- Data Plane
- Security

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/credential)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/synapse/data-plane/Microsoft.Synapse/stable/2020-12-01/artifacts.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-synapse-analytics-credential-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-synapse-analytics-credential.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-synapse-analytics-credential.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/azure-synapse-analytics-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Synapse KQL Script API

Create and manage KQL (Kusto Query Language) scripts for querying Data Explorer pools. Supports authoring and storing KQL queries as workspace artifacts.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/kql-script](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/kql-script)
- **Base URL:** `https://{workspaceName}.dev.azuresynapse.net`

#### Tags

- Data Explorer
- Data Plane
- KQL Script
- Kusto

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/kql-script)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/synapse/data-plane/Microsoft.Synapse/preview/2021-11-01-preview/kqlScripts.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-synapse-analytics-kql-script-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-synapse-analytics-kql-script.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-synapse-analytics-kql-script.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/azure-synapse-analytics-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Synapse Link Connection API

Manage Synapse Link connections for continuous data replication from operational databases. Supports configuring and monitoring real-time data synchronization from sources like Azure Cosmos DB and Azure SQL.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/link-connection](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/link-connection)
- **Base URL:** `https://{workspaceName}.dev.azuresynapse.net`

#### Tags

- Data Plane
- Data Replication
- Link Connection
- Real-Time Analytics

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/link-connection)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/synapse/data-plane/Microsoft.Synapse/preview/2023-04-18-preview/linkConnections.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-synapse-analytics-link-connection-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-synapse-analytics-link-connection.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-synapse-analytics-link-connection.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/azure-synapse-analytics-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Portal](https://portal.azure.com/)
- [Documentation](https://learn.microsoft.com/en-us/azure/synapse-analytics/)
- [Getting Started](https://learn.microsoft.com/en-us/azure/synapse-analytics/get-started)
- [Authentication](https://learn.microsoft.com/en-us/azure/synapse-analytics/security/synapse-workspace-security-overview)
- [Changelog](https://learn.microsoft.com/en-us/azure/synapse-analytics/whats-new)
- [Blog](https://techcommunity.microsoft.com/category/azuredatabases/blog/azuresynapseanalyticsblog)
- [Status Page](https://status.azure.com/)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/synapse-analytics/)
- [Best  Practices](https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-best-practices)
- [Security](https://learn.microsoft.com/en-us/azure/synapse-analytics/security/synapse-workspace-security-overview)
- [Support](https://azure.microsoft.com/en-us/support/)
- [Terms of Service](https://azure.microsoft.com/en-us/support/legal/)
- [Privacy Policy](https://privacy.microsoft.com/en-us/privacystatement)
- [GitHub Organization](https://github.com/Azure)
- [S D Ks](https://learn.microsoft.com/en-us/azure/synapse-analytics/)
- [S D K -  Python](https://pypi.org/project/azure-synapse-artifacts/)
- [S D K - . N E T](https://www.nuget.org/packages/Azure.ResourceManager.Synapse/)
- [S D K -  Java](https://learn.microsoft.com/en-us/java/api/overview/azure/analytics-synapse-artifacts-readme)
- [S D K -  Java Script](https://www.npmjs.com/package/@azure/synapse-artifacts)
- [Community](https://techcommunity.microsoft.com/category/azuredatabases/blog/azuresynapseanalyticsblog)
- [Website](https://azure.microsoft.com/en-us/products/synapse-analytics)
- [Login](https://portal.azure.com/)
- [Sign Up](https://azure.microsoft.com/en-us/free/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com/
