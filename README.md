# Azure Synapse Analytics (microsoft-azure-synapse-analytics)
Azure Synapse Analytics is an enterprise analytics service that accelerates time to insight across data warehouses and big data systems. It brings together the best of SQL technologies used in enterprise data warehousing, Spark technologies for big data, and Pipelines for data integration and ETL/ELT.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/microsoft-azure-synapse-analytics/refs/heads/main/apis.yml)

## Tags:

 - Analytics, Apache Spark, Big Data, Data Integration, Data Warehouse, ETL, SQL

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-28

## APIs

### Synapse Workspace API
Manage Synapse workspaces including creation, configuration, and lifecycle management of analytics environments through Azure Resource Manager.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/](https://learn.microsoft.com/en-us/rest/api/synapse/)

### Synapse SQL Pools API
Manage dedicated SQL pools for enterprise data warehousing workloads including provisioning, scaling, pausing, and resuming compute resources.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/sqlpools](https://learn.microsoft.com/en-us/rest/api/synapse/sqlpools)

### Synapse Spark Pools API
Manage Apache Spark pools for big data processing including pool creation, auto-scaling configuration, and Spark runtime version management.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/bigdatapool](https://learn.microsoft.com/en-us/rest/api/synapse/bigdatapool)

### Synapse Pipeline API
Create and manage data integration pipelines for ETL/ELT workflows. Supports orchestrating data movement and transformation activities across diverse data stores.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/pipeline](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/pipeline)

### Synapse Spark Job API
Submit and manage Apache Spark batch jobs and interactive sessions. Provides operations for monitoring job status, retrieving logs, and cancelling running applications.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/spark](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/spark)

### Synapse Monitoring API
Monitor pipeline runs, Spark jobs, and SQL requests within a Synapse workspace. Provides visibility into execution status, performance metrics, and operational health.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/monitoring](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/monitoring)

### Synapse Link API
Manage Azure Synapse Link for real-time analytics over operational data. Enables hybrid transactional and analytical processing without impacting operational workloads.

**Human URL:** [https://learn.microsoft.com/en-us/azure/synapse-analytics/synapse-link/](https://learn.microsoft.com/en-us/azure/synapse-analytics/synapse-link/)

### Synapse Access Control API
Manage role assignments, role definitions, and access control for Synapse workspace resources. Supports Synapse role-based access control for fine-grained permissions.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/role-assignments](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/role-assignments)

### Synapse Notebook API
Create, update, list, and delete notebooks within a Synapse workspace. Notebooks support interactive data exploration using Python, Scala, SQL, and .NET languages.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/notebook](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/notebook)

### Synapse Dataset API
Create and manage datasets that represent data structures within linked data stores. Datasets define the schema and location of data used in pipelines and data flows.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/dataset](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/dataset)

### Synapse Linked Service API
Create and manage linked services that define connection information to external data sources. Linked services act as connection strings for integrating with databases, storage, and other services.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/linked-service](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/linked-service)

### Synapse Data Flow API
Create and manage data flows for visual data transformation logic. Data flows enable code-free data transformation at scale within Synapse pipelines.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/data-flow](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/data-flow)

### Synapse SQL Script API
Create, update, list, and delete SQL scripts within a Synapse workspace. SQL scripts can target both dedicated and serverless SQL pools for querying and data management.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/sql-script](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/sql-script)

### Synapse Trigger API
Create and manage triggers that orchestrate pipeline execution. Supports schedule-based, tumbling window, and event-based triggers for automated workflow execution.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/trigger](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/trigger)

### Synapse Spark Job Definition API
Create and manage Spark job definitions as reusable templates for batch processing. Spark job definitions encapsulate configuration, code, and dependencies for repeatable execution.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/spark-job-definition](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/spark-job-definition)

### Synapse Managed Private Endpoints API
Create and manage managed private endpoints within a Synapse managed virtual network. Enables secure, private connectivity to Azure resources without exposing traffic to the public internet.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/managed-private-endpoints](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/managed-private-endpoints)

### Synapse Integration Runtimes API
Manage integration runtimes that provide the compute infrastructure for data integration activities. Supports Azure-hosted, self-hosted, and Azure-SSIS integration runtime types.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/integration-runtimes](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/integration-runtimes)

### Synapse Library API
Manage workspace libraries including JAR files, Python wheels, and other packages used by Spark pools. Supports uploading, listing, and deleting library resources.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/library](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/library)

### Synapse Git Integration API
Manage Git repository integration for Synapse workspaces. Enables source control for workspace artifacts including pipelines, notebooks, and data flows through Git-based version control.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/git-integration](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/git-integration)

