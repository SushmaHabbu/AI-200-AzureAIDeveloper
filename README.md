# AI-200-AzureAIDeveloper
AI-200 Labs

## AI-200 Labs: Developing AI Cloud Solutions on Azure

This personal learning workspace organizes practice for **AI-200: Developing AI Cloud Solutions on Azure**. It contains documentation and blank learning notes; I will write the implementation code myself in each lab folder.

### Official references

- [Microsoft learning repository](https://github.com/MicrosoftLearning/mslearn-azure-ai)
- [Microsoft lab catalogue](https://microsoftlearning.github.io/mslearn-azure-ai/)
- [Official course: Develop AI cloud solutions on Azure](https://learn.microsoft.com/en-us/training/courses/ai-200t00/)
- [AI-200 exam study guide](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/ai-200)

Baseline date: **2026-09-09**. The official catalogue was accessed on **2026-09-09** and compared with the requested 26-lab baseline. All 26 exercise links and catalogue titles matched, with no added, removed, or substituted labs. The catalogue orders the topic areas differently; this workspace keeps the requested numbered order. Individual exercise pages were not separately checked for availability.

### Learning workflow and safety

1. Open a lab below and follow its official exercise instructions, checking the latest prerequisites, subscription requirements, permissions, regional availability, and quotas before starting.
2. Write your own implementation code inside the corresponding lab folder. No Microsoft starter code has been downloaded as part of this workspace setup.
3. Record setup details, implementation notes, validation results, and resources created in that lab's README. Leave the checklist unchecked until you have completed the exercise yourself.
4. Clean up Azure resources as directed by the official exercise and record what was removed or retained.

**Cost warning:** Labs may create billable Azure resources. Check pricing and subscription requirements before starting, and verify cleanup afterward to avoid ongoing charges.

**Secrets warning:** Do not commit credentials, tokens, connection strings, or other secrets. Keep secrets out of source files, notes, screenshots, and captured command output.

### Folder tree

Each leaf-level lab folder contains its own README. Git metadata is omitted.

```text
README.md
labs/
|-- 01-container-hosting/
|   |-- 01-acr-tasks/
|   |   `-- README.md
|   |-- 02-app-service-container/
|   |   `-- README.md
|   `-- 03-app-service-sidecar/
|       `-- README.md
|-- 02-container-apps/
|   |-- 01-deploy-backend-api/
|   |   `-- README.md
|   |-- 02-troubleshoot-deployment/
|   |   `-- README.md
|   `-- 03-keda-autoscaling/
|       `-- README.md
|-- 03-azure-kubernetes-service/
|   |-- 01-deploy-inference-api/
|   |   `-- README.md
|   |-- 02-configure-apps/
|   |   `-- README.md
|   `-- 03-troubleshoot-apps/
|       `-- README.md
|-- 04-cosmos-db/
|   |-- 01-rag-document-store/
|   |   `-- README.md
|   |-- 02-semantic-search/
|   |   `-- README.md
|   `-- 03-optimize-vector-indexes/
|       `-- README.md
|-- 05-postgresql/
|   |-- 01-agent-tool-backend/
|   |   `-- README.md
|   |-- 02-vector-search/
|   |   `-- README.md
|   `-- 03-optimize-vector-search/
|       `-- README.md
|-- 06-managed-redis/
|   |-- 01-data-operations/
|   |   `-- README.md
|   |-- 02-publish-subscribe/
|   |   `-- README.md
|   `-- 03-semantic-search/
|       `-- README.md
|-- 07-integrate-services/
|   |-- 01-service-bus-messages/
|   |   `-- README.md
|   |-- 02-event-grid-events/
|   |   `-- README.md
|   |-- 03-functions-mcp-server/
|   |   `-- README.md
|   `-- 04-durable-functions-workflow/
|       `-- README.md
|-- 08-secrets-configuration/
|   |-- 01-key-vault-secrets/
|   |   `-- README.md
|   `-- 02-app-configuration/
|       `-- README.md
`-- 09-monitoring/
	|-- 01-opentelemetry/
	|   `-- README.md
	`-- 02-kql-queries/
		`-- README.md
```

### Completion checklist

#### 01 - Container hosting

- [ ] [Build and run a container image with ACR Tasks](labs/01-container-hosting/01-acr-tasks/README.md)
- [ ] [Deploy a container to Azure App Service](labs/01-container-hosting/02-app-service-container/README.md)
- [ ] [Deploy an AI API with a local model-serving sidecar](labs/01-container-hosting/03-app-service-sidecar/README.md)

#### 02 - Container Apps

- [ ] [Deploy a containerized backend API to Container Apps](labs/02-container-apps/01-deploy-backend-api/README.md)
- [ ] [Diagnose and fix a failing deployment](labs/02-container-apps/02-troubleshoot-deployment/README.md)
- [ ] [Configure autoscaling for an API using KEDA](labs/02-container-apps/03-keda-autoscaling/README.md)

#### 03 - Azure Kubernetes Service

- [ ] [Deploy an AI inference API to Azure Kubernetes Service](labs/03-azure-kubernetes-service/01-deploy-inference-api/README.md)
- [ ] [Configure apps on Azure Kubernetes Service](labs/03-azure-kubernetes-service/02-configure-apps/README.md)
- [ ] [Troubleshoot apps on Azure Kubernetes Service](labs/03-azure-kubernetes-service/03-troubleshoot-apps/README.md)

#### 04 - Cosmos DB

- [ ] [Build a RAG document store on Azure Cosmos DB for NoSQL](labs/04-cosmos-db/01-rag-document-store/README.md)
- [ ] [Build a semantic search application with Azure Cosmos DB for NoSQL](labs/04-cosmos-db/02-semantic-search/README.md)
- [ ] [Optimize query performance with vector indexes on Azure Cosmos DB for NoSQL](labs/04-cosmos-db/03-optimize-vector-indexes/README.md)

#### 05 - PostgreSQL

- [ ] [Build an agent tool backend on Azure Database for PostgreSQL](labs/05-postgresql/01-agent-tool-backend/README.md)
- [ ] [Implement vector search on Azure Database for PostgreSQL](labs/05-postgresql/02-vector-search/README.md)
- [ ] [Optimize vector search performance in Azure Database for PostgreSQL](labs/05-postgresql/03-optimize-vector-search/README.md)

#### 06 - Managed Redis

- [ ] [Perform data operations in Azure Managed Redis](labs/06-managed-redis/01-data-operations/README.md)
- [ ] [Publish and subscribe to events in Azure Managed Redis](labs/06-managed-redis/02-publish-subscribe/README.md)
- [ ] [Implement semantic search in Azure Managed Redis](labs/06-managed-redis/03-semantic-search/README.md)

#### 07 - Integrate services

- [ ] [Process messages with Azure Service Bus](labs/07-integrate-services/01-service-bus-messages/README.md)
- [ ] [Publish and receive events with Azure Event Grid](labs/07-integrate-services/02-event-grid-events/README.md)
- [ ] [Create an MCP server with Azure Functions](labs/07-integrate-services/03-functions-mcp-server/README.md)
- [ ] [Build a durable document-processing workflow with Azure Durable Functions](labs/07-integrate-services/04-durable-functions-workflow/README.md)

#### 08 - Secrets and configuration

- [ ] [Manage secrets with Azure Key Vault](labs/08-secrets-configuration/01-key-vault-secrets/README.md)
- [ ] [Retrieve settings and secrets from Azure App Configuration](labs/08-secrets-configuration/02-app-configuration/README.md)

#### 09 - Monitoring

- [ ] [Instrument an app with the OpenTelemetry SDK](labs/09-monitoring/01-opentelemetry/README.md)
- [ ] [Query logs with KQL](labs/09-monitoring/02-kql-queries/README.md)

---
*AI disclosure: The "AI-200 Labs: Developing AI Cloud Solutions on Azure" section, including its references, workflow and safety guidance, folder tree, and completion checklist, was generated by GitHub Copilot. The original repository heading and "AI-200 Labs" line above it were preserved.*

