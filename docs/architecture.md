# Architecture  

The Nebula Enterprise Agent MVP is organized into several layers:  

- **Interface Layer**: built with React/Next.js to provide chat interfaces and dashboards.  
- **Orchestration Layer**: uses frameworks like LangChain or Autogen to manage multi-agent flows, prompt management and tool calls.  
- **Memory Layer**: uses Nebula or a vector database like Pinecone/Qdrant to store interaction history and embeddings.  
- **Tool Integration Layer**: connectors for external services (Slack, CRM, databases).  
- **Infrastructure Layer**: containerized with Docker, orchestrated via Kubernetes, with CI/CD using GitHub Actions.  

Refer to the root README for getting started.