### Synapse Firewall Rules API
Manage IP firewall rules for Synapse workspaces to control network access. Supports creating, updating, and deleting server-level IP firewall rules for workspace security.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/ip-firewall-rules](https://learn.microsoft.com/en-us/rest/api/synapse/ip-firewall-rules)

### Synapse Keys API
Manage workspace encryption keys for data protection at rest. Supports customer-managed key configuration for dedicated SQL pools and workspace-level encryption.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/keys](https://learn.microsoft.com/en-us/rest/api/synapse/keys)

### Synapse Private Endpoint Connections API
Manage private endpoint connections to Synapse workspaces. Enables approval and management of private link connections for secure access from virtual networks.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/private-endpoint-connections](https://learn.microsoft.com/en-us/rest/api/synapse/private-endpoint-connections)

### Synapse Private Link Hubs API
Manage private link hubs that enable connecting to Synapse Studio through Azure Private Link. Provides centralized private connectivity for workspace management operations.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/private-link-hubs](https://learn.microsoft.com/en-us/rest/api/synapse/private-link-hubs)

### Synapse Kusto Pools API
Manage Data Explorer (Kusto) pools within a Synapse workspace for real-time log and telemetry analytics. Supports creating pools, databases, and managing data connections.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/kusto-pools](https://learn.microsoft.com/en-us/rest/api/synapse/kusto-pools)

### Synapse Azure AD Only Authentication API
Manage Azure Active Directory only authentication settings for Synapse workspaces. Enables enforcing Azure AD authentication and disabling SQL authentication for enhanced security.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/azure-ad-only-authentications](https://learn.microsoft.com/en-us/rest/api/synapse/azure-ad-only-authentications)

### Synapse Spark Configuration API
Create and manage reusable Spark configuration artifacts for Synapse Spark pools. Supports defining Spark properties, environment variables, and package requirements as shareable configurations.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/spark-configuration](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/spark-configuration)

### Synapse Data Flow Debug Session API
Manage data flow debug sessions for interactive testing and debugging of data flow transformations. Enables previewing data and validating transformation logic before deployment.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/data-flow-debug-session](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/data-flow-debug-session)

### Synapse Credential API
Manage credential artifacts used for authenticating with external data sources in Synapse workspaces. Supports creating and managing credentials referenced by linked services and datasets.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/credential](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/credential)

### Synapse KQL Script API
Create and manage KQL (Kusto Query Language) scripts for querying Data Explorer pools. Supports authoring and storing KQL queries as workspace artifacts.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/kql-script](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/kql-script)

### Synapse Link Connection API
Manage Synapse Link connections for continuous data replication from operational databases. Supports configuring and monitoring real-time data synchronization from sources like Azure Cosmos DB and Azure SQL.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/link-connection](https://learn.microsoft.com/en-us/rest/api/synapse/data-plane/link-connection)

## Common Properties

- [Portal](https://portal.azure.com/)
- [Documentation](https://learn.microsoft.com/en-us/azure/synapse-analytics/)
- [Getting Started](https://learn.microsoft.com/en-us/azure/synapse-analytics/get-started)
- [Authentication](https://learn.microsoft.com/en-us/azure/synapse-analytics/security/synapse-workspace-security-overview)
- [Change Log](https://learn.microsoft.com/en-us/azure/synapse-analytics/whats-new)
- [Blog](https://techcommunity.microsoft.com/category/azuredatabases/blog/azuresynapseanalyticsblog)
- [Status](https://status.azure.com/)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/synapse-analytics/)
- [Best Practices](https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-best-practices)
- [Security](https://learn.microsoft.com/en-us/azure/synapse-analytics/security/synapse-workspace-security-overview)
- [Support](https://azure.microsoft.com/en-us/support/)
- [Terms of Service](https://azure.microsoft.com/en-us/support/legal/)
- [Privacy Policy](https://privacy.microsoft.com/en-us/privacystatement)
- [GitHub Organization](https://github.com/Azure)
- [SDK - Python](https://pypi.org/project/azure-synapse-artifacts/)
- [SDK - .NET](https://www.nuget.org/packages/Azure.ResourceManager.Synapse/)
- [SDK - Java](https://learn.microsoft.com/en-us/java/api/overview/azure/analytics-synapse-artifacts-readme)
- [SDK - JavaScript](https://www.npmjs.com/package/@azure/synapse-artifacts)
- [Website](https://azure.microsoft.com/en-us/products/synapse-analytics)
- [Login](https://portal.azure.com/)
- [Sign Up](https://azure.microsoft.com/en-us/free/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
