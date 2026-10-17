# internal-support-agent

An AI support agent that answers internal IT helpdesk and HR policy questions from company documents and can create support tickets, running on a local LLM through Ollama.

**Status:** early development. Nothing is runnable yet.

## Planned features
- Answers grounded in IT runbooks and HR policies, with cited sources (RAG with PostgreSQL + pgvector)
- Tools served through an MCP server (ticket system, user directory), mock data only
- Role-based access to documents and tools
- Guardrails and prompt-injection tests
- Automated evaluation in CI (promptfoo)
- Tracing with OpenTelemetry
- Docker Compose for local use, Helm chart for Kubernetes (Kind)

## License
MIT, see [LICENSE](LICENSE).
